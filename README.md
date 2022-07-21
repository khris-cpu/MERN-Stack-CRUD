Create, Read, Update and Delete are the four basic functions of persistent storage. These operations are usually referred to using the acronym CRUD. Within a database each of these operations map directly to a series of commands, however their relationship with a RESTful API is slightly more complex.

The Orion Context Broker uses NGSI-v2 to manipulate the context data. As a RESTful API, requests to manipulate the data held within the context follow the standard conventions found when mapping HTTP verbs to CRUD operations.
