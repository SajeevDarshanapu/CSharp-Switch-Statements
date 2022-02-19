# CSharp-Switch-Statements


-----------------To select one of many code blocks to be executed.

# syntax

switch(expression) 
{
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
    break;
}

# Example on switch statement

int nani = 4;
switch (nani) 
{
  case 1:
    Console.WriteLine("N");
    break;
  case 2:
    Console.WriteLine("A");
    break;
  case 3:                                             //output: I
    Console.WriteLine("N");
    break;
  case 4:
    Console.WriteLine("I");
    break;
  default
    Console.WriteLine("NANI");
    break;
  
}
