# Code Blocks

Why? 

Useful for documenting our Shit Code.


Syntax:

        1. Indentation using Tab
        
        2. <TEXT> `<CODE HERE>` <TEXT> ?
        
        3. 
            ```
            <CODE HERE>
            ```

        
        4. 
            ```<LANGUAGE>
            <CODE HERE>
            ``` 

        5. 
            ```diff
            <CODE HERE>
            + <MODIFIED CODE>
            - <DELETED CODE>
            ```


<br>1.

    public class Cat{
        public static void main(String[] args){
            System.out.println("Meow");
        }
    }

<br>2.

Would this `int a = input.nextInt();` ?

<br>3.

```
public class Cat{
        public static void main(String[] args){
            System.out.println("Meow");
        }
}
```

<br>4.

```java
public class Cat{
        public static void main(String[] args){
            System.out.println("Meow");
        }
}
```

<br>5.


```diff
public class Cat{
        public static void main(String[] args){
+            System.out.println("Purr");
-            System.out.println("Meow")
        }
}
```