# ACD_JAVAB_Session_7_Assignment_3_Main

package exceptionHandling;

public class NullPointerExceptionClass {

	public void example(String name){
	System.out.println("No Exception");
	
	}
	
	    public static void main(String[] args)
	    {
	    	NullPointerExceptionClass obj = null;
	    	try{
	        obj.example("Abhinav");
	    	}catch(NullPointerException e){
	    		System.out.println("The Exception is "+e);
	    	}
	    	finally{System.out.println("Null Pointer Exception code is completed");}
	    }
	    
}

