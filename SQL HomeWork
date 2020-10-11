#1 Брой на потребители.
Select * from users;

#2 Най-стария потребител
Select username, birthDate from users
order by birthDate asc limit 1;

#3 Най-младия потребител.
Select username, birthDate from users
order by birthDate desc limit 1;

#4. Колко юзъра са регистрирани с мейли от abv и колко от gmail и колко с различни от двата.
Select count(email) from users
where email like '%abv%';

Select count(email) from users
where email like '%gmail%';

Select count(email) from users
where email not like '%gmail%' or '%abv%';

#5. Кои юзъри са banned.
select * from users where isBanned=1;

#6. Изкарайте всички потребители от базата като ги наредите по име в азбучен ред и дата на раждане(от най-младия към най-възрастния).

Select username, birthdate from users
order by birthdate asc;

#7. Изкарайте всички потребители от базата, на които потребителското име започва с a.

Select * from users where username like 'a%';

#8. Изкарайте всички потребители от базата, които съдържат а username името си.

Select * from users where username like '%a%';

#9. Изкарайте всички потребители от базата, чието име се състои от 2 имена.

select * from users where username like '%%' 




