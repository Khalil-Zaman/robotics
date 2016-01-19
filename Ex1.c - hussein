#include "simpletools.h" 
#include "abdrive.h"                    

int distance(n)
{
  /*Computes number of ticks to move n metres*/
  int x = (n*1000)/3.25;
  return x;
}

int angle(n)
{
  /*Computes number of ticks to move n degrees
  *Positive goes clockwise, Negative goes anti-clockwise
  */  
  //Doesn't work correctly, needs to be redone
  int x = n*0.284;
}

int main()
{
  while(1)
  {
    drive_goto(distance(1),distance(1));
    drive_goto(26,-25);
    drive_goto(distance(1),distance(1));
    drive_goto(26,-25);
    drive_goto(distance(1),distance(1));
    drive_goto(26,-25);
    drive_goto(distance(1),distance(1));
    drive_goto(102,-102);
    break;    
  }  
}
