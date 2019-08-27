# TestesSqlite

select * from bolusTable order by glucose_id,meal_id;

select glucose.glucose, meals.meal, bolusTable.bolus from glucose inner join bolusTable on bolusTable.glucose_id = glucose._id inner join meals on meals._id = bolusTable.meal_id order by glucose_id,meal_id;





Id | Acima de | Café da manhã | Colação | Almoço | Lanche da tarde | Jantar | Ceia | Madrugada
---|----------|---------------|---------|--------|-----------------|--------|------|----------
1  | >=60     | 1             | 1       | 1.5    | 0 | 2 | 0 | 0
2  | >=100    | 1.5           | 1.5     | 2      | 0.5 | 2.5 | 0 | 0
3  | >=150    | 2             | 2       | 2.5    | 1 | 3 | 0.5 | 0 | 
4  | >=200    | 2.5           | 2.5     | 3      | 1.5 | 3.5 | 1 | 0 
5  | >=250    | 3             | 3       | 3.5    | 2 | 4 | 1.5 | 0 | 
6  | >=300    | 4             | 4       | 4      | 2.5 | 4.5 | 2 | 0 | 
7  | >=400    | 5             | 5       | 5      | 3 | 5 | 2.5 | 0 | 
8  | >=500    | 6             | 6       | 6      | 3.5 | 5.5 | 3 | 0 | 



