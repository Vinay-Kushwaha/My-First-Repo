# Practice Problems from MySQL

### [Problem 1 Revising the Select Query I](https://www.hackerrank.com/challenges/revising-the-select-query/problem?isFullScreen=true)
  #### Sol
``` sql
Select * from CITY where countrycode = "USA" and population>100000;
```
   
 ### [Problem 2 Revising the Select Query II](https://www.hackerrank.com/challenges/revising-the-select-query-2/problem?isFullScreen=true)
  #### Sol
``` sql
Select name from CITY where countrycode="USA" and population>120000;
```
### [Problem 3 Select All](https://www.hackerrank.com/challenges/select-all-sql/problem)
#### Sol
``` sql
Select * from CITY;
```
### [Problem 4 Select By ID](https://www.hackerrank.com/challenges/select-by-id/problem?isFullScreen=true)
#### Sol
``` sql
Select * from CITY where ID=1661;
```
 ### [Problem 5 Japanese Cities' Attributes](https://www.hackerrank.com/challenges/japanese-cities-attributes/problem?isFullScreen=true)
#### Sol
``` sql
Select * from CITY where countrycode="JPN";
```
### [Problem 6 Japanese Cities' Names](https://www.hackerrank.com/challenges/japanese-cities-name/problem?isFullScreen=true)
#### sol
``` sql
Select name from CITY where countrycode ="JPN";
```
### [Problem 7 Weather Observation Station 1](https://www.hackerrank.com/challenges/weather-observation-station-1/problem?isFullScreen=true)
#### sol
``` sql
Select city, state from Station;
```
### [Problem 8 Weather Observation Station 3](https://www.hackerrank.com/challenges/weather-observation-station-3/problem?isFullScreen=true)
#### sol
``` sql
Select distinct city from station where mod(ID,2)=0;
```
