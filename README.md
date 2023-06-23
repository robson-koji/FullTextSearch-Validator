# Full Text Search Validator

This module is used to validate documents searched using a query format similar to those used in search engines like Google and Lucene.

The module accepts three arguments:

- **`test`**: str = Searched string
- **`docs`**: dict = Documents to verify
- **`index`**: dict = Inverted index of the words in the documents

This is a customized version of the script that can be found [here](https://github.com/pyparsing/pyparsing/blob/master/examples/searchparser.py). It heavily relies on the PyParsing module.

https://pyparsing-docs.readthedocs.io/en/latest/pyparsing.html
