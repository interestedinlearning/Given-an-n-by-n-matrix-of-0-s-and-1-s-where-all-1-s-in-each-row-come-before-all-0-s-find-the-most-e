# Given-an-n-by-n-matrix-of-0-s-and-1-s-where-all-1-s-in-each-row-come-before-all-0-s-find-the-most-e








import java.util.*;
public class maxzro {

public static void main(String[] args)
	{
	Scanner in=new Scanner(System.in);
int m,n;
System.out.println("enter the number of rows");
m=in.nextInt();
System.out.println("enter the number of columns");
n=in.nextInt();
int a[][]=new int[m][n];
int i,j,temp=0,count=0,rowno=0;
temp=count;
System.out.println("enter the data");
for(i=0;i<m;i++) {="" for(j="0;j&lt;n;j++)" {="" a[i][j]="in.nextInt();" }="" }="" system.out.println("the="" matrix="" is");="" for(i="0;i&lt;m;i++)" {="" for(j="0;j&lt;n;j++)" {="" system.out.print("\t"+a[i][j]);="" }="" system.out.println();="" }="" for(i="0;i&lt;m;i++)" {="" count="0;" for(j="0;j&lt;n;j++)" {="" if(a[i][j]="=0)" {="" count++;="" }="" if(count="">temp)
	{
	temp=count;
	rowno=i;
	}
	}
}
System.out.println("the row number with maximum zeros is:"+(rowno+1));
	}
