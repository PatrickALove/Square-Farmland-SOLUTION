# Square-Farmland-SOLUTION
You have been hired by a binary farmer to find the largest square plot of land for planting crops on her new farm.  The plot to be farmed must be a square where the width and depth are the same.  (Her plants have square roots.)  She has created a text file that models her property. Every square hectare of land good for planting is denoted by a 1, and every hectare that is deemed not suitable is represented by a 0. The input for this program comes from largestsquare.txt. The first line of the input file will be the integer n, the number of rows and columns of the matrix.  The following n rows will contain n 1’s or 0’s separated by spaces. Your program should find the row and column position of the upper left corner (corner with the smallest index) of the largest square that is suitable for planting and output the number of hectares in that square.  The first row and first column are numbered zero.  If there is more than one square of the largest size, your program can output any largest square.

Example input from largestsquare.txt

13
0 0 0 0 0 0 0 0 0 0 1 1 1
1 1 1 1 0 0 0 0 0 0 1 1 1
0 0 0 0 1 1 0 0 1 1 1 1 1
1 1 0 0 1 1 0 1 0 1 0 1 0
1 1 0 0 1 1 1 1 0 0 0 0 0
1 1 0 0 1 1 0 0 1 1 1 0 1
1 1 1 1 1 1 1 1 1 1 0 1 1
0 0 0 1 1 1 1 0 0 0 0 1 0
0 1 1 1 1 1 1 1 1 1 0 1 1
0 0 1 1 1 1 1 1 0 0 1 1 1
0 1 1 0 1 0 1 0 1 1 1 1 0
1 1 1 0 0 1 1 0 1 0 0 1 1
1 0 1 0 1 0 1 0 1 0 1 0 1

Example output

Biggest plot is at 6, 3 of size 16 hectare
