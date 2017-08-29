## schema

Suppose an enterprise keep track of their professional training in a database with the following tables

#### Employee

employee_id | name
----------- | ----
1 | Jane Snow
2 | John Smith
3 | Julie Style
    


#### Curriculum
course_id | subject | group_id
--------- | ------- | --------
A1 | Python language | A
A2 | Data structure | A
A3 | Algorithms | A
B1 | Agile prime | B
B2 | Version Control | B
B3 | Unit testing | B



#### Training classes
class_id | course_id | startdate
-------- | --------- | ---------
c1 | A1 | 2017-03-01
c2 | B1 | 2017-03-02
c3 | A3 | 2017-03-21
 
 
    
#### Class participation    
employee_id | class_id | score | status
----------- | --------- | ----- | ------
1 | c1 | 3 | DONE
2 | c1 | | ENROLLED
3 | c2 |  | CANCELLED


## Requirements

1. find employees who took at least 2 courses this year

1. find employees who took at least 2 courses each in the last 3 years

1. let certified employee be one who finishes at least 2 courses in group A and one in group B, list all who are certified
