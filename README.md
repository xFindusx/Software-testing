# Software-testing
# Software-testing
-- заполняем таблицу "persons"
insert into persons (person_id, first_name, last_name, role, adress_id, gender)
VALUES (1,'Ilya', 'Abramov', 'student', 1, 'male'),
       (2, 'Denis', 'Alekseev', 'teacher', 2, 'male'),
       (3, 'Christa', 'Stewens', 'teacher', 3, 'female'),
       (4, 'Nannie', 'Wolff', 'teacher', 4, 'male'),
       (5, 'Stine', 'Skaarup', 'student', 5, 'male'),
(6, 'Evert', 'Hills', 'student', 6, 'male'),
(7, 'Kiss', 'Ádámné', 'student', 7, 'male'),
(8, 'Amira', 'Haverinen', 'student', 8, 'male'),
(9, 'Zoe', 'Pfannerstill', 'student', 9, 'female'),
(10, 'Amanda', 'Walker', 'student', 10, 'female'),
(11, 'Antoine', 'Dupuis', 'student', 11, 'male'),
(12, 'Resi', 'Ruf', 'student', 12, 'female'),
(13, 'Ayanda', 'Kok', 'student', 13, 'female'),
(14, 'Cesar', 'Hijo', 'student', 14, 'male'),
(15, 'Isobel', 'Hane', 'student', 15,'female'),
(16, 'Aminu', 'Titilayo', 'student', 16,'female'),
(17, 'Vicky', 'Bennett', 'student', 17, 'female'),
(18, 'Andrey', 'Zhilycov', 'student', 18, 'male'),
(19, 'Yulya', 'Zakharova', 'student', 19,'female'),
(20, 'Emilie', 'Thiry', 'student', 20, 'female'),
(21, 'Fiona', 'Butler', 'student', 21, 'female'),
(22, 'Julia', 'Price', 'student', 22, 'female'),
(23, 'Georgia', 'Collins', 'student', 23, 'female'),
(24, 'Rigoberto', 'Deckow', 'student', 24, 'male'),
(25, 'Millie', 'Beier', 'student',25, 'female'),
(26, 'Fenne', 'Brink', 'student', 26, 'male'),
(27, 'George', 'Shaw', 'student', 27, 'male')
(28, 'Egor', 'Abramov', 'student', 28, 'male');

-- заполняем таблицу "adress"
INSERT INTO adress (adress_id, country, city, street, house)
values (1, 'Russia', 'Lytkarino', 'Sovetskaya', 14),
(2, 'Russia', 'Moscow', 'Olkhovskaya', 14),
(3, 'Germany', 'Berlin', 'Osloer Str.', 87),
(4, 'Czech Republic', 'Lake Addieshire', 'Sven Island', 140),
(5, 'Denmark', 'Ulstrup', 'Nielsenvej', 1),
(6, 'USA', 'Marjorybury', 'Gaylord Loop', 720),
(7, 'Hungary', 'Debrecen', 'Biró köz', 462),
(8, 'Finland', 'Uus-Nico', 'Ramitöyry', 81),
(9, 'USA', 'Jovanimouth', 'Ellen Ridges Suite', 544),
(10, 'United Kingdom' , 'Port Daniel', 'Eleanor Spring', 9),
(11, 'France', 'Delattre', 'boulevard Virginie Pons', 25),
(12, 'Germany', 'Merzig', 'Probststr', 1),
(13, 'South Africa', 'South Belindahaven', 'Ndebele Falls Suite', 860),
(14, 'Venezuela,Alcaraz de Mata', 'Callejón Silvia', 32),
(15, 'Hong Kong', 'Kowloon', 'Nim Lau Estate', 46),
(16, 'Nigeria', 'AladeVille', 'Emmanuel Street', 92),
(17, 'United Kingdom', 'Smithborough', 'Bennett Junctions', 3),
(18, 'Sakartvelo', 'Tbilisi', 'Vakhtang Gargosali turn', 9),
(19, 'Sakartvelo', 'Batumi', 'Mtisdziri', 3),
(20, 'Belgium', 'Alost', 'De Winter', 7),
(21, 'United Kingdom', 'West Leeshire', 'Finley Street', 1),
(22, 'United Kingdom', 'East Zach', 'Adam Drives', 7),
(23, 'United Kingdom', 'Robinsonton', 'Reid Meadow', 7),
(24, 'USA', 'Port Nickolas', 'Pearlie Drive', 4769),
(25, 'New Zeland', 'Miaston', 'Hilario Rise', 80),
(26, 'Netherlands', 'Driebergen-Rijsenburg', 'Uzunweg', 9),
(27, 'United Kingdom', 'Oliviaboroughg', 'Barry Burgs', 289);

