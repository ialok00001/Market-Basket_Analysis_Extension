# Market-Basket Analysis Extension

This project is an extension to the traditional Market-Basket analysis models, that only give one-to-one association rules. In this section, we have extended this to include many-to-one association rules too, opening more possibilities for the model. With this extension, we can get more powerful association rules.

One can also leverage the code to identify classification rules in datasets of certain kinds, especially those in which the attributes are categorical. We wish to use this technique to find and learn how the attributes' values together give us certain kinds of classifications. Note that it is different from the normal classifiers since it is the user gaining insights into relations in the dataset in this case.

For example, if we are given a bunch of lists each of them containing a collection of words such as school, basketball, football, work, discipline, etc. and their corresponding target identifies whether a particular list of words belongs to educational or a sports background. This is not as simple as it looks, for the word discipline can be used in both cases, i.e. in an academic field or a sports field. So the collection of attributes together is important to understand these rules.

To implement such an idea, one has to recreate the market basket from scratch. This project contains the scratch part of it. It will also be an excellent exercise to learn more about the algorithm itself.
