# SignalFlowGrapher

## Version 0.2 

Intended for beta test in the autumn term of 2020.

This version still has some issues and may crash; be careful and save often.

And please report all issues you find to hanspeter.schmid@fhnw.ch

## License
This package is distributed under the Artistic License 2.0, which you find in the file LICENSE and on the internet on https://opensource.org/licenses/Artistic-2.0.

## Authors of Version 0.2
Simon Näf, Nicolai Wassermann, Dominik Gruntz and Hanspeter Schmid. Contact author: hanspeter.schmid@fhnw.ch

## Installation instructions

### Installation of plain Python or of Anaconda

- Get the latest version of Python from https://www.python.org/ or of Anaconda from https://www.anaconda.com/products/individual

### Get the code

- Clone or download from https://github.com/hanspi42/signalflowgrapher

### Create and activate virtual environment with Python

For the managment of the dependencies, a virtual enviromnent is used.
- Open the `src` directory in a terminal
- Create virtual environment using the command `python3 -m venv signalflowgrapher`
- On Windows run `signalflowgrapher\Scripts\activate.bat` or `signalflowgrapher\Scripts\Activate.ps1`
- On Unix or MacOS run `source signalflowgrapher/bin/activate`

### Create and activate virtual environment with Anaconda

For the managment of the dependencies, a virtual enviromnent is used.
- Open the `src` directory in an anaconda terminal
- Create virtual environment using command `conda create -n sfg`
- Activate virtual environment using the command `conda activate sfg`
- Install pip with `conda install pip`

### Restore dependencies

- Open the `src` directory in a terminal or an anaconda terminal
- Run `pip install -r requirements.txt`

### Run application

- Open the `src` directory in a terminal or an anaconda terminal
- Run `python -m signalflowgrapher`
- Run `python -m signalflowgrapher --language de_CH` for using the application with german translations

### Run unit tests and format tests

- Open the `src` directory in a terminal or an anaconda terminal
- Run `python -m unittest`
- Run `flake8 -v`

## User manual

There is none yet, but to familiarize yourself with signal-flow graphs, you can
- Watch "Signal-Flow Graphs in 12 short lessons" on https://tube.switch.ch/channels/d206c96c?order=episodes
- Read our papers, https://link.springer.com/article/10.1007%2Fs10470-018-1131-7 and http://rdcu.be/naw5 .

## Credits
Implemention of Johnson's algorithm: https://github.com/qpwo/python-simple-cycles
