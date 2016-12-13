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
   
 
 
 
 
 
   
  
