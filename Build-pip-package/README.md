# Build a pip-installable package and publish it to PyPI
1. Get familiar with ```testpypi``` examples [here](https://packaging.python.org/en/latest/tutorials/packaging-projects/), before trying ```pypi```.
2. ```pip install hatch twine```
3. ```hatch build```
4. ```twine upload dist/*```
