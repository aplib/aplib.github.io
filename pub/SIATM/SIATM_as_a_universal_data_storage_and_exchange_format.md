
## SIATM as a universal data storage and exchange format

SIATM is a compositional markup language that encapsulates both data and processing methods.
These methods can be part of the built-in library, a public library, or a combination of both.
To address different problems, developers can use a different set of methods and encodings. However, since the main storage format is unified, these changes do not affect the integrity of the serialized objects.

Because fragments are referenced, this markup supports a separate way of storing and processing parts.
That is, data exchange can use partial images or diffs, separating data and metadata.

With this markup, it will be possible to operate with a vertically compatible hierarchy from a simple DSL serializer to a full-fledged model with a full description or even schemas.
This will allow you to move to a higher level of data abstraction, from simple models to virtual models.

The markup file format allows you to combine text and binary elements, or provide an interface for accessing binary blocks with streaming access.

Simple SIATM serialized data, can be in the form of a more compact text than XML, is faster to process in a multi-threaded environment, as it is basic indexed and identified per fragment.