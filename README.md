# Structures-c

In C programming, a struct (or structure) is a collection of variables (can be of different types) under a single name.There are cases where we need to store multiple attributes of an entity. It is not necessary that an entity has all the information of one type only. It can have different attributes of different data types. For example, an entity Student may have its name (string), roll number (int), marks (float).

Define Structures:
Before you can create structure variables, you need to define its data type. To define a structure, the struct keyword is used.

Syntax of struct

struct structureName {
  dataType member1;
  dataType member2;
  ...
};

For example,

struct student 
{
  char name[50];
  
  int rollno;
  
  float marks;
  
};


Here, struct is the keyword; student is the name of the structure;name, roll no, and marks are the members of the structure.

