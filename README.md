#include <stdio.h>
#include <iostream>

 int main()
 {
     int edad;
     std::cout << "ingresa la edad";
     std::cin >> edad;
     
     if (edad >=18) {
         std::cout <<"usted es mayor de edad: " << std::endl;
         }else {
             std::cout << "usted es menor de edad: " << std::endl;
         }
         return 0;
     }