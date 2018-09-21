# debugmodule


To make sure everything is running correctly in venv, and to practice switching between branches

   - create a new virtual environment, or activate an existing one.
   - install this 'module' using ```python setup.py develop```
   - run ```python test.py```, it should return the name of the branch you are on
   - change branches to 'alternative'
   - run ```python test.py```, it should return the name of the branch you are on

If that is all working ok, do the same thing in a job sumbission script via the queue.

If that all works fine, then we know the porblem isn't with venv!

