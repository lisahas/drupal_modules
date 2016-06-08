This small module helps content creators by overriding the 'save', 'add' and 'add existing' 
button labels on node forms and any inline entity forms.

The button labels are altered so they specify the node type eg. 'save project' or 'save artist' 
instead of simply 'save'.

When entity reference forms are used, the buttons are overriden so they also specify the node type eg.
'Add new artist' or 'Add existing artist' instead of simply 'Add new node' which is the default.

This helps people by making it clear what kind of node they are creating, adding or saving. This is 
especially useful when inline entity forms are used with entity references.  Inline entity forms are 
useful when there is a lot of linked data, but often lead to a form for one kind of node being open within 
a form for another, confusing editors.

It's a small issue, but it makes a difference to content creators!


Installation
------------

Add to your modules directory and enable in the usual way.


TODO
----

Get working with when multiple node types are possible in an entity reference field.
