# SuperSecretHyperProject

### Concept
Create an application to change a map's projection from a selected origin [O] based on a selected travel method [e.g. public transport, walking, etc.] as defining the new mapping. A given travel method would create mapping of geographic points [r,theta] to just time [t].

### Plan of Action

- Simple models first: t = f[r,theta] = r^2

- Map time as height above as proof of concept

- How hard it is to extract travel times to O(100) from some API?

- How hard is it fit a limited set of t to a given f[r, theta]?

- How do I transform an image based my new f[r,theta] (easy)?

- How do I tranform and maintain the features of original geography (hard)?
