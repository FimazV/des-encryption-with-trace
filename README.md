# DES Encryption Implementation with Trace
## Core Features
- Encrypt a specified 64-bit (16 hex digit) data value with a 64-bit (16 hex digit) key using DES.  
- Show Trace  

## Trace
- plain text and key in binary format
- subkeys generation process (subkeys in binary and hex format)
- DES encryption process
  - value after IP permutation
  - value after each iteration
  - value after IP-1 permutation  
  
Please view the output-example.txt for more information about the output.

## Usage
~~~~ 
g++ des.cpp -o des  
./des
~~~~ 


