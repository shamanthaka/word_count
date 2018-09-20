

    su - hduser

    cd /usr/local/hadoop

    bin/hdfs dfs -mkdir /user

    bin/hdfs dfs -mkdir /user/shamanthaka

    create a sample file /home/shamanthaka/Desktop/data as sample.txt

    bin/hdfs dfs -put /home/shamanthaka/Desktop/data /user/input/data

    bin/hadoop jar /home/shamanthaka/IdeaProjects/wordcount/target/wordcount-1.0-SNAPSHOT.jar com.shamanthaka.wordcount.WordCount /user/input/data output3

    bin/hdfs dfs -cat output2/*

    http://localhost:50070
