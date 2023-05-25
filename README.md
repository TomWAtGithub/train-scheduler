# Train scheduler

In 2022, the German Society for Computer Science organized a coding competition called InformatiCup that tackled the problem of creating optimal timetables for a rail network. The goal of the contest was to minimize the overall delay of all passengers and thus improve overall customer satisfaction with rail transportation.

This projects implements an algorithm that solves the described task and creates robust and high quality timetables for passengers and trains with. The exact assignment can be found in [the official repository](https://github.com/informatiCup/informatiCup2022).

# Requirements
The following packages are used:
- sys
- typing
- pathlib
- traceback
- pandas
- os

Furthermore, an installation of [jupyter-notebook](https://jupyter.org/install) is required to run the .ipynb-files. Once installed, typing `jupyter-notebook` in a terminal will open a dashboard in your browser, where you can navigate to the code and open it.

# How to run
If you want to execute the code on input files do the following:
- make sure that the input files you want to test follow the format described in the [official repository](https://github.com/informatiCup/informatiCup2022/blob/main/informatiCup%202022%20-%20Abfahrt!.pdf)
- place your .txt-files in the folder `Input` and make sure to add the suffix `input` to your input-files (for example: `test1_input.txt`)
- open `main.ipynb`
  - overwrite the attribute `notebook_name` at the top of the code - this will be the name of the folder in which the output files are created
  - select `Cell - Run All`
- the output files can be found in the folder `Output/<notebook_name>`
  - for each input file in the folder `Input` one output file is created, where the suffix `input` is replaced by the suffix `output` (for example: `test1_output.txt`)

