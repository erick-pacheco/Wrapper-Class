# Terminology: wrapper class 
an object that encapsulates primitive types into one of the classes from the java.lang package: Boolean, Byte, Character, Double, Float, Integer, Long or Short to provide additional methods. In other words, converts primitive types into Objects.

```java
/* print array elements */ 

public class Main {
  public static void main(String[] args) {
      
    int[] numbers = {3, 7, 5, 20};
    
    /* The for each loop converts an array to their own object with a new type 
     * in this case, the new variable number of type int */  
    for (int number: numbers) {
      System.out.println(number);
    }
  }
}
```