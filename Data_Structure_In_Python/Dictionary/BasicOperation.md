____________________________

Day 12:Lecture 2
Content: Basic operation on dictionary
Author:Ravishankar Chavare
Date:12-06-2019
LinkedIn:https://www.linkedin.com/in/ravishankar-chavare-84474a102
_______________________________

*Add new key value element in dictionary*

- we can add key and value in dictionary using key.

Syntax:
dictname[key]=value

Example:
mydict={"name":"ravi","age":20}
mydict["bdate"]="26/01/1993"

print(mydict)
#Result:{"name":"ravi","age":20,"bdate":"26/01/1993"}



*Updating value in dictionary*
Syntax:
dictname[existed key]="new value"


Example:
mydict={"name":"ravi","age":20}
#update name with jhon

mydict["name"]="jhon"

print(mydict)
#Result : {"name":"jhon","age":20}


*Removing key value pair from dictionary*

- use built in method pop() to remove element from dictionary

Syntax:
dictname.pop("keyname")


Example:
mydict={"name":"ravi","age":20}
#remove age
mydict.pop("age")

print(mydict)
#Result:{"name":"ravi"}


*Clear all element of dictionary*

- clear() in built method is used to empty the dictionary.

Syntax:
dictname.clear()


Example:

mydict={"name":"ravi","age":20}
#clear all element 
mydict.clear()

print(mydict)
#Result:{}

*Deleting dictionary*
- *del* keyword used to delete complete dictionary.

Syntax:
del dictionary_name

Example
mydict={"name":"ravi","age":20}
del mydict