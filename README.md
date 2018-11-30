# BasicProdCon
# Producer
Compile:javac -cp .:`mapr classpath` Producer.java 
Run:java -cp .:`mapr classpath` Producer apps/str1:topic1 10000

# Consumer:
Compile : javac -cp .:`mapr classpath` Consumer.java 
Run:java -cp .:`mapr classpath` Consumer  /apps/str1:topic1 grp7
