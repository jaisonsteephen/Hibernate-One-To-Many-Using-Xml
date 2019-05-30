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



Hibernate: select question0_.id as id1_1_, question0_.qname as qname2_1_ from q501 question0_

Question Name: What is Java?

Hibernate: select answers0_.qid as qid4_1_0_, answers0_.id as id1_0_0_, answers0_.type as type5_0_, answers0_.id as id1_0_1_, answers0_.answername as answerna2_0_1_, answers0_.postedBy as postedBy3_0_1_ from ans501 answers0_ where answers0_.qid=?

Java is a programming language:Ravi

Java is a platform:Sudhir

Question Name: What is Servlet?

Hibernate: select answers0_.qid as qid4_1_0_, answers0_.id as id1_0_0_, answers0_.type as type5_0_, answers0_.id as id1_0_1_, answers0_.answername as answerna2_0_1_, answers0_.postedBy as postedBy3_0_1_ from ans501 answers0_ where answers0_.qid=?

Servlet is an Interface:Jai

Servlet is an API:Arun
