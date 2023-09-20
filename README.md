# My-Java-Tuts
This is my personal repo for learning the basics of Java programming language which is a requirement for my Masters degree program in Software Engineering.
I used a [Youtube video](https://youtu.be/eIrMbAQSU34?si=GVYnEl1lbVdUU1zz) by [Programming with Mosh](https://www.youtube.com/@programmingwithmosh).
> I simply followed the tutorial by practicing in a code editor (VScode) and commenting note along the code lines.
## Learnt
* Anatomy of Java
* Classes and Functions in Java
* Variables
* Data Types (Primitive and Reference)
* String Data Type
```Java
String message = "Hello padi" + "Kilode \"now\""; 
// Escape characters include: \, \n (new line), \t (tab)
System.out.println(message.length());
//The message class can take dotted methods/function like: length(), toUpperCase(), toLowerCase(), Trim(), indexOf(), replace(target: " ", replacement: " ").
```
* Arrays (2D and 3D)
```Java
//ARRAYS
        int[] numbers = new int[5];
        numbers[0] = 1;
        numbers[1] = 2;
        numbers[2] = 3;
        numbers[3] = 4;
        numbers[4] = 5;
        System.out.println(Arrays.toString(numbers));
        
        int[] number = {2, 3, 7, 1, 5, 2};
        Arrays.sort(number); //This sorts the array.
        System.out.println(number.length); //This prints the array length.
        System.out.println(Arrays.toString(number)); //This prints the Array by converting it to string.

        //2D ARRAYS
        int[][] twoDArray = new int[2][3]; // The first and second sqaure brackets represent row and column respectively.
        twoDArray [0][0] = 1;
        System.out.println(Arrays.deepToString(twoDArray));

        int[][] twoDArrayc = {{1, 2, 3}, {4, 5, 6}};
        System.out.println(Arrays.deepToString(twoDArrayc));
```
* Constants
```Java
//CONSTANTS: uses "final" for consant variable.
        final float pi = 3.14F;
        // pi = 953.2F; //final/constant variable can not be reassigned a value
```
* Arithmetic Expression
  ```Java
  //ARITHMETIC EXPRESSION
  // + => Addition
  // - => Subtraction
  // / => Division
  // * => Multiplication
  // + => Increment
  // ++ => Increment
  // -- => Decrement
        int result = 10 / 3; //This ill print 3 as the output because the output of 2 whole numbers is whole number.
        double results =  (double)10 / (double)3;
        // System.out.println(results);
        //Increment operator
        int x = 1;
        int y = x++;
        // System.out.println(y + x);
        int z = 10 + 3 * 2; //or int z = (10 + 3) * 2 = 26.
        // System.out.println(z);
        
        //Order Of Operation
        // ()
        // */
        // +-
  ```
* Casting and Type Conversion
```Java
//CASTING AND TYPE CONVERSION
        //Implicit Casting
        // byte > short > int > long (convertion tree)
        short a = 1;
        int b = a + 2;

        double c = 1.1;
        double d = c + 2;
        System.out.println(d); 

        //Explicit Casting
        double e = 1.1;
        int f = (int)e + 2;
        System.out.println(f);

        //A method that takes a string and return integer, float, short, long etc.
        short.parseShort();
        long.parseLong();
        float.parseFloat();
        double.parseDouble();
        // example
        String g = "2";
        int h = Integer.parseInt(g);
        String i = "2.1";
        double j = Double.parseDouble(i);
        // System.out.println(j);
```
* Math Class
```Java
//THE MATH CLASS
        int result0 = Math.round(1.1F); //Round the number up to the nearest whole number. Answer = 1.
        int result1 = (int)Math.ceil(1.1F); //Smaller integer that is greater than or equal to the value of this variable. Answer = 2.
        int result2 = (int)Math.floor(1.1F); // Largest integer that is smaller than or equal to the value of this variable. = 1.
        int result3 = Math.max(5, 2); // Returns the greater of two values
        int result4 = Math.min(5, 2); // Returns the smaller of two values
        double result5 = Math.random(); // Generate random value between 0-1
        //To generate value between 0-100 and etc,
        double result6 = Math.random() * 100;
        //To round the result up into a whole number,
        double result7 = Math.round (Math.random() * 100);
        //OR
        int result8 = (int)(Math.random() * 100);
        // System.out.println(result8); 
```
