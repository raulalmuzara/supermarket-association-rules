# Association rule mining for market basket analysis

Analysis of the Weka dataset *supermarket.arff* in **Python**. It contains 4627 customer transactions, which are lists of products from 216 departments in a supermarket.

The objective is to identify association rules and learn purchasing patterns to find out which products are often purchased together. In order to extract meaningful rules, we will be interested in those rules with a certain minimum support, confidence and lift. The rules will be obtained with the *Apriori* algorithm.
