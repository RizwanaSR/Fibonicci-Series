# Fibonicci-Series
class FibonicciExample1{
public static void main(String[] args){
int n1=0,n2=1,n3,i,count=10;
System.out.println(n1+" "+n2);//printing 0 and 1
for(i=2;i<count;++i);//loop start with 2 because 0 and 1 already printed
{
n3=n1+n2;
System.out.println(" "+n3);
n1=n2;
n2=n3;
}
}}
