# Hibernate-One-To-Many-Using-Xml

Hibernate: select max(id) from q501

Hibernate: select max(id) from ans501

Hibernate: insert into q501 (qname, id) values (?, ?)

Hibernate: insert into ans501 (answername, postedBy, id) values (?, ?, ?)

Hibernate: insert into ans501 (answername, postedBy, id) values (?, ?, ?)

Hibernate: insert into q501 (qname, id) values (?, ?)

Hibernate: insert into ans501 (answername, postedBy, id) values (?, ?, ?)

Hibernate: insert into ans501 (answername, postedBy, id) values (?, ?, ?)

Hibernate: update ans501 set qid=?, type=? where id=?

Hibernate: update ans501 set qid=?, type=? where id=?

Hibernate: update ans501 set qid=?, type=? where id=?

Hibernate: update ans501 set qid=?, type=? where id=?

SQL> select * from q501;

	ID QNAME
	 1 What is Java?
	 2 What is Servlet?

SQL> select *  from ans501;

	ID	  QID POSTEDB ANSWERNAME			TYPE
	 1	    1 Ravi    Java is a programming language	0
	 2	    1 Sudhir  Java is a platform		1
	 3	    2 Jai     Servlet is an Interface		0
	 4	    2 Arun    Servlet is an API 		1

