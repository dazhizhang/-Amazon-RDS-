# -Amazon-RDS-
 Amazon RDS 数据库

https://docs.aws.amazon.com/zh_cn/elasticbeanstalk/latest/dg/java-rds.html

Class.forName("com.mysql.jdbc.Driver").newInstance();
con = java.sql.DriverManager.getConnection("jdbc:mysql://hostname:port/" + "dbname", "userName","password");
