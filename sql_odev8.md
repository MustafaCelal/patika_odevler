1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
  - `CREATE TABLE employee (id SERIAL PRIMARY KEY, name VARCHAR(50) NOT NULL,	email VARCHAR(100),	birthday DATE);`
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
  insert into employee (id, name, email, birthday) values (1, 'Carleen Aucott', 'caucott0@dell.com', '5/5/2002');
  insert into employee (id, name, email, birthday) values (2, 'Allianora Avieson', 'aavieson1@elpais.com', '6/2/1980');
  insert into employee (id, name, email, birthday) values (3, 'Paige O''Cullinane', 'pocullinane2@cbsnews.com', '9/16/1972');
  insert into employee (id, name, email, birthday) values (4, 'Gaven Babidge', 'gbabidge3@blinklist.com', '11/20/1974');
  insert into employee (id, name, email, birthday) values (5, 'Lotti Standish-Brooks', 'lstandishbrooks4@vimeo.com', '5/11/1973');
  insert into employee (id, name, email, birthday) values (6, 'Zelig McCaughren', 'zmccaughren5@japanpost.jp', '4/6/1976');
  insert into employee (id, name, email, birthday) values (7, 'Suki Stapford', 'sstapford6@ebay.co.uk', '1/31/2002');
  insert into employee (id, name, email, birthday) values (8, 'Keven Swatradge', 'kswatradge7@jugem.jp', '6/24/1987');
  insert into employee (id, name, email, birthday) values (9, 'Yettie Hambribe', 'yhambribe8@patch.com', '1/2/1973');
  insert into employee (id, name, email, birthday) values (10, 'Lockwood Lundon', 'llundon9@timesonline.co.uk', '5/22/1985');
  insert into employee (id, name, email, birthday) values (11, 'Toddy Hingeley', 'thingeleya@cocolog-nifty.com', '12/8/1996');
  insert into employee (id, name, email, birthday) values (12, 'Benedicta Ebourne', 'bebourneb@shutterfly.com', '1/30/1963');
  insert into employee (id, name, email, birthday) values (13, 'Lurline Irvine', 'lirvinec@gizmodo.com', '4/3/1987');
  insert into employee (id, name, email, birthday) values (14, 'Silvia Hiom', 'shiomd@freewebs.com', '9/20/1964');
  insert into employee (id, name, email, birthday) values (15, 'Nyssa Archer', 'narchere@microsoft.com', '7/15/1989');
  insert into employee (id, name, email, birthday) values (16, 'Sisile Shotter', 'sshotterf@dropbox.com', '2/16/1991');
  insert into employee (id, name, email, birthday) values (17, 'Hunfredo Dukelow', 'hdukelowg@samsung.com', '4/25/1970');
  insert into employee (id, name, email, birthday) values (18, 'Violet Fisby', 'vfisbyh@army.mil', '4/15/1981');
  insert into employee (id, name, email, birthday) values (19, 'Crin Schoolcroft', 'cschoolcrofti@g.co', '9/24/1982');
  insert into employee (id, name, email, birthday) values (20, 'Ron Ehrat', 'rehratj@wiley.com', '1/13/1974');
  insert into employee (id, name, email, birthday) values (21, 'Elsa Birchenough', 'ebirchenoughk@foxnews.com', '8/22/1996');
  insert into employee (id, name, email, birthday) values (22, 'Garrard Kob', 'gkobl@marketwatch.com', '10/11/2001');
  insert into employee (id, name, email, birthday) values (23, 'Jessalyn Balston', 'jbalstonm@mozilla.org', '11/6/1971');
  insert into employee (id, name, email, birthday) values (24, 'Kelcie Gallager', 'kgallagern@hubpages.com', '6/2/1966');
  insert into employee (id, name, email, birthday) values (25, 'Cynthie Iwanczyk', 'ciwanczyko@odnoklassniki.ru', '11/20/1969');
  insert into employee (id, name, email, birthday) values (26, 'Carine Tofful', 'ctoffulp@taobao.com', '9/18/1995');
  insert into employee (id, name, email, birthday) values (27, 'Armin Baxster', 'abaxsterq@blogger.com', '4/26/1967');
  insert into employee (id, name, email, birthday) values (28, 'Veronique Josefer', 'vjoseferr@telegraph.co.uk', '5/27/1967');
  insert into employee (id, name, email, birthday) values (29, 'Gloriana Marrington', 'gmarringtons@diigo.com', '6/20/1985');
  insert into employee (id, name, email, birthday) values (30, 'Federico Francklin', 'ffrancklint@ebay.com', '5/14/1987');
  insert into employee (id, name, email, birthday) values (31, 'Prescott Sherrin', 'psherrinu@flavors.me', '8/15/1996');
  insert into employee (id, name, email, birthday) values (32, 'Issiah Cheese', 'icheesev@moonfruit.com', '11/3/1962');
  insert into employee (id, name, email, birthday) values (33, 'Zeke Finey', 'zfineyw@behance.net', '5/22/1964');
  insert into employee (id, name, email, birthday) values (34, 'Alvy MacMeanma', 'amacmeanmax@ocn.ne.jp', '8/21/1978');
  insert into employee (id, name, email, birthday) values (35, 'Shelden Nicholas', 'snicholasy@accuweather.com', '12/7/2001');
  insert into employee (id, name, email, birthday) values (36, 'Nadean Sauniere', 'nsaunierez@huffingtonpost.com', '10/1/1996');
  insert into employee (id, name, email, birthday) values (37, 'Tracey Ottawell', 'tottawell10@intel.com', '5/20/1993');
  insert into employee (id, name, email, birthday) values (38, 'Flossi Westmore', 'fwestmore11@php.net', '8/14/1988');
  insert into employee (id, name, email, birthday) values (39, 'Shaylah Pavis', 'spavis12@ebay.co.uk', '10/24/1964');
  insert into employee (id, name, email, birthday) values (40, 'Kassey Broyd', 'kbroyd13@wikipedia.org', '2/9/1988');
  insert into employee (id, name, email, birthday) values (41, 'Clari Fenne', 'cfenne14@cnbc.com', '12/2/1989');
  insert into employee (id, name, email, birthday) values (42, 'Kale Domenici', 'kdomenici15@yahoo.co.jp', '10/19/1961');
  insert into employee (id, name, email, birthday) values (43, 'Annice Parbrook', 'aparbrook16@fotki.com', '9/16/1977');
  insert into employee (id, name, email, birthday) values (44, 'Bonnibelle Duchant', 'bduchant17@mtv.com', '8/31/1965');
  insert into employee (id, name, email, birthday) values (45, 'Codi Cox', 'ccox18@phpbb.com', '3/8/1972');
  insert into employee (id, name, email, birthday) values (46, 'Kendre Purkins', 'kpurkins19@eepurl.com', '5/13/1965');
  insert into employee (id, name, email, birthday) values (47, 'Reina Cescon', 'rcescon1a@mozilla.com', '2/20/1966');
  insert into employee (id, name, email, birthday) values (48, 'Shanta Dunseath', 'sdunseath1b@exblog.jp', '12/1/1979');
  insert into employee (id, name, email, birthday) values (49, 'Cornela Marchbank', 'cmarchbank1c@w3.org', '10/7/1987');
  insert into employee (id, name, email, birthday) values (50, 'Holly Spindler', 'hspindler1d@nsw.gov.au', '8/28/1986');
```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee SET name = 'Ali Sarı', email = 'ali@info.com', birth_day = "2000-01-01" WHERE id = 1
UPDATE employee SET name = 'Veli Yeşil', email = 'veli@mail.com', birth_day = "2010-01-01" WHERE id = 2
UPDATE employee SET name = 'Ayşe Pembe', email = 'ayse@ayse.com', birth_day = "1995-10-01" WHERE id = 3
UPDATE employee SET name = 'Fatma Mor', email = 'fatma@ogr.edu', birth_day = "1990-01-05" WHERE id = 4
UPDATE employee SET name = 'Ahmet  Adsız', email = 'ahm@ahm.com', birth_day = "1965-05-10" WHERE id = 5
```
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee WHERE id = 1
DELETE FROM employee WHERE id = 2
DELETE FROM employee WHERE id = 3
DELETE FROM employee WHERE id = 4
DELETE FROM employee WHERE id = 5
```
