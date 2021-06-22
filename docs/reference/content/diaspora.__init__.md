
Back to [Reference Overview](https://github.com/pyrustic/diaspora/blob/master/docs/reference/README.md)

# diaspora.\_\_init\_\_



<br>


```python

class Diaspora:
    """
    work in progress 
    """

    def __init__(self, tk=None, event_sep=' '):
        """
        Initialize self.  See help(type(self)) for accurate signature.
        """

    @property
    def event_sep(self):
        """
        
        """

    @property
    def resources(self):
        """
        
        """

    @property
    def subscribers(self):
        """
        
        """

    @property
    def tk(self):
        """
        
        """

    @tk.setter
    def tk(self, val):
        """
        
        """

    def event_handler(self, instance, prefix='_on_'):
        """
        
        """

    def pub(self, event, data=None, sync=False):
        """
        
        """

    def req(self, resource, res_args=None, res_kwargs=None, consumer=None, sync=False):
        """
        
        """

    def res(self, name, handler):
        """
        
        """

    def sub(self, event, consumer):
        """
        
        """

    def unres(self, name):
        """
        
        """

    def unsub(self, sid):
        """
        
        """

```

<br>

```python

class Error:
    """
    Common base class for all non-exit exceptions.
    """

    def __init__(self, *args, **kwargs):
        """
        Initialize self.  See help(type(self)) for accurate signature.
        """

```

