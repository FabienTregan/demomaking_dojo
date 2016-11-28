# demomaking_dojo
Dojo to show some principles of code optimization, making useless but beutifull things.


##Intro

* demo scene : Crackers, adds text message to show their names, then trainers to show skills, then cracktro -> demo
* pure demonstration of dev skills, twoard artistic creation (montrer la cuddly demo et la statof the art ?)
* disclaimer : this dojo is useless, most of performance problems are not in code. Things to check first :
  *Cache and memory size
  *Poll sizes
  *Network
  *Simplify business requirements
  *Allow asynchronism (nightly batch calculation, ...)

##Rotozoom (c'est un bon probleme ?)

  Ca tourne et ca zoom, cool
  
##Data navigation

###The problem

###difference between arrays and maps

###Indexation (eg : hashmaps, pas d'utilité dans le rotozoom :( )
   
##Allocations

###Cost of allocation (and hidden cost of GC)
###Static immutable resources
###Hidden allocation
*libraries
*autoboxing
###Optimization the JVM makes for you
*recycling of objects
*singletonized Integers

##Loops, innerloop

*minimize cost in inner loop
*avoid loops (and inner loops)
*mathematical simplifications

##Expensive operations

###What to look for
*data navigation
*heavy maths
*external ressource access
*allocations

##What to do

*cache
*approximations
*change mathematical model (fixed comma numbers)
