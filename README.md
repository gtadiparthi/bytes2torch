byte2torch
==========
This code can do the following
- Reads the .bytes files that contain hex codes of assembly instructions
- Converts the hex to decimal
- Writes it a csv or a torch dataset


The inspiration for this piece of code is csv2torch-datasets package.

Basically copied the code from csv2torch-datasets and modified it for my purpose.

I basically modified csv2torch-datasets package. Used it to convert bytecodes (.bytes files). It is still a working document. 

```
Requires:
- torch
- torch-datasets
