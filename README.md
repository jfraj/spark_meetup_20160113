# Spark meetup basics
This is a very short summary of steps that you can do to get ready.
These steps are by no means mandatory as the meetup is there to show you how things work and what you can do to get started.
One can use these instructions and notebooks to try it by yourself after the talk.
But if you plan to install it during the meetup, it is suggested that you download the file first.

The following (very short) installations steps worked for my Macbook Pro with OSX El Capitan

## Installing spark (pre-built)
(assuming no all other dependencies are installed)
* Go to spark [downloads](http://spark.apache.org/downloads.html)
* Choose newest (I successfully tried both 1.6.0 and 1.5.2) pre-build for hadoop 2.6 and later
* decompress e.g. `tar xvfz spark-1.6.0-bin-hadoop2.6.tar`
* try it (`cd [where you decompressed]`) `./bin/spark-shell`



##Notebooks used for the presentation
### Zeppelin install
(assuming no all other dependencies are installed)
* download `git clone https://github.com/apache/incubator-zeppelin/`
* `cd incubator-zeppelin/`
* `mvn clean package -Pspark-1.5 -DskipTests`
* `./bin/zeppelin-daemon.sh start`
* go to `http://localhost:8080/`
 
Acessing an exported notebook instruction [here](http://fedulov.website/2015/10/16/export-apache-zeppelin-notebooks/)
