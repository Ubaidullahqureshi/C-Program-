#include<iostream>
	
	
using namespace std;
	
	
	
	int main(){
	
	
	
		int trynum = 0;
		char c;
		
	
	
	
	
	do {
			cout << "Please Enter a character between a-z for guesing ";
			cin >> c;
			
	
	
	
	
	
				if ( c == 'z' ){
				cout << "Congratuation !  You Guess is Correct ";
				trynum = 6;
			}
			
	
	
	
	
				else {
				trynum = trynum + 1;
			
	
	
	
			}
		
	
	
	
		}
		
	
	
	
	
	
	
			while ( trynum <= 5 &&  c != 'z');
		
	
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
		return 0;
	
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
					  
}
