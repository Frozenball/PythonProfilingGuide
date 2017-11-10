# PythonProfilingGuide

## Line profiling

````bash
pip3 install line_profiler
# Mark functions with @profile
# There is some magic so no need to import it anywhere, it's built-in now.
# Run script using:
kernprof -l script.py
# See results with
python3 -m script.py.lprof
````
