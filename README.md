twfython
=
*Automatically exported from code.google.com/p/twfython - __No longer maintained__*

A python binding for the [http://www.theyworkforyou.com/ TheyWorkForYou] [http://www.theyworkforyou.com/api/ API].

This API is still not fully tested, so please report any bugs on the [http://code.google.com/p/twfython/issues/list Issues] page.

Usage
-
```python
twfy = TWFY.TWFY(APIKEY)

twfy.api.METHOD(PARAMS)
```

  * APIKEY = You [http://www.theyworkforyou.com/api/key TheyWorkForYou API Key]
  * METHOD = The name of a [http://www.theyworkforyou.com/api/ TheyWorkForYou API Function], for example 'getMP'
  * PARAMS = The parameters supplied to the different [http://www.theyworkforyou.com/api/ TheyWorkForYou API] functions. See the [http://www.theyworkforyou.com/api/ API docs] for more info. The 'output' parameter is required by all methods and sets the output format you want the results in, must be one of: 'xml','php','js','rabx'

An example of how to use the API is included in the SVN repository, you can checkout the source [http://code.google.com/p/twfython/source/checkout here]
