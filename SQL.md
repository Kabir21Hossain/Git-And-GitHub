![alt text](sqlimg.jpg)

<center><h2><p style="background-color:green"><b><i> KEYWORD</i></b><br><hr></p></h2>

>* <p style="color: green">SELECT </p>
>* <p style="color: green">FROM</p>
>* <p style="color: green"> WHERE</p>
>* <p style="color: green">NULL</p>
>* <p style="color: green">NOT</p>
>* <p style="color: green">IS</p>
>* <p style="color: green">CREATE TABLE </p>
>* <p style="color: green">DISTINCT</p>
>* <p style="color: green">ORDER BY ASC  DSC</p>
>* <p style="color: green">AND</p>
>* <p style="color: green">OR</p>
>* <p style="color: green">INSERT INTO</p> 
>* <p style="color: green">VALUES </p> 
>* <p style="color: green"> SET</p> 
>* <p style="color: green">VALUES</p>
>* <p style="color: green">UPDATE</p>
>* <p style="color: red">DELETE</p>
>* <p style="color: green">IN </p>
>* <p style="color: green">BETWEEN</p>
>* <p style="color: green">SELECT TOP</p>
>* <p style="color: green">As</p>
>* <p style="color: green">GROUP BY</p>
>* <p style="color: green">JOIN  </p>
>* <p style="color: green">NOT  </p>
>* <p style="color: green">RENAME </p>
>* <p style="color: green">ADD </p>
>* <p style="color: green">MODIFY</p>


</center>
#
<center><h2><p style="background-color:magenta"> AGGREGATE FUNCTION</p> 
</h2>

* <p style="color: magenta">MAX( )
* <p style="color: magenta">MIN( )
* <p style="color: magenta"> SUM( )
*  <p style="color: magenta"> AVG( )
* <p style="color:magenta"> COUNT( )<br>
</center>


<center><h2><p style="background-color:purple">WildCard</p></h2></center>
<center><p style="color:green">[1] _ =single character<br>
[2] % = multiple characters  </p></center>

 <center><h3 style="color:magenta"><p style="background-color:orange">For Example</p></h3></center>
 
<code>

%k= Ends with k<br>
k%= starts with k<br>
%k%= it contains k<br>
_k% = k in second position<br>
__k% = it contains at least 3 characters<br>
L__nd_%=starts with L and 4th 5th place hold nd <br>
'[bsp]%'= starts with b || s || p<br>
[a-f]%= from a to f <br>
</code>
<hr color="GREEN" width="600"/>
<center style="color:red"><p style="background-color:blue"> Database</p>  </center>


* <p style="color:green">CREATE DATABASE</p>
* <p style="color:green"> DROP DATABASE  </p>
* <p style="color:green"> BACKUP DATABASE </p>
<h3><p style="color:green"> Table</h3>  </p> 

* <p style="color:green">CREATE TABLE  </p>

* <p style="color:green">DROP TABLE</p>
* <p style="color:green"> TRUNCATE TABLE</p>
* <p style="color:green">ALTER TABLE</p>
* <p style="color:green">Constraint(NOT NULL, PRIMARY KEY,FOREIGN KEY,UNIQE)
</p>
<hr color="magenta">
<center><p style="Font-family:gothic"> <h1>Datatable</h1></p></center>
<hr color="magenta">
<table border=2 style="background-color:purple">
<tbody>
<thead>A table to manipulate through SQL</thead><br><br>
<tr>
<th>ID</th>
<th>name</th>
<th>Gmail</th>
<th>ProductName</th>
<th>Price</th>
<th>Piad</th>
<th>Due</th>
<th>Discount</th>
</tr>

<tr>
<td>1342</td>
<td>Md kabir hossain </td>
<td>kabir20304@gmail.com</td>
<td>Coffee</td>
<td>100 tk</td>
<td>90 tk</td>
<td>00 tk</td>
<td>10 tk</td>
</tr>
<tr>
<td>2342</td>
<td>rajendraPurahitGajendra</td>
<td>raja231@gmail.com</td>
<td>rice</td>
<td>40 tk</td>
<td>40 tk</td>
<td>0.0 tk</td>
<td>0.0 tk</td>
</tr>

<td>2342</td>
<td>rajendraPurahitGajendra</td>
<td>raja231@gmail.com</td>
<td>rice</td>
<td>40 tk</td>
<td>40 tk</td>
<td>0.0 tk</td>
<td>0.0 tk</td>
</tr>
<td>2342</td>
<td>rajendraPurahitGajendra</td>
<td>raja231@gmail.com</td>
<td>rice</td>
<td>40 tk</td>
<td>40 tk</td>
<td>0.0 tk</td>
<td>0.0 tk</td>
</tr>
<td>2342</td>
<td>rajendraPurahitGajendra</td>
<td>raja231@gmail.com</td>
<td>rice</td>
<td>40 tk</td>
<td>40 tk</td>
<td>0.0 tk</td>
<td>0.0 tk</td>
</tr>
<td>2342</td>
<td>rajendraPurahitGajendra</td>
<td>raja231@gmail.com</td>
<td>rice</td>
<td>40 tk</td>
<td>40 tk</td>
<td>0.0 tk</td>
<td>0.0 tk</td>
</tr>
<td>2342</td>
<td>rajendraPurahitGajendra</td>
<td>raja231@gmail.com</td>
<td>rice</td>
<td>40 tk</td>
<td>40 tk</td>
<td>0.0 tk</td>
<td>0.0 tk</td>
</tr>
<td>2342</td>
<td>rajendraPurahitGajendra</td>
<td>raja231@gmail.com</td>
<td>rice</td>
<td>40 tk</td>
<td>40 tk</td>
<td>0.0 tk</td>
<td>0.0 tk</td>
</tr>
</tbody>
</table>
 

 <center><p style="Font-family:gothic"> <h1>Select query</h1></p></center>
 
