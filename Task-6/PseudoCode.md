# __PSEUDO CODE-ARMSTRONG NUMBER__
Initialize n

temp=n

sum=0

order= length of n

WHILE n>0

    digit=n%10
    sum=sum+digit**order
    n=n/10
ENDWHILE

IF sum==temp

    PRINT "IT IS AN ARMSTRONG NUMBER"
ELSE

    PRINT "IT IS NOT AN ARMSTRONG NUMBER"
