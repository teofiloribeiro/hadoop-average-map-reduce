# hadoop-avarege-map-reduce
This is a simple project where you can calculate the average of the values in a HDFS.  
This program maps a file where each line contains one record. Each key value pair must be separated by **;**  

## Example
**Input**
> Junior; 1500  
> Senior; 6000  
> Senior; 7500  
> Junior; 2000  

**Output**
> Junior; 1750  
> Senior; 6750

## Instalation

```sh
$ git clone https://github.com/teofiloribeiro/hadoop-average-map-reduce.git  
$ cd hadoop-average-map-reduce  
$ mvn clean install  
```

[Or only .jar file.](https://github.com/teofiloribeiro/hadoop-average-map-reduce/tree/master/target)

## Using
You need to pass as parameter your HDFS input and output directory

```sh
$ hadoop jar {your/jar/location}AverageMapReduce.jar com.teofilo.reducer.Main /input_dir /output_dir
```
