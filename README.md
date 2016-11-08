# nirvana
something 
#include<stdio.h>
int main(void)
int a,b,d,i,j,k,m;
 {  
   printf ( "Enter the number :\n" );   
   scanf ( "%d", &a );    
	   b = a; 
	   m = 0; 
	   while ( b >= 10 ) { 
		   b = b / 10; 
		   m = m++; 
	   } 
	   for ( i = m; i > 0; i-- ) { 
		   d = 1; 
		   for ( j = 0; j < i; j++ ) 
			   d = d * 10; 
		   printf ( "%d", a / d ); 
		   a = a - a / d * d; 
	   } 
	   printf ( "%d \n", a % 10 );  
     
     return 0;
 }
