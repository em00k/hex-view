# hex-view
 hex view with python on the for comparing data
For analysing data dumps on the command line with python 

Usage:

To display the hex view the ASCII text for the whole row:

python hex.py <path_to_binary_file>

To display the hex view with ASCII characters for each byte and the ASCII text for the whole row:

python hex.py <path_to_binary_file> -c

To limit the output to the first N bytes, with both the per-byte ASCII view and the end-of-row ASCII text:

python hex.py <path_to_binary_file> -bytes N -c
