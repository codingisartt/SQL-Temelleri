#### 1-Test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee(
    id INTEGER,
    name VARCHAR(50) ,
    birthday DATE ,
    email VARCHAR(100)
);
```
#### 2-Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into MOCK_DATA (id, first_name, birthday, email) values (1, 'Cynthie', '9/6/1991', 'cstillman0@gizmodo.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (2, 'Maybelle', '12/14/1998', 'mbute1@ted.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (3, 'Andre', '11/17/1988', 'aganders2@flavors.me');
insert into MOCK_DATA (id, first_name, birthday, email) values (4, 'Kippie', '10/4/1998', 'kleneham3@unc.edu');
insert into MOCK_DATA (id, first_name, birthday, email) values (5, 'Audrye', '3/15/1995', 'abehnecken4@barnesandnoble.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (6, 'Rodi', '10/5/1998', 'rsilvers5@gravatar.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (7, 'Adrien', '1/1/1999', 'ajewiss6@rediff.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (8, 'Padriac', '6/20/1995', 'pangelini7@cornell.edu');
insert into MOCK_DATA (id, first_name, birthday, email) values (9, 'Merrick', '7/21/1997', 'mkopfer8@drupal.org');
insert into MOCK_DATA (id, first_name, birthday, email) values (10, 'Arte', '5/1/2000', 'abannester9@wisc.edu');
insert into MOCK_DATA (id, first_name, birthday, email) values (11, 'Vivi', '9/15/1991', 'vlytea@webs.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (12, 'Maire', '6/16/1998', 'mbrydonb@squidoo.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (13, 'Drona', '1/11/1998', 'dwestwaterc@cpanel.net');
insert into MOCK_DATA (id, first_name, birthday, email) values (14, 'Gretta', '3/25/1997', 'gjolld@about.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (15, 'Juliane', '12/17/1995', 'jdybelle@prweb.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (16, 'Kenn', '4/30/1991', 'klowethf@wufoo.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (17, 'Ulrikaumeko', '3/12/1995', 'ufitzsimmonsg@1und1.de');
insert into MOCK_DATA (id, first_name, birthday, email) values (18, 'Grange', '9/22/1993', 'gholdh@ezinearticles.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (19, 'Ulrikaumeko', '8/13/1995', 'uledgertoni@vk.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (20, 'Maure', '2/19/1994', 'msolwayj@cloudflare.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (21, 'Leupold', '7/23/1994', 'lscandredk@last.fm');
insert into MOCK_DATA (id, first_name, birthday, email) values (22, 'Genny', '12/8/1990', 'getchinghaml@theglobeandmail.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (23, 'Manfred', '4/19/1994', 'mpulequem@1688.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (24, 'Jule', '1/17/1999', 'jbattmann@booking.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (25, 'Charissa', '4/25/1997', 'cdeacono@chron.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (26, 'Marion', '4/17/1999', 'mmoylerp@examiner.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (27, 'Sutherland', '5/3/1990', 'spicottq@wikipedia.org');
insert into MOCK_DATA (id, first_name, birthday, email) values (28, 'Ely', '10/17/1990', 'estendallr@jugem.jp');
insert into MOCK_DATA (id, first_name, birthday, email) values (29, 'Dimitry', '9/25/1989', 'dgillilands@howstuffworks.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (30, 'Sibelle', '8/5/1994', 'smadgint@reuters.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (31, 'Viviana', '7/1/2000', 'vgunstoneu@shareasale.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (32, 'Lucio', '9/25/1997', 'lizchakiv@baidu.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (33, 'Hubey', '2/17/1998', 'hollinw@naver.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (34, 'Howey', '9/8/1994', 'hgosforthx@wsj.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (35, 'Arlana', '1/7/1997', 'ashoulery@marketwatch.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (36, 'Stinky', '4/18/1989', 'sbondleyz@opera.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (37, 'Antonino', '10/15/1988', 'acaven10@surveymonkey.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (38, 'Katee', '12/3/1993', 'kquinlan11@thetimes.co.uk');
insert into MOCK_DATA (id, first_name, birthday, email) values (39, 'Clari', '6/19/1992', 'cduddin12@eepurl.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (40, 'Oona', '9/26/1990', 'omessam13@mail.ru');
insert into MOCK_DATA (id, first_name, birthday, email) values (41, 'Gibby', '5/28/1991', 'gduthie14@friendfeed.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (42, 'Titos', '10/13/1999', 'tmisson15@walmart.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (43, 'Daniel', '2/19/1992', 'dlynnett16@cdbaby.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (44, 'Lenna', '6/8/1999', 'lrainville17@cargocollective.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (45, 'Guenevere', '10/22/1991', 'gcaren18@youku.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (46, 'Brana', '11/21/1992', 'bfaiers19@auda.org.au');
insert into MOCK_DATA (id, first_name, birthday, email) values (47, 'Ilyse', '6/14/1990', 'ijosland1a@illinois.edu');
insert into MOCK_DATA (id, first_name, birthday, email) values (48, 'Sibylla', '11/24/1994', 'shinkins1b@howstuffworks.com');
insert into MOCK_DATA (id, first_name, birthday, email) values (49, 'Alayne', '6/17/1997', 'amcphail1c@cornell.edu');
insert into MOCK_DATA (id, first_name, birthday, email) values (50, 'Nissa', '1/30/1989', 'nhaliburton1d@cargocollective.com');
```
#### 3-Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee  
SET name = 'Lenna',
birthday = '11/24/1994',
email = 'lrainville17@cargocollective.com'
WHERE id =10;

UPDATE employee
SET name = 'Aras',
birthday = '6/17/1997',
email = 'nhaliburton1d@cargocollective.com'
WHERE id =40;

UPDATE employee
SET name = 'Pars',
birthday = '6/17/1998',
email = 'burton1d@cargocollective.com'
WHERE id =1;

UPDATE employee
SET name = 'Alayne',
birthday = '6/17/1990',
email = 'burtod@cargocollective.com'
WHERE id =19;

UPDATE employee
SET name = 'Nissa',
birthday = '6/17/1998',
email = 'buron1d@cargocollective.com'
WHERE id =17;
```
#### 4-Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee
WHERE id =43;

DELETE FROM employee
WHERE name;

DELETE FROM employee
WHERE birthday;

DELETE FROM employee
WHERE email;
```