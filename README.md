# IBM-SparkAssignment

1. Configured Hadoop and Spark services in VM(I've used GCP compute Engine)
2. I've created envsetup.sh script that would install all dependencies and start spark services
3. Created functSpark.py that has main class and methods for reading, writing data into COS and DB(using spark jdbc driver.) 
4. Created main.py for instantiating spark session in standalone mode.
5. Implemented logging capability to write logs for each session.
6. Implemented generic methods to read data from different file formats and DB's

## Sample output snips:

### Average salary/Department

![image](https://user-images.githubusercontent.com/34623941/100903653-299ccc00-34ec-11eb-8be9-041ebdf05b74.png)

### Male and female salary gap in each department

![image](https://user-images.githubusercontent.com/34623941/100903496-fbb78780-34eb-11eb-87ed-41dfd69b8af6.png)

### Gender ratio in each department

![image](https://user-images.githubusercontent.com/34623941/100903746-433e1380-34ec-11eb-884d-fa5b40a715f2.png)

### Created mysql DB instance

![image](https://user-images.githubusercontent.com/34623941/100904167-c2334c00-34ec-11eb-92cb-c204f6cd997c.png)

### Data loaded into mysql DB.

![image](https://user-images.githubusercontent.com/34623941/100904257-d8d9a300-34ec-11eb-9aeb-0684405ab2cf.png)