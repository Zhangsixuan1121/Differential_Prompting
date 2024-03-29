# Differential Prompting

## Demo

https://github.com/Zhangsixuan1121/Differential_Prompting/assets/125631501/460e59b1-ca47-42a7-9857-27257f84f61b

## Description

Differential Prompting is an approach that can effectively find failure-inducing test cases with the help of the compliable code synthesized by the problem description. This command line tool allows users to interact with Gemini to automatically generate code, and test input pools.

## Installation

1. Clone or download our code to your local machine:

   ```bash
   git clone https://github.com/Zhangsixuan1121/Differential_Prompting.git
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

To use the command line tool, run the following command:

```bash
cd main
```

```bash
python DP.py
```

You need enter the valid key value for accessing Gemini:

<img src="img.png" alt="picture" width="400" height="40">

If your key value is invalid,you can not get the right result as follows:

<img src="img_1.png" alt="picture" width="480" height="400">

Once the command is executed, the results will be saved in the `results.xlsx` file.

