# ic-tester
The IC to be tested will be inserted in a 14 pin ZIF socket. The IC number is to be entered via a keyboard.
The keyboard has keys 0-9, backspace, enter and test.
The user places the IC in the ZIF socket, closes it – then enters the IC No, followed by the enter key.
The IC No. is displayed on the 7-segment display.
The testing will start once the user presses the test key.
After Test the result PASS/FAIL must be displayed on the 7-segment display.
After testing is complete, PASS/FAIL will be displayed for approximately 5s and then the display will be reset. 
During this time no input will be taken. After the reset, the user can give another input.

ASSUMPTIONS:
 Memory is able to provide data at the speed at which the processor is reading.
OnlyICnumbersthataregivenintheproblemstatementareconsideredasvalid
IC numbers.
 Test key will only be pressed after the Enter key has been pressed.
 If Test Key is pressed before Enter Key, the 7 - segment LED will display ‘FAIL’.
 IftheuserpressesEnterKeyaftergivinginvalidICnumberasinput,the7-
segment LED will display ‘FAIL’.
 AfterattachingtheICintotheZIFsocket,theuserclosesitandthentypestheIC
number using the hex keypad.
 TheALPhasbeenmadeassumingthereisnodebouncewhenakeyispressed
in Proteus.
 Two or more keys cannot be pressed simultaneously and if pressed it will be
ignored.
 ThefirstinputcannotbeBackspace,EnterorTestkey.ItMustbeadigit.
 The User cannot give inputs while PASS/FAIL is being displayed.
