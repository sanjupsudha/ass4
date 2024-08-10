## 1. Write a chained if / else-if statement to fill in the following conditions
##    val < 5  => Tiny
##    val < 10 => Small
##    val < 15 => Medium
##    val < 20 => Large
##    val >= 20 => Huge
### ans. let val=10
###      if(val<5){
###   Console.log("tiny")};
###    else if(val<10){
###   Console.log("small")};
###   else if(val<15){
###    Console.log("Medium")};
###    else if(val<20){
###    Console.log("Large")};
###     else if(val>=20){
###     Console.log("Huge")};

## 2. Use the switch case and create an application with the following roles.
##   admin => gets full access
##   subAdmin => gets access to create and delete courses
##   testPrep => gets access to create and delete tests
##   user => gets access to consume contents
### ans. let access = "admin"
###       switch (access){
###       case "admin" :
###      Console.log("gets full access");
###        break;
###       case "subAdmin" :
###      Console.log("gets access to create and delete courses");
###        break;
###       case "testPrep" :
###      Console.log("gets access to create and delete tests");
###        break;
###        case "user" :
###      Console.log("gets access to consume contents");
###       break;
###       default:
###      Console.log("Wrong choice");}
###