-- заполняем таблицу "contacts"
insert into contacts(contact_id, email, phone, persons_id)
values (1, 'greyucrifremmau-5806@yopmail.com', '(+7) 905 733 22 90', 1)

select * from contacts

insert into contacts(contact_id, email, phone, persons_id)
values (2, 'foffebrotraussei-9160@yopmail.com', '(+7) 903 511 13 21', 2)

select * from contacts

insert into contacts(contact_id, email, phone, persons_id)
values (3, 'catrin17@ackermann.net', '02174 368232', 3)

select * from contacts

insert into contacts(contact_id, email, phone, persons_id)
values (4, 'hschmeler@yahoo.com', '1-454-390-4084', 4)

select * from contacts

insert into contacts(contact_id, email, phone, persons_id)
values (5, 'christensen.kjeld@frederiksen.dk', '01397975', 5)

select * from contacts

insert into contacts(contact_id, email, phone, persons_id)
values (6, 'tkohler@hotmail.com', '+1-624-734', 6)

select * from contacts

insert into contacts(contact_id, email, phone, persons_id)
values (7, 'worsos@torok.com', '06-04-348-6395', 7)

select * from contacts

insert into contacts(contact_id, email, phone, persons_id)
values (8, 'taneli.vennamo@harjunpaa.com', '+358 (17) 7139450', 8)

select * from contacts

insert into contacts(contact_id, email, phone, persons_id)
values (9, 'tania55@koepp.com', '343-268-4068', 9)

select * from contacts

insert into contacts(contact_id, email, phone, persons_id)
values (10, 'sean.edwards@hotmail.com', '(0285) 9731186', 10);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (11, 'noemi.mallet@bernard.fr', '+33 (0)2 47 46 90 49', 11);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (12, 'schaller.ahmet@aol.de', '0935773275', 12);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (13, 'schaller.ahmet@aol.de', '0935773275', 13);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (13, '	siphokazi.white@hotmail.com', '016-970-0522', 13);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (14, 'lucia.esquibel@hotmail.es', '452 0560287', 14);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (15, 'hwintheiser@kerluke.com.hk', '63479205', 15);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (16, 'kadesina@yahoo.com', '08172958917', 16);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (17, 'wright.linda@gmail.com', '(07833) 400085', 17);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (18, 'bruseuddoiloiwe-2490@yopmail.com', '1(237)470-54-40', 18);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (19, 'xeibujiralei-4185@yopmail.com', '4(9555)151-79-98', 19);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (20, 'rune90@advalvas.be', '0735 86 70 57', 20);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (21, 'brandon88@murphy.com', '(02349) 371130', 21);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (22, 'melissa56@hotmail.co.uk', '0641 9629578', 22);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (23, 'jennifer98@hotmail.com', '(01882) 66799', 23);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (24, 'rodger.feil@hotmail.com', '1-429-542-8268', 24);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (25, 'helen18@herman.geek.nz', '049614961', 25);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (26, 'ldubois@gmail.com', '+31800 104240', 26);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (27, 'elliot.murphy@cooper.co.uk', '0987740540', 27);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (28, 'gcampbell@gmail.com', '+44(0)3564187257', 1);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (29, 'bennett.dennis@gmail.co.uk', '05802395397', 2);

select * from contacts;

insert into contacts(contact_id, email, phone, persons_id)
values (30, 'hannah36@yahoo.com', '04917 700238', 3);

select * from contacts;

