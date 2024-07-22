# Offshore Wind to H<sub>2</sub>
Data &amp; Code Repository for the EES Article - Sailing towards sustainability: offshore wind's green hydrogen potential for decarbonization in coastal USA.

Authors: Rishi Kaashyap Balaji and Fengqi You

DOI: [10.1039/D4EE01460J](https://doi.org/10.1039/D4EE01460J)

![image](https://github.com/user-attachments/assets/e8a23f66-0ca1-4e4c-bbee-7b95fc681e58)

## System Requirements

### Operating System
This repository was developed and tested on Windows 11, ensuring full compatibility with this operating system.

### Hardware Requirements
The models do not require any non-standard hardware and can be run on a typical desktop computer. The code has been tested on a system with the following specifications:

- DELL OPTIPLEX 7040 Desktop 
- Intel(R) Core (TM) i7-6700 CPU @3.40 GHz
- 32GB of RAM

### Package Requirements
- python  3.9.13
- pandas  1.4.4
- numpy  1.23.5 
- matplotlib  3.3.4
- pyomo  6.5.4
- Gurobi 10.0.1
- OpenLCA 11.0
  
## Installation Guide
The source code is not distributed as a package, therefore, no installation is required. It is highly recommended to use [Anaconda](https://www.anaconda.com/) to manage the Python environment to run the code. To get started, please follow these steps:

1. **Clone the repository:** Clone the repository to a local directory using the following command:

```sh
git clone https://github.com/PEESEgroup/Offshore_Wind_to_H2.git
```

2. **Create a Conda environment:** Navigate to the cloned directory and create a Conda environment with the required packages as specified in the [Package Requirements](#package-requirements) section. 

```sh
conda create --name <environment_name>
# Install the packages listed in Package Requirements
```

3. **Activate the Conda environment and run the code:** With the Conda environment activated, you can now run the code as needed following the instructions in the [Demo](#demo) section.

```sh
conda activate <environment_name>
# Run the code
```
## Instructions for Use

To reproduce the results in our paper, please refer to the jupyter notebooks provided. Prior to executing these files, obtain a Gurobi licensce (Free Academic academic licenses are provided by Gurobi) and add the solver exectuable to the system path. Further, unzip the file - CF_Data.zip that is provided and place the unzipped directory in the working directory. 

## Citation
```
@article{balaji2024sailing,
  title={Sailing towards sustainability: offshore wind's green hydrogen potential for decarbonization in coastal USA},
  author={Balaji, Rishi Kaashyap and You, Fengqi},
  journal={Energy \& Environmental Science},
  year={2024},
  publisher={Royal Society of Chemistry}
  doi = {https://doi.org/10.1039/D4EE01460J}
}
```
