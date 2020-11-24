This C program takes BMP images as input and apply filter to them.

Using Instructions:
This may not work on your local system but it will work online compilers and it is will work fine on -> ide.cs50.io . which is an online ide that supports many languages. You should first know how to comile a C program using comman-line Arguments and you should know how to run a program in ide.cs50.io. I have also uploaded a bmp image for the usage here and upload this bmp image in ide too. 

Using Command Line Arguments:

Options for filters:
-g for greyscale

-r for reflect

-e for edge detecion filter

-s for sepia filter

-b for blur filter

Using:
After uploading all files , check that all files are in same directory or not.
If you didnot created folder, then you donot need to think for this.

then build this file:
The build will give error but don't focuse on that

then according to your system:
if clang:
./main -g blur-stadium.bmp out.bmp

if gcc:
main.exe -g blur-stadium.bmp out.bmp

syntax:
./main -filter input.bmp output.bmp

here you need to replace -filter by the -g , -r and any of your choice.
here you need to replace input.bmp by the name of the file and don't forget to include .bmp after the name.
here you need to replace output.bmp by the name of the output file and don't forget to include .bmp after the name.

then a new file will get created with the output file name. 

Open it and see the the filter has been applied.

For any errors you can ask on github.


 
