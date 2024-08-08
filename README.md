create database project1;
use project1;

create table students(
st_id int primary key,
st_name varchar(20) not null,
dob date not null,
gender varchar(10) not null,
cont_no bigint unique not null,
email varchar(50) unique not null,
address text not null,
join_date date not null,
room_id int,
status enum('active','inactive','graduate') default('active')
);


insert into students (st_id,st_name,dob, gender,cont_no,email,address,join_date,room_id,st)
values (1,'')



create table rooms(
room_id int,
floor int,
capacity varchar(20),
hos_id int,
status varchar(20)
);

drop table rooms;
drop table students;
drop table hostels;

create table hostels(
hostel_id int,
hostel_name varchar(20),
location text,
total_rooms varchar(50),
warden_name varchar(20)
);



create table staff(
staff_id int,
staff_name varchar(20),
role varchar(20),
cont_no bigint,
email varchar(50),
hostel_id int
);



create table facilities(
facility_id int,
facility_name varchar(20),
hostel_id int
);
