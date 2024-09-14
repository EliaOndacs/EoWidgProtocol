# The Dom

The Dom is one of the most important part of the whole idea
it has the job of storing and querying all the DomNode's

```python

class Dom:
    def query(self: "Dom", id: str) -> list[Widget]:
        """The Query Function

        its job is to query widget and the DomNode's based on the id

        """

    def query_one(self: "Dom", id: str) -> Widget:
        """The QueryOne Function

        its job is similar to query but it only will return one widget/DomNode
        based on the implementation choice it can act if it finds more than expected one widget with the id

        """

    @property
    def nodes(self: "Dom") -> list[Domnode]:
        """a property that stores the child domnode's"""

```