-- заполяем таблицу "lessons"
insert into lessons(lesson_id, lesson_name, time)
VALUES (1, 'О тестировании и курсе', 5400);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (2, 'SQL part 1', 7200);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (3, 'SQL part 2', 7200);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (4, 'SQL part 3', 7200);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (5, 'SQL part 4', 7200);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (6, 'Работа с репозиторием', 5400);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (7, 'Linux cook book', 10800);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (8, 'Sed, grep, awk', 5400);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (9, 'Передача данных', 7200);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (10, 'http', 5400);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (11, 'Теория тестирования 1', 7200);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (12, 'Теория тестирования 2', 5400);

select * from lessons;

insert into lessons(lesson_id, lesson_name, time)
VALUES (13, 'Как тестировать SAAS', 7200);

select * from lessons;

-- заполняем таблицу "material"

insert into material (material_id, material_name, author, material_type, material_source)
values (1, 'ТестированиеДотКом', 'Роман Савин', 'пособие', 'bit.ly/3iFrJbe')

select * from material

insert into material (material_id, material_name, author, material_type, material_source)
values (2, 'Bash. Карманный справочник системного администратора', 'Арнольд Роббинс', 'карманный справочник', 'https://drive.google.com/file/d/1Yh1HtlN3wBek4-RRiASl7ri6vuO8eZOQ/view')

select * from material

insert into material (material_id, material_name, author, material_type, material_source)
values (3, 'Тестирование черного ящика', 'Борис Бейзер', 'пособие', 'https://drive.google.com/file/d/1Fo1ORGg5LJD1gTkEWvqzEJrIkYQ2kCPn/view')

select * from material

insert into material (material_id, material_name, author, material_type, material_source)
values (4, 'Введение в реляционные базы данных', 'Дейт К. Дж.', 'учебник', 'https://drive.google.com/file/d/1VqXLvTV1xtm-sTjJyFN0ZIGtWW4vlyGe/view')

select * from material

insert into material (material_id, material_name, author, material_type, material_source)
values (5, 'Изучаем SQL', 'Бьюли Алан', 'вводный курс', 'bit.ly/3VL0hYm')

select * from material

insert into material (material_id, material_name, author, material_type, material_source)
values (6, 'Bash-скрипты, руководство в 11 частях', 'likegeeks', 'руководство', 'bit.ly/3VZkhpG')

select * from material

insert into material (material_id, material_name, author, material_type, material_source)
values (7, 'Вселенная тестирования, или Как стать тестировщиком', 'stepik', 'курс', 'https://stepik.org/lesson/788945/step/1?unit=791596')

select * from material

insert into material (material_id, material_name, author, material_type, material_source)
values (8, 'Тестирование программного обеспечения. Базовый курс', 'Святослав Куликов', 'вводный курс', 'http://svyatoslav.biz/software_testing_book/')

select * from material;

-- заполняем таблицу "persons_lessons"
insert into person_lesson (person_id, lesson_id)
VALUES (2, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 4);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 6);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 7);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 8);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 9);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 10);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 11);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 12);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 13);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 14);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 15);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 16);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 16);

select * from person_lesson;

