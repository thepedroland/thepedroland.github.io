Some steps I had to make in order to use that package:

First, I had to downgrade the pandas to 2.3.3 - it seems there was a modification for pandas >=3.0.0

Second, I installed fiona using: conda install -c conda-forge fiona
	- I could not just use "pip install fiona"