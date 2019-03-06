# Logic-Code
import java.util.*;
    public class TruthAssignment{
	
   //initializing values for the body of the code
	String[] myStringArray;
	boolean[] mybooleanArray;
	
	public static void main(String[] args) {
		//declaration of the array of strings 
				
	}
	//creating a constructor that returns false in all cases
	public  TruthAssignment(){
		String[] myStringArray = new String [1];
		String[] myStringArray11 = new String[] {"F"};
	}
		
// Array of string with proposition constant
	public void TruthAssignment1(){
		//declaration of the array of strings 
		String[] myStringArray = new String [1];
		String[] myStringArray11 = new String[] {"F"};
		Arrays.fill(myStringArray, false);
	}
	
	//Array of a logical sentence
	public void TruthAssignment2() {
	char charArray[];
	charArray = new char[] {'p','v','q','v','r'};
	//Creating a Map assignment in which proposition constant is assigned to boolean value
	  Map< String ,String> hm =  
              new HashMap< String,String>(); 
hm.put("F", new String("p" + "v"+ "q" + "v" + "r")); 
 

// Returns Set view      
Set< Map.Entry< String,String> > st = hm.entrySet();    

for (Map.Entry< String,String> me:st) 
{ 
 System.out.print(me.getKey()+":"); 
 System.out.println(me.getValue()); 
} 


	
	
		
	}
}



public class TestTruthAssignment {
	public static void main(String[] args) {
	TruthAssignment myTruthAssignmnet = new TruthAssignment();
	String[] Array = new String[5];
	String[] Array1 = {"p" + "q" + "r"};
	}
	}
