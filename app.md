# The App

App is a class/manager that has the job of managing
and running the Dom and (rendering)? the widgets

```python

class App:
    """The Application Class"""
    def compose(self: "App") -> Generator:
        """The Compose Function

        will yield the widgets for the app to use

        """
    def messages(self: "App") -> Generator:
        """The Messages Function

        will yield the message bind's for the app to use

        """
    def run(self: "App", *args) -> None:
        """The Run Function

        Runs the application

        """

```
