# QA Automation Homework  Unit Testing the Collection C# Class
Unit testing &amp; Nunit Basics

The first Homework project of the lecture Unit testing & Nunit from the course QA Automation on Software University   :06.05.2022 


You are given a C# class Collection<T>, which implements a generic collection, holding an indexed sequence of elements
 
  ![image](https://user-images.githubusercontent.com/101709956/167027841-e35fd95b-6242-4eb0-aa03-b2f569f791e1.png)
  
Write unit tests for the class Collection<T>. Ensure that the code coverage is high and that all interesting cases are covered: test all public methods, test the auto growing of the underlying array, test with valid and invalid ranges, and try to cover all other special cases.
Hints :
•	Test all public methods.
•	Think about all different scenarios, which can happen, e. g. insert at the start, insert at the end, insert at the middle, insert with auto-grow, insert at invalid   
  position, insert into empty collection, etc.
•	Ensure you test each method with valid and invalid data.
•	Implement a performance test with 1 million items, with timeout.
