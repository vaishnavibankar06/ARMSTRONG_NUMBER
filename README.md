# ARMSTRONG_NUMBER
public class ArmstrongNumber {
static void armstrong(int num){
int newNum=0,remainder,temp;
temp=num;
while(temp !=0){
 remainder=temp % 10;
newNum=newNum+remainder*remainder*remainder;
temp=temp/10;
}
if(newNum==num){
System.out.println(num+"is armstrong.");
}else{
System.out.println(num+"is not armstrong.");
}
}
public static void main(String args[]){
armstrong(407);
}
}
