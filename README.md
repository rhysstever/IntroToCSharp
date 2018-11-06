# IntroToCSharp
This is  a list of topics I wish to cover in my C# Technical Seminar. I plan to base it mostly on C#'s differences to Java

**Misc Stuff in Main()**
  -Printing 
  -Getting User Input
  -Using the Console Window
    --Clearing
    --Setting Cursor Position
    --Coloring Back/Foreground
  -Lists<> and not Arraylists
  -Constants
**Classes**
  -Basic format
  -Using multiple constructors
  -Properties 
  -Generic Classes
  -Pillars of OOP
    1) Encapsulation
      -Public = everywhere
      -Private = only in that class
      -Protected = only in inherited classes
    2) Polymorphism
      -Overloading methods
        --Same method name in the same scope, different parameters  different output
    3) Inheritance
      -Parent, Child class
        --No “extends” or “implements”, just “:”
      -Overriding methods 
        --2 methods with the same name but in different classes
        --Base one in parent class  prints a generic output
        --Overridden in child class  more specific output
      Ex) Dog d1 = new Corgi(); 
        --Valid, but... C# thinks d1 is only a Dog 
        --d1 cannot use any method from Corgi Class
        --Downcast to Corgi object --> Corgi c = (Corgi)d1;
