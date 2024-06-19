 `Article about how to write docs with rst <https://www.writethedocs.org/guide/writing/reStructuredText/>`_

====
Header 1
====
This is how headers are created

Subheader 1
===========
This is how subheaders are created

Now, let's insert some code sample::

 def findMax(list):
     if len(list) == 0: return -1
 
     max = list[0]
     for x in list:
         if x > max: max = x
     return max





