<!-- start header -->
To run this example locally, [install Ploomber](https://docs.ploomber.io/en/latest/get-started/quick-start.html) and execute: `ploomber examples -n cookbook/variable-number-of-products`

To start a free, hosted JupyterLab: [![binder-logo](https://binder.ploomber.io/badge_logo.svg)](https://binder.ploomber.io/v2/gh/ploomber/binder-env/main?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fploomber%252Fprojects%26urlpath%3Dlab%252Ftree%252Fprojects%252Fcookbook/variable-number-of-products%252FREADME.ipynb%26branch%3Dmaster)

Found an issue? [Let us know.](https://github.com/ploomber/projects/issues/new?title=cookbook/variable-number-of-products%20issue)

Have questions? [Ask us anything on Slack.](https://ploomber.io/community/)

For a notebook version (with outputs) of this file, [click here](https://github.com/ploomber/projects/blob/master/cookbook/variable-number-of-products/README.ipynb)
<!-- end header -->



# Tasks with a variable number of products

<!-- start description -->
Shows how to create tasks whose number of products depends on runtime conditions.
<!-- end description -->

1. [Basic](basic) - Basic example
2. [Serializer](serializer) - Example using serializer and unserializer


```sh
cd basic
ploomber build --entry-point pipeline.yaml
```

```sh
cd serializer
ploomber build --entry-point pipeline.yaml
```
