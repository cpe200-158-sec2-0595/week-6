# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code

![](http://www.uppic.biz/images/2015/10/02/AnimalWorld.png)

2. Detail explaination about the identified pattern and all the parcipants

  This program is simulating the world of animals. Which has 2 Continents. One is Africa and another is America.
Each of continent has 2 type of animal. A Carnivore and a herbivore. For instance, Africa has a lion and a wildebeast, While America has a wolf and a bison. The program is create a world and simulate animal food chain. At the end. It will conclude the result that which one animal is eater and which one is eaten.

  At first. The program create the whole world. Which contain <Continent> and <Animal>. Then seperate <Continent> which we see as AbstractFactory into two side which is <Africa> and <America> which are ConcreteFactory. And then divide the AbstractFactory <animal> to another AbstractFactory <Carnivore> and <Herbivore> and finally create a ConcreteFactory <AnimalName> from it.

3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
  ![](http://www.uppic.biz/images/2015/10/02/AnimalWorld2.png) 
  

  - Test the new requirment by modifying the main function and show the result.
   ![](http://www.uppic.biz/images/2015/10/02/Screenshot_2015-10-02_17.png)
  
  - Show the main function and snippet of C# code that is related to the process.
  - ![](http://www.uppic.biz/images/2015/10/02/Screenshot_2015-10-02_17SWkNn.png)
  - ![](http://www.uppic.biz/images/2015/10/02/Screenshot_2015-10-02_17W4uXz.png)
  - ![](http://www.uppic.biz/images/2015/10/02/Screenshot_2015-10-02_17suOTg.png)

