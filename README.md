# python_decorators
A repository to teach Python decorators.

## Python decorators
By definition the decorators are functions that transform the behavior of other functions without explicitly modifying them.

ex:
```python
class Example:
    @classmethod
    def foo(cls):
        pass
```
Without the `@classmethod` decorator, the `foo` method would be connected to the attribute. With the decorator, the method have it's behavior changed to be connected to the class instead of the object.

## Python PEPs on decorators
Describe decorators syntax and the process of creating and using on:
* [PEP 318](https://www.python.org/dev/peps/pep-0318/)  functions and methods;
* [PEP 3129](https://www.python.org/dev/peps/pep-3129/)  class.

## Notebooks sequences:

See [motivation notebook](notebooks/motivation_notebook.ipynb) to see examples of why `decorators` were created.

Then see:
 * [class and static properties](notebooks/class_and_static_methods.ipynb)
 * [property_methods](notebooks/property_methods.ipynb)
 * [creating_methods](notebooks/creating_methods.ipynb)


## Useful sources
### Built-in methods
[This link](https://docs.python.org/3/library/functions.html) will get you to built-in methods. As you'll understand in this repository, built-in decorators are created from built-in methods.

### Methods resolution order
[This link](https://www.python.org/download/releases/2.3/mro/) will guide you to the fun documentation about Python C3 methods resolution order. Even if is confusing, see the beautiful Python snake created. :)

> This document is intended for Python programmers who want to understand the C3 Method Resolution Order used in Python 2.3. Although it is not intended for newbies, it is quite pedagogical with many worked out examples. I am not aware of other publicly available documents with the same scope, therefore it should be useful.

### Python PatternDigest
[This link](https://web.archive.org/web/20031204182047/http://patterndigest.com/patterns/Decorator.html) will guide you to the beautiful pattern explanation about decorators and how they change methods dynamically.

You'll find:
* Applicability
* Consequences
* Metapatterns

### Real Python tutorial
[This link](https://realpython.com/primer-on-python-decorators/) will guide you to a Real Python tutorial about decorators.


# Ending note
> [...] Explicit is better than implicit. [...] Simple is better than complex. [...] Readability counts. (PEP 20)
