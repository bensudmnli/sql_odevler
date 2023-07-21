## sql ödev8
1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (id, name, email, birthday) values (1, 'Danny', 'dmaiklem0@netvibes.com', '9/9/2022');
insert into employee (id, name, email, birthday) values (2, 'Addia', 'alibri1@hud.gov', '4/21/2023');
insert into employee (id, name, email, birthday) values (3, 'Ezri', 'eharrington2@ning.com', '7/24/2022');
insert into employee (id, name, email, birthday) values (4, 'Reinhard', 'rgobbet3@house.gov', '10/26/2022');
insert into employee (id, name, email, birthday) values (5, 'Timothy', 'tproctor4@ftc.gov', '7/6/2023');
insert into employee (id, name, email, birthday) values (6, 'Leslie', 'lstandall5@sogou.com', '2/24/2023');
insert into employee (id, name, email, birthday) values (7, 'Dorena', 'dguage6@example.com', '5/22/2023');
insert into employee (id, name, email, birthday) values (8, 'Roselin', 'rstepto7@bandcamp.com', '8/2/2022');
insert into employee (id, name, email, birthday) values (9, 'Hamish', 'hheeron8@tripod.com', '8/2/2022');
insert into employee (id, name, email, birthday) values (10, 'Leola', 'ljakeway9@wordpress.com', '2/8/2023');
insert into employee (id, name, email, birthday) values (11, 'Sam', 'ssherringhama@delicious.com', '2/21/2023');
insert into employee (id, name, email, birthday) values (12, 'Thornie', 'tmccluneyb@gmpg.org', '3/19/2023');
insert into employee (id, name, email, birthday) values (13, 'Hilary', 'hgeraghtyc@godaddy.com', '11/14/2022');
insert into employee (id, name, email, birthday) values (14, 'Harmonie', 'hbutlandd@time.com', '7/2/2023');
insert into employee (id, name, email, birthday) values (15, 'Siana', 'sdegregolie@google.ru', '7/13/2023');
insert into employee (id, name, email, birthday) values (16, 'Holden', 'hbarstowkf@sphinn.com', '8/20/2022');
insert into employee (id, name, email, birthday) values (17, 'Phillipe', 'pcallisg@va.gov', '6/5/2023');
insert into employee (id, name, email, birthday) values (18, 'Luz', 'lsimisterh@naver.com', '8/26/2022');
insert into employee (id, name, email, birthday) values (19, 'Malory', 'mhallfordi@wikipedia.org', '8/3/2022');
insert into employee (id, name, email, birthday) values (20, 'Brandyn', 'bpridittj@webnode.com', '4/3/2023');
insert into employee (id, name, email, birthday) values (21, 'Arlana', 'arickardk@mapy.cz', '12/12/2022');
insert into employee (id, name, email, birthday) values (22, 'Prudy', 'pfattorinil@scientificamerican.com', '11/15/2022');
insert into employee (id, name, email, birthday) values (23, 'Pinchas', 'phackingem@instagram.com', '9/1/2022');
insert into employee (id, name, email, birthday) values (24, 'Susannah', 'salsfordn@epa.gov', '2/11/2023');
insert into employee (id, name, email, birthday) values (25, 'Donny', 'dbiltono@over-blog.com', '4/17/2023');
insert into employee (id, name, email, birthday) values (26, 'Estelle', 'etamblingsonp@reference.com', '4/4/2023');
insert into employee (id, name, email, birthday) values (27, 'Donny', 'dkerseyq@squidoo.com', '10/30/2022');
insert into employee (id, name, email, birthday) values (28, 'Gloriana', 'gtaillr@github.io', '10/7/2022');
insert into employee (id, name, email, birthday) values (29, 'Bili', 'bbolderoes@sphinn.com', '11/24/2022');
insert into employee (id, name, email, birthday) values (30, 'Bellanca', 'bschieferstent@theguardian.com', '2/3/2023');
insert into employee (id, name, email, birthday) values (31, 'Nichols', 'nhebbornu@list-manage.com', '2/3/2023');
insert into employee (id, name, email, birthday) values (32, 'Maggy', 'mspencev@goo.ne.jp', '12/20/2022');
insert into employee (id, name, email, birthday) values (33, 'Aleen', 'amixerw@dailymail.co.uk', '5/15/2023');
insert into employee (id, name, email, birthday) values (34, 'Lewie', 'lnarriex@1688.com', '5/21/2023');
insert into employee (id, name, email, birthday) values (35, 'Sauveur', 'spingy@cbc.ca', '11/12/2022');
insert into employee (id, name, email, birthday) values (36, 'Taylor', 'tblowinz@reuters.com', '2/14/2023');
insert into employee (id, name, email, birthday) values (37, 'Liz', 'lbrimson10@spotify.com', '12/15/2022');
insert into employee (id, name, email, birthday) values (38, 'Lew', 'lpoli11@elpais.com', '3/6/2023');
insert into employee (id, name, email, birthday) values (39, 'Eugenie', 'erosendorf12@prlog.org', '9/28/2022');
insert into employee (id, name, email, birthday) values (40, 'Ardith', 'agubbin13@craigslist.org', '7/31/2022');
insert into employee (id, name, email, birthday) values (41, 'Henri', 'hwiburn14@furl.net', '3/23/2023');
insert into employee (id, name, email, birthday) values (42, 'Casper', 'cdurtnal15@utexas.edu', '12/27/2022');
insert into employee (id, name, email, birthday) values (43, 'Cindie', 'cbradwell16@unicef.org', '7/7/2023');
insert into employee (id, name, email, birthday) values (44, 'Imogen', 'ivispo17@bigcartel.com', '3/29/2023');
insert into employee (id, name, email, birthday) values (45, 'Bernadene', 'bcescon18@ifeng.com', '5/1/2023');
insert into employee (id, name, email, birthday) values (46, 'Liesa', 'lbergeau19@meetup.com', '12/3/2022');
insert into employee (id, name, email, birthday) values (47, 'Janina', 'jsamwell1a@domainmarket.com', '12/12/2022');
insert into employee (id, name, email, birthday) values (48, 'Karrie', 'kenstone1b@istockphoto.com', '8/8/2022');
insert into employee (id, name, email, birthday) values (49, 'Bernardina', 'bfrowing1c@sciencedaily.com', '7/9/2023');
insert into employee (id, name, email, birthday) values (50, 'Orbadiah', 'oguirardin1d@irs.gov', '6/15/2023');

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee
SET name ='Jane' 
WHERE id=50;

UPDATE employee
SET name='Mary'
WHERE birthday = '7/9/2023';

UPDATE employee
SET name='Harry'
WHERE email = 'cdurtnal15@utexas.edu';

UPDATE employee
SET email='newmail@mail.com'
WHERE birthday = '3/23/2023';

UPDATE employee
SET birthday='2/14/2023'
WHERE name = 'Casper';

SELECT * FROM employee

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee
WHERE name = 'Eugenie';

DELETE FROM employee
WHERE id=10;

DELETE FROM employee
WHERE birthday='12/27/2022';

DELETE FROM employee
WHERE email='bbolderoes@sphinn.com';

DELETE FROM employee
WHERE birthday='6/15/2023';
