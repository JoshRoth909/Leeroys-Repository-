
```java



public class Codewars {
  public static String oddOrEven (int[] array) {
  int sum = 0; 

    for(int i = 0; i < array.length; i++) {
      int num = array[i];
   
      sum = sum + num; // 41 + 6;

    }
    return (sum % 2 == 0) ? "even" : "odd";
  }
}
```
