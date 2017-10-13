# DES Encryption Implementation with Trace  
<img width="557" alt="desenc" src="https://user-images.githubusercontent.com/8156002/31529241-a324d068-af9d-11e7-96bd-db7fa8f4bdb3.png">  

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


