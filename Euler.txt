clear
clc
fprintf('Euler Method \n')
y=input('Enter function in terms of variable t and y=','s');
c=inline(y,'t','y');
c
t1=input('Enter the lower limit in integer=');
t2=input('Enter the upper limit in integer=');
to=input('Enter value of to=');
yo=input('Enter value of yo=');
h=input('Enter value of h=');
fprintf('      tn           yn\n')
disp([to yo])
x=t1+h;

for l=x:h:t2
    yo=yo+h*c(t1,yo);
    
    
    
    t1=t1+h;
    
    disp([t1 yo])
    
    
end