<hr color="red"/>
<pre>
<code> 

>SELECT * FROM Datatable;  <br>
SELECT Name FROM Datatable;<br>
SELECT Name, Gmail,Price FROM Datatable;<br>
SELECT DISTINCT Name FROM Datatable;<br>
SELECT ProductName,price,paid,due,discount FROM Datatable;<br>
SELECT DISTINCT ProductName,Price FROM Datatble;<br>
SELECT Name,price FROM Datatable
WHERE Name='Md Kabir Hossain';<br>
SELECT * FROM Datatable WHERE Name='Md kabir Hossain';<br>
SELECT * FROM Datatable WHERE 
ID IN BETWEEN 2000 AND 4000;<br>
SELECT * FROM Datatable 
ORDER BY Name ;<br>
SELECT * FROM Datatable 
ORDER BY Price DESC;<br>
SELECT Name FROM Datatable 
WHERE Name LIKE 'k%' AND PRICE<200;<br>
SELECT Name FROM Datatable 
WHERE Name LIKE 'k%' AND (Price >10 tk OR ID< 300000); <br>
SELECT * FROM Datatable 
ORDER BY Name ASC, Price DESC;<br>
SELECT * FROM Datatable WHERE Name NOT LIKE 'k%';<br>
SELECT * Name FROM Datatable WHERE Address NOT IN ('Kashimpur','Gazipur','London');<br>
SELECT * FROM Datatable WHERE NOT Name='RajendrapurahitGajenda';<br>
SELECT * FROM Datatable WHERE ID NOT BETWEEN 10 AND 1000;<br>
SELECT * FROM Datatable WHERE NOT ID>20 ;<br>
SELECT * FROM Datatable WHERE ID !>20 ;<br>
CREATE TABLE ktable(
    SerialNO autonumber NOT NULL  PRIMARY KEY,
    ProductID autonumber FOREIGNKEY,
    ExpiryDate Long text
);
CREATE TABLE copytable AS SELECT name,gmail,price 
FROM Datatable;
ALTER TABLE datatable 
ADD address varchar(255);
ALTER TABLE datatable 
ADD email varchar(255);
ALTER TABLE datatable 
DROP COLOUMN gmail;
ALTER TABLE datatable
ALTER COLOUMN gmail longText;


>INSERT INTO ktable(SerialNO,ProductID,ExpiryDate) 
VALUES('1','3421','2/03/2030');<br>


>INSERT INTO ktable
VALUES('1','3421','2/03/2030');<br>

>INSERT INTO ktable(ExpiryDate) 
VALUES('2/03/2030');<br>
INSERT INTO ktable(SerialNO,ProductID,ExpiryDate) 
VALUES('1','3421','2/03/2030'),('1','3421','2/03/2030'),('1','3421','2/03/2030'),('1','3421','2/03/2030');<br>
 UPDATE  Datatable 
 SET Name='umrao jaaan',Gmail='umraojaan20304@gmail.com'
 WHERE Name='rajendrapurahitGajendra';
 >> If you don't use Where clause, then complete table will be updated.
  
  >DELETE FROM Datatable 
  WHERE Price=10;
  DELETE FROM Datatable;(all rows are deleted but table)
  DROP TABLE Datatable;
  TRUNCATE TABLE Datatable;

  >SELECT TOP 3 * FROM Datatable;
  SELECT * FROM Datatable 
  LIMIT 3;
  SELECT TOP 2 Name,price,paid,due FROM Datatable;

 >>Aggreegate Function 
 >
 >SELECT SUM(Price) AS total
 FROM Datatable;
 SELECT Name 
 FROM Datatable 
 WHERE (Price <SELECT SUM(PRICE));
 SELECT MAX(Price) FROM Datatable;
 SLECT MAX(Price) As Maximum FROM Datatable;
 SELECT MIN(Price) AS minimum
 FROM Datatable 
 GROUP BY Name;
 SLECET COUNT(DISTINCT Name) FROM Datatable;

>SELECT Name As CustomerName FROM Datatable;
SELECT Name As CustomerName, Gmail As CustomerMail
FROM Datatable;






</code>
 </pre>


 #
# [Link: To learn SQL](https://www.w3schools.com/sql/)




