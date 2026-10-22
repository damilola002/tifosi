# tifosi

1. cd to project folder 
2. create virtual environment (python3 -m venv .venv
)

To run Venv--> source .venv/bin/activate

download fastf1 library 
pip install fastf1 (comes with panda)

run example code 

import pandas as pd
import fastf1
fastf1.logger.set_log_level("DEBUG")
session = fastf1.get_session(2020, 'Italian Grand Prix', 'R')
session.load()
session.results
