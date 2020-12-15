## CRPP
This repository containts the data files used in the computational experiments in the working paper

> Domínguez, C., Labbé, M., & Marín, A. (2020). Multi-product pricing under a ranked-based consumer choice model: mixed-integer formulations for the Capacitated Rank Pricing Problem.

## Citation

If you use the data in this repository in your own research, please cite the above paper.

## License 

This code is available under the MIT License.

Copyright (C) 2018 Velibor Misic

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Repository Structure

This repository contains one directory:

+ `CRPP_DATA`: Contains the data files used in the numerical experiments:
  + `CRPP_DATA_K*_I**_C***_INS****`: contains data for synthetic data instances (see Section 6 of Domínguez et al.), where `*`, `**` and `***` are the values of `|K|`, `|I|` and `C`, respectively, and  `****` indicates the number of the instance (there are 5 randomly generated instances for each combination of parameters). Each file includes:
   + K : Number of customers (`|K|` in the paper),
   + I : Number of products (`|I|` in the paper),
   + C : Number of copies of each product for sale.

