
# Cearting Table in SQL 


I've started learning SQL since 3 months ago and during this time creating a portfolio was a biggest concern. At the end, after a lot of searching and watching Youtube videos, I came up with the idea of creating table. 

In the following picture, I created a table with different data types: Int= integer which is for numeric values , Nvarchar just accepts string and 50 means you can write up to 50 character, then I defined a primary key for the first column and a default value for "Date" Column which will be automatically filled by " (getdate())" function.


<img width="1345" alt="B9CBBA5C-FFB3-43CD-ACE4-A0A3BD64742E" src="https://user-images.githubusercontent.com/127425854/227874492-5173d776-abb0-4d95-98df-248a24e86581.png">



## Foreign Key

When we want to linke a table to another, we can do it through a Primary key and a Foreign key. It acutally gives rise to having a consistent data in our database. 



<img width="1093" alt="BD47EC3D-2053-4116-855B-CF40B36FACCA" src="https://user-images.githubusercontent.com/127425854/227880592-d27eb485-99df-4682-9521-23e40aab2ff7.png">




## Constraints 
For constraints, we can define some conditions that should be met while entering data. Here, we applied a condition for EndD (END DATE) column which should be greater than StartD or it can be empty. 

<img width="580" alt="FDBD0B8B-D398-4ADE-9B5F-F13909C84261" src="https://user-images.githubusercontent.com/127425854/227881046-d4867e7a-f486-40e9-b9a4-f85a6a8c5eac.png">



## Index 

Indexes are used to retrieve data from the database more quickly than otherwise. ACS: Sorts the result set in ascending order.

<img width="710" alt="6516528F-406F-4D17-88F2-81D620640AAC" src="https://user-images.githubusercontent.com/127425854/227887890-9e68095f-cd41-4050-8b9c-222427bdba14.png">

