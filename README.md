# Double-Double-Domino

1. the libraries required to run the project including the full version of each library

numpy 				1.24.2
opencv-contrib-python         4.7.0.72
opencv-python                 4.7.0.68
pip                           22.3.1
jupyter_client                7.4.8
conda                         23.1.0
mpmath                        1.3.0
glob2                         0.7
python				3.9.13

2. how to run your solution and where to look for the output file.

script: Project 1.ipynb
function: solve_all_images(images,moves), where images is the path to the folder of all images, and moves is the path
	    to the folder with the moves.txt. the script will take every image called: "*_*.png" and every text called: "*_moves.txt"
example:  solve_all_images("train/regular_tasks","train/regular_tasks")
It is mandatory to have the image cropped_board2.jpg in the same folder with the script.
Please create an empty folder called "results" before running the script, in this folder will be saved the generated output
output: the output file consists of txt files in results