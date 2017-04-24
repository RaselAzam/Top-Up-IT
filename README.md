# Top-Up-IT
Top Up IT Code
//Top Up IT class Six 
//get an index from a list of number in array.
import java.util.Scanner;
public class IndexSerach{
public static void main(String[] args){
Scanner k=new Scanner(System.in);
int arr[]=new int[10];
for(int i=0;i<arr.length;i++){

arr[i]=k.nextInt();
}
Sytem.out.println("Now please a number if it exits then its index will be shown");
int a=k.nextInt();
int index=-1;
for(int g=0;g<arr.length;g++){
if(arr[g]==a){

index=g;
break;
}
if(index==-1){

System.out.println("Your inserted number is not in the list");

}
else{
system.out.println("Index of inserted number is:"+index);

}

}

}

}
