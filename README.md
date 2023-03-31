# data-sql-
#I had started learing and revising data &amp;sql from begining
#CREATING A DATABASE :
create database bakery;
use bakery;
#CREATINGTABLE
create table sweet (ID  integer,item_name VARCHAR(50),price decimal(10,2));
select * from sweet;
create table savoury( ID integer NOT NULL,item_name VARCHAR(50),price decimal(10,2),main_ingrediant varchar(50),primary key(ID));
#INSERTINGVALUESIN THE DATABASE 
insert into sweet(ID,item_name,price)
VALUES
(1,'doughnut',0.5),
(2,'croissant',0.75),
(3, 'painauchocalat',0.55),
(4,'cinnamontwirl',0.45),
(5,'cannoli',0.88),
(6,'appletart',1.12);

insert into savoury
VALUES
(1,'meatpie',1.25,'pork'),
(2,'sausageroll',1,'egg'),
(3,'pasty',2.45,'beef');
select * from sweet;
select * from savoury;
![image](https://user-images.githubusercontent.com/46300558/229107042-7e4fd2d3-c4ec-458f-9963-76a478913c39.png)
![image](https://user-images.githubusercontent.com/46300558/229107139-54aa9d20-91f3-46c9-9adc-e41fe036ebdd.png)
