# SQL-ODEV-8

1-test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

2-Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

3-Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

4-Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

Çözüm:

1-

 CREATE TABLE employee(
	id INTEGER PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);

2-

insert into Employee (id, name, email, birthday) values (1, 'Kassia', 'kcleynman0@msn.com', '2016-09-22');
insert into Employee (id, name, email, birthday) values (2, 'Becca', 'bcollaton1@yandex.ru', '1976-04-21');
insert into Employee (id, name, email, birthday) values (3, 'Caro', 'cdobell2@cnn.com', '1994-11-08');
insert into Employee (id, name, email, birthday) values (4, 'Salvidor', 'sgoldstone3@earthlink.net', '2019-06-20');
insert into Employee (id, name, email, birthday) values (5, 'Ellis', 'efollitt4@alexa.com', '1954-12-25');
insert into Employee (id, name, email, birthday) values (6, 'Farr', 'fwigmore5@amazon.co.jp', '1971-02-19');
insert into Employee (id, name, email, birthday) values (7, 'Francoise', 'fpossa6@mit.edu', '1994-10-07');
insert into Employee (id, name, email, birthday) values (8, 'Konrad', 'kgaddie7@ustream.tv', '2018-05-18');
insert into Employee (id, name, email, birthday) values (9, 'Rudy', 'rforlonge8@shop-pro.jp', '1961-05-18');
insert into Employee (id, name, email, birthday) values (10, 'Gaynor', 'glovemore9@list-manage.com', '2021-09-14');
insert into Employee (id, name, email, birthday) values (11, 'Alberto', 'ashallikera@bluehost.com', '2014-05-28');
insert into Employee (id, name, email, birthday) values (12, 'Anthony', 'abrewisb@nbcnews.com', '1997-09-05');
insert into Employee (id, name, email, birthday) values (13, 'Vanya', 'vkebbellc@alexa.com', '1987-12-04');
insert into Employee (id, name, email, birthday) values (14, 'Carroll', 'cpetricd@archive.org', '2018-07-12');
insert into Employee (id, name, email, birthday) values (15, 'Del', 'dsteutlye@blogspot.com', '2004-03-05');
insert into Employee (id, name, email, birthday) values (16, 'Erika', 'emacounf@cocolog-nifty.com', '1996-06-11');
insert into Employee (id, name, email, birthday) values (17, 'Theo', 'trickardesg@webmd.com', '1970-01-31');
insert into Employee (id, name, email, birthday) values (18, 'Mort', 'mtantumh@hostgator.com', '1995-02-21');
insert into Employee (id, name, email, birthday) values (19, 'Frasier', 'fgeanyi@usgs.gov', '2019-06-27');
insert into Employee (id, name, email, birthday) values (20, 'Cyrill', 'cgreenrdej@nih.gov', '1985-02-03');
insert into Employee (id, name, email, birthday) values (21, 'Lucho', 'lgreystokek@jigsy.com', '1982-06-23');
insert into Employee (id, name, email, birthday) values (22, 'Griz', 'gfilipl@meetup.com', '1984-01-23');
insert into Employee (id, name, email, birthday) values (23, 'Zonnya', 'ztarburnm@independent.co.uk', '1999-05-31');
insert into Employee (id, name, email, birthday) values (24, 'Kelley', 'kgantzn@google.com.au', '1968-02-21');
insert into Employee (id, name, email, birthday) values (25, 'Allan', 'aduggeto@unc.edu', '2003-11-03');
insert into Employee (id, name, email, birthday) values (26, 'Karine', 'krisebarerp@artisteer.com', '2012-05-27');
insert into Employee (id, name, email, birthday) values (27, 'Nikoletta', 'ntriplowq@cam.ac.uk', '1962-11-02');
insert into Employee (id, name, email, birthday) values (28, 'Ruth', 'rofferr@studiopress.com', '1989-08-15');
insert into Employee (id, name, email, birthday) values (29, 'Janka', 'jdiess@answers.com', '1980-01-25');
insert into Employee (id, name, email, birthday) values (30, 'Haskel', 'hperettt@ask.com', '1956-06-30');
insert into Employee (id, name, email, birthday) values (31, 'Saleem', 'sappleu@hugedomains.com', '1990-11-08');
insert into Employee (id, name, email, birthday) values (32, 'Alexandrina', 'apuddingv@jimdo.com', '2007-09-01');
insert into Employee (id, name, email, birthday) values (33, 'Helge', 'hkitleew@webeden.co.uk', '1997-09-12');
insert into Employee (id, name, email, birthday) values (34, 'Monica', 'mberringtonx@slashdot.org', '2021-02-16');
insert into Employee (id, name, email, birthday) values (35, 'Elroy', 'ekennicotty@lycos.com', '1952-06-01');
insert into Employee (id, name, email, birthday) values (36, 'Fredi', 'fsantiz@hostgator.com', '2009-03-21');
insert into Employee (id, name, email, birthday) values (37, 'Celestine', 'cfooks10@netscape.com', '1983-03-18');
insert into Employee (id, name, email, birthday) values (38, 'Joyann', 'jspindler11@ihg.com', '2012-10-22');
insert into Employee (id, name, email, birthday) values (39, 'Neilla', 'nchoppen12@quantcast.com', '1995-12-01');
insert into Employee (id, name, email, birthday) values (40, 'Brianna', 'bisabell13@cyberchimps.com', '2002-11-17');
insert into Employee (id, name, email, birthday) values (41, 'Allys', 'acharrett14@businessinsider.com', '1991-08-05');
insert into Employee (id, name, email, birthday) values (42, 'Dulcea', 'dbotger15@nydailynews.com', '1984-05-07');
insert into Employee (id, name, email, birthday) values (43, 'Samantha', 'scharke16@ted.com', '1986-06-20');
insert into Employee (id, name, email, birthday) values (44, 'Byrle', 'bleifer17@furl.net', '2019-07-04');
insert into Employee (id, name, email, birthday) values (45, 'Humfrey', 'hsleney18@wix.com', '1996-01-29');
insert into Employee (id, name, email, birthday) values (46, 'Rycca', 'rleser19@mail.ru', '1970-03-27');
insert into Employee (id, name, email, birthday) values (47, 'Harv', 'hporrett1a@mtv.com', '1974-03-15');
insert into Employee (id, name, email, birthday) values (48, 'Rickey', 'rsprankling1b@deliciousdays.com', '2004-12-03');
insert into Employee (id, name, email, birthday) values (49, 'Kit', 'kblinde1c@instagram.com', '1967-05-06');
insert into Employee (id, name, email, birthday) values (50, 'Scarface', 'sjoiner1d@census.gov', '2021-12-06');

3-
a)

UPDATE Employee
SET name = 'asya'
WHERE name LIKE 'K%';

b)
UPDATE Employee
SET birthday = '1980-02-20'
WHERE id IN(9, 6, 5);

4-

DELETE FROM Employee
WHERE name LIKE 'A%'





