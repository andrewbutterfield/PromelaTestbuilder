# TODO

## Remove Coconut

  1. archive coconut sources [DONE]

  2. decide order in which to remove .coco files
     If we do `make clean` followed by `make py`, 
     the only additons/changes to `.py` files take place in:
     `./env/lib/python3.14/site-packages/pip/.../*.py`

  3. Do it ....

## Align `automatic_testgen.py` with `testbuilder.py`.

   1. Purge references to RTEMS
   
   2. Move implementation of `help` up closer to start of `main`,
      with an immediate exit.

   See `testbuilder.py` commits from 4th Nov. **2025** to 5th Nov. 2026.