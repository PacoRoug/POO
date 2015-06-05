public class enterosCumplen{

	public static void enterosCumplen(){
		int a,
		    b=1;
		double e;

		for(a=500;a>0;a= a-1){
			b=1;
			while(b<499){
				if((a*a+b*b+1)%(a*b)==0 && b>a){
					System.out.println(a +" " +b );
				
				}
				b=b+1;
									
			}
	
		}

	}
	

	public static void imprimeSerie(int howMany,int lineLenght){
		int contador=0;
		
		while(contador<howMany){
			for(int a=0;a<lineLenght+1;a=a+1){
				if(contador<howMany){
					if (a%3==0 && a+2<=lineLenght ){
						System.out.print("[");
						
					}
					if ((a-1)%3==0 && a+1<=lineLenght  ){
						contador=contador+1;
						System.out.print(contador);
					
					}
					if ((a+1)%3==0 && a<=lineLenght){
						System.out.print("]");
					}
					
				}
					
			
			}
		if (contador<howMany){
			System.out.println(" ");
		}
		else {
			System.out.println("]");
		}
			
		}
		
		
		
	}

	public static void main(String[] args){

		enterosCumplen();
		imprimeSerie(9,11);
	}


}
