# star_triangle
how to create * triangle  using c language

In this program i used a A.P formula to print spaces and star.
In this program we observe that before printing star we will have to print spaces 
in first line 3 spaces , in second line 2 spaces , in thrid line 1 spaces , and fourth line 0 spaces
it means spaces    3,2,1,0
we are observing spaces are decreasing by 2-3=-1.(NOw we will use Arithmetic progression formula)
a =First term  , d= difference between two successive terms ,Tn =n'th  term.
there a=3,  d=2-3=-1, 
Tn=a+(n-1)*d
now we will use i in place of n as nth term.

Tn=3+(i-1)*-1;
Tn= 3-i+1;
Tn=4-i;
this condition we will use to print spaces


Now we are observing stars  1,3,5,7 in lines  
a=1,d=3-1=2;
a=1, d=2;
Tn= a+(n-1)*d;  
Tn = 1+(i-1)*2; //  i as nth term
Tn= 1+2*i-2;
Tn= 2*i-1;  
This condition we will use to print starts

