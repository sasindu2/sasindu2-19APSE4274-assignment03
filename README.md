# 19APSE4274-Assignment-03


## 01.docker-compose up -d
![image](https://github.com/user-attachments/assets/4b5009d0-7724-46b7-b963-1c94fcffbf44)


## 02.docker exec -it namenode hdfs dfs -mkdir -p /input
## 03. docker exec -it namenode hdfs dfs -put /path/to/sample.txt /input
![image](https://github.com/user-attachments/assets/7155104b-c075-4ac9-82a1-aa0ed4a01a4c)

## 04. docker exec -it namenode hdfs dfs -ls /input
![image](https://github.com/user-attachments/assets/18b785d0-cd48-44d2-b325-830e7aa4c9f9)

## 05. docker exec -it namenode hadoop jar /opt/hadoop/share/hadoop/mapreduce/hadoop-mapreduceexamples-*.jar wordcount /input /output
![image](https://github.com/user-attachments/assets/e41f211c-8798-4de7-8aa1-f65a63a25345)
![image](https://github.com/user-attachments/assets/0fa8f93e-c067-43ee-aa18-d57a78af57cd)
![image](https://github.com/user-attachments/assets/320f58df-d4f0-447b-9d3c-3d91c9cadbc6)
![image](https://github.com/user-attachments/assets/80677e8a-fa15-401c-9533-ede6c2237f7f)
![image](https://github.com/user-attachments/assets/ae35f593-69cf-4fcd-90d5-0e0d5fdd6f6c)

## 06. docker exec -it namenode hdfs dfs -ls /output
![image](https://github.com/user-attachments/assets/97650e79-a701-4cbd-84ec-7ed73fd02548)

## 07. docker exec -it namenode hdfs dfs -cat /output/part-r-00000
![image](https://github.com/user-attachments/assets/be4893cd-9ea2-4ff8-b7d4-ccae7cccd12c)




