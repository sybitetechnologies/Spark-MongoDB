About
*****

Spark-Mongodb is a library that allows the user to read/write data with `Spark SQL <http://spark.apache.org/docs/latest/sql-programming-guide.html>`__
from/into MongoDB collections.

`MongoDB <http://www.mongodb.org>`__ provides a documental data model
richer than typical key/value systems. `Spark <http://spark.incubator.apache.org/>`__ is a
fast and general-purpose cluster computing system that can run applications up to 100 times faster than Hadoop.

Integrating MongoDB and Spark gives us a system that combines the best of both
worlds opening to MongoDB the possibility of solving a wide range of new use cases.


Latest compatible versions
==========================
+-----------------+----------------+----------+
| Spark-MongoDB   | Apache Spark   | MongoDB  |
+=================+================+==========+
|     0.10.x      |      1.5.x     |   3.0.x  |
+-----------------+----------------+----------+
|  0.8.2 - 0.9.2  |      1.4.0     |   3.0.x  |
+-----------------+----------------+----------+
|     0.8.1       |      1.3.0     |   3.0.x  |
+-----------------+----------------+----------+
|     0.8.0       |      1.2.1     |   3.0.x  |
+-----------------+----------------+----------+


Requirements
============
This library requires Apache Spark 1.5.X, Scala 2.10 or Scala 2.11, Casbah 2.8.X