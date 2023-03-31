
## SIATM as a universal data storage and exchange format

SIATM is an overlay markup that encapsulates data and processing methods.
These methods may be part of the built-in library, or one of the public ones, or even a combination of both.
To solve different problems, a different set of methods can be used, but since the main storage format is unified, this does not affect the integrity of the serialized object.

Due to the globally addressable referencing of fragments, this markup supports a separate way of storing and processing parts.
That is, data exchange can use partial images or diffs, separating, for example, data and metadata.

With this markup, it will be possible to operate with a vertically compatible hierarchy from a simple DSL serializer to a full-fledged model with a full description or even schemas.
This will allow you to move to a higher level of data abstraction, from simple models to virtual models.

The markup file format allows you to combine text and binary elements, or provide an interface for accessing binary blocks with streaming access.

Simple SIATM serialized data, can be in the form of a more compact text than XML, is faster to process in a multi-threaded environment, as it is basic indexed and identified per fragment.