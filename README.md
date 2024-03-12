create table YF_22(

    id int primary key,
    name Varchar(50),
    age int,
    my_date date
    
);

desc YF_22;

insert into YF_22  values (1, 'ahmed', 25, to_date('1999-01-01', 'yyyy-mm-dd'));
insert into YF_22  values (2, 'ali', 63, to_date('1989-04-30', 'yyyy-mm-dd'));
insert into YF_22  values (3, 'turki', 22, to_date('1333-03-30', 'yyyy-mm-dd'));
insert into YF_22  values(4, 'smah', 11, to_date('1555-04-22', 'yyyy-mm-dd'));
insert into YF_22  values(5, 'yahya', 57, to_date('2444-02-13', 'yyyy-mm-dd'));
insert into YF_22  values (6, 'omar', 55, to_date('3333-10-03', 'yyyy-mm-dd'));
insert into YF_22  values (7, 'badr', 44, to_date('1989-04-1', 'yyyy-mm-dd'));
insert into YF_22  values (8, 'nasser', 22, to_date('1989-04-2', 'yyyy-mm-dd'));
insert into YF_22  values (9, 'mossad', 12, to_date('1989-04-3', 'yyyy-mm-dd'));
insert into YF_22  values (10, 'zeyade', 21, to_date('1989-04-4', 'yyyy-mm-dd'));
insert into YF_22  values (11, 'zeed', 12, to_date('1989-04-5', 'yyyy-mm-dd'));
insert into YF_22  values (12, 'sara', 42, to_date('1989-04-6', 'yyyy-mm-dd'));
insert into YF_22  values (13, 'ga3fr', 2, to_date('1989-04-7', 'yyyy-mm-dd'));
insert into YF_22  values (14, 'slman', 12, to_date('1989-04-8', 'yyyy-mm-dd'));
insert into YF_22  values (15, 'faisl', 45, to_date('1989-04-9', 'yyyy-mm-dd'));
insert into YF_22  values (16, 'hassn', 6, to_date('1989-04-10', 'yyyy-mm-dd'));
insert into YF_22  values (17, 'hssam', 5, to_date('1989-04-11', 'yyyy-mm-dd'));
insert into YF_22  values (18, 'hssan', 54, to_date('1989-04-12', 'yyyy-mm-dd'));
insert into YF_22  values (19, 'bander', 5, to_date('1989-04-13', 'yyyy-mm-dd'));
insert into YF_22  values (20, 'hox', 54, to_date('1989-04-14', 'yyyy-mm-dd'));
insert into YF_22  values (21, 'mike', 55, to_date('1989-04-15', 'yyyy-mm-dd'));
insert into YF_22  values (22, 'alloy', 5, to_date('1989-04-16', 'yyyy-mm-dd'));
insert into YF_22  values (23, 'clash', 9, to_date('1989-04-17', 'yyyy-mm-dd'));
insert into YF_22  values (24, 'rakan', 5, to_date('1989-04-18', 'yyyy-mm-dd'));
insert into YF_22  values (25, 'gojo', 54, to_date('1989-04-19', 'yyyy-mm-dd'));
insert into YF_22  values (26, 'sataru', 45, to_date('1989-04-20', 'yyyy-mm-dd'));
insert into YF_22  values (27, 'skuna', 75, to_date('1989-04-21', 'yyyy-mm-dd'));
insert into YF_22  values (28, 'nanami', 67, to_date('1989-04-22', 'yyyy-mm-dd'));
insert into YF_22  values (29, 'fddf', 66, to_date('1989-04-23', 'yyyy-mm-dd'));
insert into YF_22  values (30, 'jack', 56, to_date('1989-04-24', 'yyyy-mm-dd'));
insert into YF_22  values (30, 'kaido', 65, to_date('1989-04-24', 'yyyy-mm-dd'));
insert into YF_22  values (31, 'zoro', 86, to_date('1989-04-25', 'yyyy-mm-dd'));
insert into YF_22  values (32, 'nwafe', 28, to_date('1989-04-26', 'yyyy-mm-dd'));
insert into YF_22  values (33, 'naif', 13, to_date('1989-04-27', 'yyyy-mm-dd'));
insert into YF_22  values (34, 'fdsf', 33, to_date('1989-04-28', 'yyyy-mm-dd'));
insert into YF_22  values (35, 'erer', 53, to_date('1989-04-29', 'yyyy-mm-dd'));
insert into YF_22  values (36, 'errrs', 43, to_date('1989-04-30', 'yyyy-mm-dd'));
insert into YF_22  values (37, 'how', 73, to_date('1322-03-22', 'yyyy-mm-dd'));
insert into YF_22  values (38, 'lee', 83, to_date('1999-01-1', 'yyyy-mm-dd'));
insert into YF_22  values (39, 'ddd', 93, to_date('1999-01-2', 'yyyy-mm-dd'));
insert into YF_22  values (40, 'fff', 3, to_date('1999-01-3', 'yyyy-mm-dd'));
insert into YF_22  values (41, 'ggg', 22, to_date('1999-01-4', 'yyyy-mm-dd'));
insert into YF_22  values (42, 'hhh', 21, to_date('1999-01-5', 'yyyy-mm-dd'));
insert into YF_22  values (43, 'jjj', 23, to_date('1999-01-6', 'yyyy-mm-dd'));
insert into YF_22  values (44, 'kkk', 24, to_date('1999-01-7', 'yyyy-mm-dd'));
insert into YF_22  values (45, 'lll', 25, to_date('1999-01-8', 'yyyy-mm-dd'));
insert into YF_22  values (46, 'iii', 26, to_date('1999-01-9', 'yyyy-mm-dd'));
insert into YF_22  values (47, 'uuu', 27, to_date('1999-01-10', 'yyyy-mm-dd'));
insert into YF_22  values (48, 'yyy', 28, to_date('1999-01-11', 'yyyy-mm-dd'));
insert into YF_22  values (49, 'ttt', 18, to_date('1999-01-12', 'yyyy-mm-dd'));
insert into YF_22  values (50, 'rrr', 18, to_date('1999-01-13', 'yyyy-mm-dd'));
    delete from YF_22 where id=50;

select * from YF_22;

