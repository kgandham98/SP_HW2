
To Compile:
        make (gcc -o hw2 hw2_kgandham.c)

To Execute:
  1) With arguments and without arguments
	./hw2
 	./hw2 ./(Directory Name)
        ./hw2 (Path)

  2) Using -S
        ./hw2 -S
	./hw2 -S ./(Directory Name)

  3) Using -s
	./hw2 -s (file size in bytes)
  
  4) Using -f
     	./hw2 -f (string) (depth)

  5) Using -t
        For regular files - ./hw2 -t f
	For Directories - ./hw2 -t d
	
  6) Combinations:
	1.  ./hw2 -S -s (file size in bytes)
	2.  ./hw2 -s (file size in bytes) -S
	3.  ./hw2 -s (file size in bytes) -f (string) (depth)
	4.  ./hw2 -f (string) (depth) -s 1024 
	5.  ./hw2 -S -f (string) (depth)
	6.  ./hw2 -f (string) (depth) -S
	7.  ./hw2 -S -s (file size in bytes) -f (string) (depth)
	8.  ./hw2 -S -f j(string) (depth) -s (file size in bytes)
	9.  ./hw2 -f (string) (depth) -s (file size in bytes) -S
	10. ./hw2 -f (string) (depth) -S -s (file size in bytes)
	11. ./hw2 -s ((file size in bytes) -S -f (string) (depth) 
	12. ./hw2 -s (file size in bytes) -S -f (string) (depth)  	 
   
