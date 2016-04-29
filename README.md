# CythonExampleTest
Tests to illustrate conda install of package

1. clone repo or download the `test_polygon.py`

2. create new conda environment and activate it
   ```
   conda create -n cy_example python pytest
   activate cy_example
   ```

3. install the polygon package from jsandhu channel
    `conda install -c jsandhu polygon`

4. run tests
    `py.test -v test_polygon.py`