delete from person_lesson;

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (2, 4);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (3, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (3, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (3, 6);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (3, 7);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (3, 8);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (4, 9);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (4, 10);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (4, 11);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (4, 11);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (4, 12);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (4, 13);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (1, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (1, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (1, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (1, 4);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (1, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (5, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (5, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (6, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (6, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (6, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (6, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (7, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (7, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (7, 4);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (8, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (8, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (8, 4);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (8, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (8, 6);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (9, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (9, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (9, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (9, 6);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (10, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (11, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (11, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (12, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (12, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (12, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (12, 4);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (12, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (12, 6);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (13, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (13, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (13, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (13, 4);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (13, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (13, 6);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (14, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (14, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (14, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (14, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (15, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (15, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (16, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (17, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (17, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (17, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (17, 4);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (17, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (17, 6);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (18, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (18, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (19, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (20, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (20, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (20, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (20, 4);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (20, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (20, 6);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (21, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (21, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (22, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (23, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (23, 4);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (24, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (25, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (25, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (25, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (26, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (27, 1);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (27, 2);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (27, 3);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (27, 4);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (27, 5);

select * from person_lesson;

insert into person_lesson (person_id, lesson_id)
VALUES (27, 6);

select * from person_lesson;

--заполняем таблицу "material_lesson"
insert into material_lesson (material_id, lesson_id)
VALUES (1, 1);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (3, 1);

delete
from material_lesson;

select * from material_lesson;

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (1, 1);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (1, 11);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (1, 12);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (1, 13);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (2, 6);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (2, 7);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (2, 8);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (2, 9);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (2, 10);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (3, 11);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (3, 1);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (3, 12);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (3, 13);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (4, 2);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (4, 3);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (4, 4);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (4, 5);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (5, 2);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (5, 3);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (5, 4);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (5, 5);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (6, 8);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (7, 1);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (7, 11);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (7, 12);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (7, 13);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (8, 1);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (8, 11);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (8, 12);

select * from material_lesson;

insert into material_lesson (material_id, lesson_id)
VALUES (8, 13);

select * from material_lesson;

-- заполняем таблицу "schedule"
insert into schedule (schedule_id, date_time, lesson_id)
values (1, '2022-12-11 20:00', 1);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (2, '2022-12-14 20:00', 2);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (3, '2022-12-18 15:00', 3);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (4, '2022-12-21 20:00', 4);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (5, '2022-12-25 15:00', 5);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (6, '2022-12-28 20:00', 6);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (7, '2023-01-01 15:00', 7);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (8, '2023-01-04 15:00', 8);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (9, '2023-01-08 20:00', 9);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (10, '2023-01-11 20:00', 10);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (11, '2023-01-15 15:00', 11);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (12, '2023-01-18 20:00', 12);

select * from schedule;

insert into schedule (schedule_id, date_time, lesson_id)
values (13, '2023-01-22 15:00', 13);

select * from schedule;
-- выполняем задания

--  1. Фамилии, имена, емейл, номер телефона и полный адрес всех студентов
select distinct last_name, first_name, email, phone, country, city, street, house
from persons inner join
    contacts c on persons.person_id = c.persons_id
    inner join
    adress a on a.adress_id = persons.adress_id
where role <> 'teacher'
group by last_name;

-- 2. Среднее время потраченное на уроки каждым_ой студеном_кой (выводим фамилию, имя, емейл, среднее время на уроках)
select last_name, first_name, email, AVG(time)
from persons inner join
    contacts c on persons.person_id = c.persons_id
inner join
    person_lesson pl on persons.person_id = pl.person_id
inner join lessons l on l.lesson_id = pl.lesson_id
where email in (select email
from persons inner join contacts c on persons.person_id = c.persons_id
group by persons.person_id) and role <> 'teacher'
group by last_name, first_name, email;

-- 3. Запрос позволяющий проверить есть ли в группе однофамильцы (не важно студенты или учителя).  Вывести все повторяющиеся фамилии и их количество
select last_name, count(last_name) AS amount
from persons
GROUP BY last_name
HAVING count(last_name) > 1;

-- 4. Запрос позволяющий проверить есть ли в группе среди студентов тезки
select first_name, count(first_name) AS amount
from persons
GROUP BY first_name
HAVING count(first_name) > 1;

-- 5. Вывести фамилию, имя, контактные данные учителя - который потратил больше всего времени на уроках
insert into person_lesson
values (28, 1);

insert into person_lesson
values (28, 2);

insert into contacts (contact_id, persons_id)
values (31, 28);

select * from contacts;

select last_name, first_name, email, phone, MAX(Sum_Time)
from (select last_name, first_name, email, phone, SUM(time) AS Sum_Time
from persons inner join
    contacts c on persons.person_id = c.persons_id
inner join
    person_lesson pl on persons.person_id = pl.person_id
inner join
    lessons l on l.lesson_id = pl.lesson_id
group by last_name, first_name, email, phone)
group by last_name, first_name, email, phone;

select last_name, first_name, email, phone
from (select last_name, first_name, email,
             phone, role, SUM(time) AS Sum_Time
from persons inner join
    contacts c on persons.person_id = c.persons_id
inner join
    person_lesson pl on persons.person_id = pl.person_id
inner join
    lessons l on l.lesson_id = pl.lesson_id
where role <> 'student'
group by last_name, first_name, email, phone, role)
WHERE Sum_Time = (select MAX(Sum_Time)
from (select last_name, first_name, email,
             phone, role, SUM(time) AS Sum_Time
from persons inner join
    contacts c on persons.person_id = c.persons_id
inner join
    person_lesson pl on persons.person_id = pl.person_id
inner join
    lessons l on l.lesson_id = pl.lesson_id
where role <> 'student'
group by last_name, first_name, email, phone, role))
   and email in (select email
from persons inner join contacts c on persons.person_id = c.persons_id
group by persons.person_id);

-- 6. Вывести фамилию, имя, контактные данные студента_ки - который_ая посетил_а больше всего уроков
select last_name, first_name, email, phone
from (select last_name, first_name, email,
             phone, role, COUNT(l.lesson_id) AS lesson_amount
from persons inner join
    contacts c on persons.person_id = c.persons_id
inner join
    person_lesson pl on persons.person_id = pl.person_id
inner join
    lessons l on l.lesson_id = pl.lesson_id
where role <> 'teacher'
group by last_name, first_name, email, phone, role)
WHERE lesson_amount = (select MAX(lesson_amount)
from (select last_name, first_name, email,
             phone, role, COUNT(l.lesson_id) AS lesson_amount
from persons inner join
    contacts c on persons.person_id = c.persons_id
inner join
    person_lesson pl on persons.person_id = pl.person_id
inner join
    lessons l on l.lesson_id = pl.lesson_id
where role <> 'teacher'
group by last_name, first_name, email, phone, role)) and email in (select email
from persons inner join contacts c on persons.person_id = c.persons_id
group by persons.person_id);

-- 7. вывести для каждого_ой студента_ки (фамилия, имя) рекомендуемые материалы всех пройденных конкретным студентом_кой уроков
select last_name, first_name, material_name
from material
    inner join
    material_lesson ml on material.material_id = ml.material_id
inner join lessons l on l.lesson_id = ml.lesson_id
inner join person_lesson pl on l.lesson_id = pl.lesson_id
inner join persons p on pl.person_id = p.person_id
where role <> 'teacher'
order by last_name, first_name;

-- 8. Вывести для каждого_ой студента_ки (фамилия, имя) уникальные рекомендуемые материалы (они не должны повторяться) всех пройденных конкретным студентом_кой уроков
select last_name, first_name, material_name
from material
    inner join
    material_lesson ml on material.material_id = ml.material_id
inner join lessons l on l.lesson_id = ml.lesson_id
inner join person_lesson pl on l.lesson_id = pl.lesson_id
inner join persons p on pl.person_id = p.person_id
where role <> 'teacher'
group by material.material_id, p.person_id
order by last_name, first_name;

-- 9. Вывести страну в которой живут студенты посетившие больше всего уроков
select country
from
    (select country, last_name, first_name, count(lesson_id) AS lesson_amount
from adress inner join
    persons p on adress.adress_id = p.adress_id
inner join person_lesson pl on p.person_id = pl.person_id
where role <> 'teacher'
group by p.person_id)
where lesson_amount in (select max(lesson_amount)
                        from (select country, last_name, first_name, count(lesson_id) AS lesson_amount
from adress inner join
    persons p on adress.adress_id = p.adress_id
inner join person_lesson pl on p.person_id = pl.person_id
where role <> 'teacher'
group by p.person_id));

-- 10. Вывести город в котором живут студенты которые потратили больше всего время на посещения уроков
select city
from
    (select country, city, last_name, first_name, sum(time) AS lesson_time
from adress inner join
    persons p on adress.adress_id = p.adress_id
inner join person_lesson pl on p.person_id = pl.person_id
inner join lessons l on pl.lesson_id = l.lesson_id
where role <> 'teacher'
group by p.person_id)
where lesson_time in (select max(lesson_time)
 from (select country, city, last_name, first_name, sum(time) AS lesson_time
from adress inner join
    persons p on adress.adress_id = p.adress_id
inner join person_lesson pl on p.person_id = pl.person_id
inner join lessons l on pl.lesson_id = l.lesson_id
where role <> 'teacher'
group by p.person_id)));
