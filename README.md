# Blaster. 
A simple phyton program for blasting fasta files with uknown id's.

## Getting Started

This tool allows you to accomplish nucleotide blast search looking for organisim identifiers.
### Prerequisites

You need to install python3 with Biopython module to run this tool.

### Installing

To install this tool clone this repository to your PC.

```
~$ git clone https://github.com/anton-shikov/Blaster
```

## Running and using tool

Using this tool is not complicted. After downloading repository launch terminal and enter this repository or run programm using absolute path to .py file.
Use this following command to execute tool:
```
~$ python Blaster.py -i classwork2.fasta -o classwork2_out.fasta
```
Information about flags:  
-o sequence output name  
-i sequence input name 


Output format: fasta file with identifiers displaying species belonings and also log file with information about contigs (groups of contigs related to organism)


## Author

* **Anton Shikov** - *Initial work* - [anton-shikov](https://github.com/anton-shikov)


## License

This project is free and available for everyone.

## Acknowledgments

Eugene Bakin for python course.
