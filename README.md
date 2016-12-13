# function-1
函数声明与函数表达式

1.函数声明总是会优先于函数表达式先执行。

(1) alert(sum(10,10));

    function sum(num1,num2){
    
          return num1+num2;
          
    }
    
    //不会报错。
    
(2)alert(sum(10,10));
  
   var sum=function(num1,num2){
       
         return num1+num2;
        
   }
   
   //会报错
   
   总结：除了什么时候可以访问函数这一点区别外，函数声明与函数表达式其实是等价的。
   
 2.在javascript中，作用域是由function进行声明的，而不是代码块。
  
   声明的作用域创建于代码块，但不是终结于代码块。
   
   函数可以在其作用域范围内被提前引用，但是变量不行。每个声明项的作用域不仅取决于它的声明，还取决于它是变量还是函数。
 
 
 
 
   
  
