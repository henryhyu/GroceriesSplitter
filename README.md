# GroceriesSplitter
Great python script for splitting bills with Housemates.

**Why**

When you shop with your housemates and one person pays for everything, it is such a hassle to go through each item on the list and ask e.g. who wants to drink the orange juice. If you enter an 'x' in the given your box on your spreadsheet that excludes you from the item. It then goes through everyone who doesn't have an x and splits the bill evenly. Check groceries.xls for a sample.

**How to run script and requirements**

I have included the xldir python module in the repository. It is a library for developers to extract data from Microsoft Excel (tm) spreadsheet files.

The version I included might be outdated. See https://pypi.python.org/pypi/xlrd for further details. 

Extract file and run setup.py file like: python setup.py install

Linux and Mac terminal:

python NewGroceries.py yourSpreadsheet.xls 

**Or**

chmod u+x NewGroceries.py

./NewGroceries.py yourSpreadsheet.xls

**How to use**

Follow the format in the sample spreadsheet in *groceries.xls*.

Courtesy of Ryan Fu.
