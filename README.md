# CI-V-Voice-CW-Keyer-for-Icom-7300
Arduino CI-V keyer for ICOM IC-7300
/*
   CI-V Voice/Morse keyer
   Version 1.1
   
   https://yo3hjv.blogspot.com/2020/04/cw-and-voice-memory-keyer-for-icom-ic.html
   
   This is a CW memory keyer for ICOM CI-V radios.
   It was tested on IC-7300 and it is working well.
   It was tested on IC-703 and was find not compatible.
   Many thanks for inspiring the structure to KEN - KC9UMR.

   The 4 x 4 keypad is able to send:
   -In CW, 10 preprogrammed CW messages, each of 128 bytes;
   -in SSB, AM, FM, 8 prerecorded voice messages
   -"A" is Power ON
   -"B" is Power OFF
   -"C" is TUNE

   The rest will be defined later on other versions.

   
   This was a good opportunity for me to learn to use Arrays and Switch/case
   Many thanks for the whole community from where I learned!
   Thanks also to our wise government for keeping us at home...

   de Adrian Florescu, YO3HJV. April, 2020
   

   This code is released under the EUPL v1.2.

*/
