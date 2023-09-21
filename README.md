This program takes 9 color palettes and maps them into a 3x3 square on the image.

- Download 3x3PalleteColorMap-CPP
- Naviagte into 3x3PalleteColorMap-CPP/ folder
- To run Code with preset comands:
-      ./run1.sh
            - runs with waves.png image.
            - output into output.png
-      ./run2.sh
            - runs with checkers.png image
            - output into output.png
-      ./run3.sh 
            - runs with Lena.png image
            - output into output.png
- To run Code bare:
-     make clean
-     make   OR
-     ./final <input_image> <output_image>


- Once program is running:
  - Click image with left mouse button to apply color map
  - Program will take some time to run because some color palettes are giant.
  - Press 'r' or 'R' to revert image to original
  - Press 'w' or 'W' to write image to specified file. If no file specified, program will ask you to input one
  - Press 'f' or 'F' to input a new image file to map to
  - Press 'q' or 'Q' to exit program.
