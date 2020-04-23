# Artistic-Style
astyle_3.0.1_linux , shouldDeleteEmptyLines it is overridden to delete multiple consecutive empty lines instead of deleting all empty lines, you got try it !

----------------------------------------------------------------------------------------------
before:
fun
{
  int a;
  
  int b;
}

fun
{
  int a;
  int b;
}

----------------------------------------------------------------------------------------------
now:
fun
{
  int a;
  
  
  
  
  int b;
}

fun
{
  int a;
  
  int b;
}
