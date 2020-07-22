# DESIGNPATTERNS
package behavioural;

public class IteratorPatternDemo {

	public static void main(String[] args) {
		 CollectionofNames cORepository = new CollectionofNames();  
         
         for(Iterator iter = cORepository.getIterator(); iter.hasNext();){  
             String name = (String)iter.next();  
             System.out.println("Name : " + name);  
          }      
	}

}
