# Modulo topic

## short symbols
- I=Intersection
- U=Union

# Main topic


>a(mod x)={a+nx: x in N}=a+0(mod x) **TODO:What are the special properties 0(mod x) and 1(mod x) have compared to  a(mod x) 
I feel like it has some more benefit**
>
>(a+b)(mod x)=a(mod x)+b(mod x)
>
>a(mod 1)=N
>
>a(mod x)=a(mod x1) I a(mod x2) I a(mod x3) .... where x=lcd(x1.x2.x3.....)
>that's mean a(mod x) subset of a(mod x1),a(mod x2)..
>
>a(mod x) I b(mod x) =null for a(mod x)!=b(mod x)
>
>x\*a(mod x)=0(mod x) That's where 0(mod x) is important.
>
>x1\*a(mod x)=x1\*a(mod x1) I x1\*a(mod x2) .....
>or,x1\*a(mod x)=0(mod x1) I x1\*a(mod x2)

Let's suppose the only thing function takes is a set.
So it don't takes number.when I say f(1) it actually means f({1}).
>Here f(A)={f(x):x in A}
The speciality of set with other math abstruction is that it only knows what is in it. It doesn't know 
where is it in the set, how many of one thing is there. It just knows if its there or not.
So,if some problem need to care only the values,set is really powerful.

If it need some position use some vector.set doesn,t have position ,
So it can't have duplicate(**why is that I don't know.I just feel like it.**)

If I treat a set as number I can explain 
>a+x=a   where a=b(mod x)
>example: {....-2,0,2,4,6,8....}+2={...-2,0,2,4,6,8.....}
In simple number system a should be infinity.
 
Vector which also knows the position of the data can be expressed as function where domain of the function is position.

Now there are some properties of intersection and union.
1.f(A U B)=f(A) U f(B) where f is any function.
2.f(A I B)=f(A) I f(B) where f in one_to_one function.
3.f(A/B)=f(A)/f(B)     where f in one_to_one function.

**This is one of the most important use of symmetry for solving problem.
x->f(x)->g(x)->f-1(x)=x->g(x)**

**f(x)=x+a is a one_to_one function.**
**that means (0(mod x1) I 0(mod x2) I ....) +a=a(mod x1) I a(mod x2)....**
## proof
	if f(A)=A and f(B)=B than f(A U B)=f(A U B) , f(A I B)=f(A) I f(B) 
	beacuse f(x)=x is one_to_one function.
# Hypotheses:
>Every properties like prime number and factor etc can be explained by set and symmetry



#Problem:
##problem 1.
>A ball bounce in a rectangle,when will it go to the point (a,b).
>
##problem 2.
>We know that,
>1. 0(mod a1) I 0(mod a2)=0 (mod lcd(a1,a2))
>2. 0(mod a1) + 0(mod a2)=0 (mod gcd(a1,a2))
>Want an equation for 0(mod a1) U 0(mod a2)
>
##problem 3.
>how 0 (mod a)+0 (mod b)=0 (mod gcd(a,b))

##problem 4.
>a1 (mod x1) I a2 (mod x2)=

