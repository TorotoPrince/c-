# c-
use C++ to play"Castle in the Sky"
In win64,there is an interesting pronunciation function：Beep()

The prototype of the function:
BOOL WINAPI Beep(
 _in DWORD dwFrep,
 _in DWORD dwDuration);
 OK,Let us use C++ to play the music"Castle in the Sky",here is the code:
 
 #include<iostream>
 #include<windows.h>
 using namespace std;
 enum fy
  {
  d1 = 262, d1_ = 277,d2 = 311,d3 = 330,d4 = 349,d5 = 415,d6 = 440,d6_ = 466,d7 = 494,z1 = 523, z1_ = 554,z2 = 578,
  z3 = 659,z4 = 698,z4_ = 740,z5 = 784, z6 = 880,z6_ = 932,z7 = 988,
