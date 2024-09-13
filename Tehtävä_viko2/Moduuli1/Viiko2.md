# tehtävä viko 1

### tehtävä1
select *
from goal;
![kuva](kuva1.png)

### tehtävä2
select name airport_type 
from airport 
where iso_country = "FI";
![](kuva2.png)

### Tehtävä3
Select name 
from airport
where iso_country ="FI"
order by name;
![](kuva3.png))

### Tehtävä4
select name, type 
from airport 
where iso_country = "FI" 
order by type, name
![](kuva4.png)

### Tehtävä5
select name 
from country
where name like "F%"
![](kuva5.png)

### Tehtävä6
select name 
from country 
where name like "%F%";
![](kuva6.png)

### Tehtävä7
select location 
from game 
where screen_name = "Vesa";
![](kuva7.png)

### Tehtävä8
select co2_consumed 
from game 
where screen_name = "Ilkka"
![](kuva8.png)
### Tehtävä9
SELECT distinct co2_budget
FROM game;
![](kuva9.png))