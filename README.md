<h3>JMeter with MySQL</h3>
<h4>make sure this file "mysql-connector-java-5.1.44" available in the jmeters lib folder. if not download it from GitHub and paste it there. then restart jmeter.</h4>

<h4>connect xampp - create new database and table with sqlyog - add one new data in the table</h4>

<h4>create db</h4>

 ![image](https://github.com/ReNayeem/JMeter-with-MySQL/assets/96969117/5775616d-bdfc-4c4d-8a83-bfb6e5025f95)

<h4>create table</h4>

![image](https://github.com/ReNayeem/JMeter-with-MySQL/assets/96969117/fed3377b-3c57-4f7e-9ba6-bd86ba96608f)

<h4>add a data</h4>

![image](https://github.com/ReNayeem/JMeter-with-MySQL/assets/96969117/f8f90846-6c20-4ceb-b70b-cdc52076e8a4)

<h4>Thread Group > add > config element > jdbc connection configuration</h4>

<h4>right click on thread group > add > config element > random variable (for creating random value)</h4>
<h4>Random Variable</h4>

![image](https://github.com/ReNayeem/JMeter-with-MySQL/assets/96969117/04bd63c5-c221-4c0c-a276-c5f05328e85a)

<h4>thread group > add > sampler > jdbc request</h4>

![image](https://github.com/ReNayeem/JMeter-with-MySQL/assets/96969117/4a6ea8d1-abea-4b22-9355-48be888747b0)

<h4>thread group > add > sampler > jdbc request</h4>

![image](https://github.com/ReNayeem/JMeter-with-MySQL/assets/96969117/e7235dfc-20e6-4d15-b043-d3d49258b212)

<h4>view results tree</h4>

![image](https://github.com/ReNayeem/JMeter-with-MySQL/assets/96969117/5e8f425f-3e6b-489f-ac67-d42780c94693)

<h4>summary report</h4>

![image](https://github.com/ReNayeem/JMeter-with-MySQL/assets/96969117/b91359ee-e586-4a50-a4a1-2eea78d87890)

<h4>END</h4>



