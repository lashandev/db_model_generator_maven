# db_model_generator_maven
Database model class generator Using Maven Pluging

File : src/main/resources/hibernate.properties
Point "Database_Name" in hibernate.connection.url and hibernate.default_schema to your Database Name and change username and password

File : src/main/resources/hibernate.cfg.xml
Point <property name="hibernate.connection.url"> property value to your Database Name and change username and password

File : src/main/resources/hibernate.reveng.xml
Point <schema-selection match-catalog="Database_Name"/> to your Database Name
Point your entity package <table-filter match-name=".*" package="com.L_R_F.lashan.entity"/>
