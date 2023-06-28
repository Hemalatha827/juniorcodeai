# Common Features and Differences in Function Syntax of Various Programming Languages

# Functions:
  Function is a block of code that perform a specific task.
  
# Why we need functions in programming language
•	To improve the readability of the code so that other programmers can easily understand your code well.

•	To improve the reusability of the code so that same function can be used in any program rather than writing from scratch

•	Debugging the code will be easier if you use functions as errors are easily traced.

•	Reduce the size of the code.

# Types of Functions:
1.Pre defined functions:
   Standard library functions are also know as built in functions. Functions as printf(), scanf() are standard library functions. These functions are defined with .h extensions are called header files as stdio.h
   
2.User defined functions
The functions that can be created by the user is known as user defined function.
Syntax:
 return_type  function_name(argument_list){
         set of statements—block of code
}
return_type: Return type can be of any data type such as int, double, char, void, short etc. 

function_name: It can be anything, however it is advised to have a meaningful name for the functions so that it would be easy to understand the purpose of function just by seeing it’s name.

argument list: Argument list contains variables names along with their data types. These arguments are kind of inputs for the function. For example – A function which is used to add two integer variables, will be having two integer argument.

Block of code: Set of statements, which will be executed whenever a call will be made to the function.

Let’s see an example of  how to use functions in various programming langauges

Javascript-> In Javascript function is defined as follows
```
function add(){
            const num1 = 5;
            const num2 = 3;

        // add two numbers
        const sum = num1 + num2;

            // display the sum
            console.log('The sum of ' + num1 + ' and ' + num2 + ' is: ' + sum);
        }
        add();
```
C--> In C function is defined as follows
```
#include<stdio.h>
void add();                                               //Function Declaration
int main()
{
  add();                                                  //Function Calling
  return 0;
}
void add()                                                //Function Definition
{
   int a,b,c;
   printf("\nEnter The Two values:");
   scanf("%d%d",&a,&b);
   c=a+b;
   printf("Addition:%d",c);
}
```
TypeScript--> In Typescript function is defined as follows

```
function addtwonumbers(a: number, b: number){ 
  return a + b; 
  } 
 var sum: number = addtwonumbers(10, 15) 
console.log('Sum of the two numbers is: ' +sum); 
```
 Dart--> In Dart function is defined as follows
 ```
void main() { 
   var num1 = 101; 
   var num2 = 2; 
   var res = 0; 
   
   res = num1+num2; 
   print("Addition: ${res}");
}

```
PHP--> In PHP  function is defined as follows
 ```
 function add($a,$b)
{
$c=$a+$b;
echo $c;
}

echo "sum of 2  numbers is";

//calling a function

add(1, 2);
```

Java--> In Java function is defined as follows
 ```
import java.util.*;

public class Main{
    
    public static int sum(int num1, int num2){
        int ans = num1 + num2;
        return ans;
    }
    
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        
        System.out.println("Enter the first number: ");
        int n1 = sc.nextInt();
        
        System.out.println("Enter the second number: ");
        int n2 = sc.nextInt();
        
        int sum = sum(n1,n2);
        
        System.out.println("The sum of "+n1+" and "+n2+" is "+sum);
        
    }
    
    
}
```

Kotlin --> In Kotlin function is defined as follows
```
 fun main(args: Array<String>) {
    val x: Int = 10
    val y: Int = 25

    val z = x + y

    println("The sum of $x + $y is  $z")
}
```
Swift --> In Swift function is defined as follows
```
func add(a: Int, b: Int) {
    let result = a + b
    print("The result is \(result)")
}
 
add(a: 4, b: 3)
```
Golang --> In Golang function ius defined as follows
```
package main

import "fmt"

func main()  {
    var sum int
    
    num1 := 10
    num2 := 25

    sum = num1 + num2

    fmt.Println("The Sum of num1 and num2  = ", sum)
}
```
C++---> In C++ function is defined as follows
```
  
int add(int a, int b) {  
    return a + b;  
}  
int main() {  
    int num1, num2, sum;  
    cout << "Enter two numbers: ";  
    cin >> num1 >> num2;  
  
    sum = add(num1, num2);  
    cout << "Sum of " << num1 << " and " << num2 << " is: " << sum << endl;  
    return 0;  
}  
```
Objective C--> In Objective function can be defined as follows 

``` 
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[]){
    @autoreleasepool {
        int a, b;

        NSLog(@"Enter value for a:\n");
        scanf("%i", &a);

        NSLog(@"Enter value of b:\n");
        scanf("%i", &b);

        int sum = a + b;

        NSLog(@"Sum of two numbers:\t%i\n", sum);
    }
    return 0;
}
 
```

 This is will  give overview of functions and its syntax for writing various functions using different programmming languages 
  


  






