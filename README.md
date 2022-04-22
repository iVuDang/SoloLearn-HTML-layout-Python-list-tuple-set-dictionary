# Purpose:
* Outline my plan and software stack roadmap. 
* Supplement knowledge with SoloLearn introduction tutorials.  


# Vu's Software Stack Roadmap :earth_asia: 

| | **FRONT END**  | >> | >> | **BACK END** | >> | >> | **UI/UX DESIGN** |
| ------------- | ------------- | ------------- | ------------- | ------------- |------------- | ------------- | ------------- |
| **Base Language** | Excel/VBA | HTML/CSS | JavaScript | Python | SQL | Java | Adobe Photoshop|
| **Frameworks / Libraries** | | Bootstrap | React.js | Django | | | Adobe Premiere Pro | 
| **Cross-platform** | | | Express.js / Node.js | | MongoDB | | Adobe After Effects |


# Vu's Human Language Stack Roadmap :speech_balloon:
| Primero  | Segunda | Tercero | Cuarto | 
| ------------- | ------------- | ------------- | ------------- | 
| English | Vietnamese | Spanish | Portuguese? French? |


## Proof of completion (SoloLearn certificates)

| # | Course  | Certificate |
| ------------- | ------------- | ------------- |
| 1 | HTML  | https://www.sololearn.com/Certificate/1014-18375186/jpg  |
| 2 | CSS  | https://www.sololearn.com/Certificate/1023-18375186/jpg  |
| 3 | Responsive Web Design  | https://www.sololearn.com/Certificate/1162-18375186/jpg  |
| 4 | JavaScript  | https://www.sololearn.com/certificates/course/en/18375186/1024/landscape/png  |
| 5 | React+Redux  | https://www.sololearn.com/Certificate/1097-18375186/jpg/  |
| 6 | SQL  | https://www.sololearn.com/certificates/course/en/18375186/1060/landscape/png  |
| 7 | Python for Beginners  | https://www.sololearn.com/certificates/course/en/18375186/1157/landscape/png |
| 8 | Python Core  | https://www.sololearn.com/certificates/course/en/18375186/1073/landscape/png  |
| 9 | Python Intermediate  |   https://www.sololearn.com/certificates/course/en/18375186/1158/landscape/png	|
| 10 | Python Data Structures  | https://www.sololearn.com/certificates/course/en/18375186/1159/landscape/png  |
| 11 | Python for Data Science  |  https://www.sololearn.com/certificates/course/en/18375186/1161/landscape/png  |
| 12 | Java  |   |


## Favorite Key Takeaways :star:
- - - -
### HTML 
The HTML layout:

```
<!DOCTYPE html>
<html>

<head>
  <meta charset='UTF-8'>
  <meta name='description' content='iVuDang'> 
  <meta name='keywords' content='iVuDang, Vu Dang'>
  <metaname='author' content='Vu Dang'>
  <meta name='viewport' content='width=device-width, initial-scale=1'>
  <title>iVuDang</title> 
</head> 

<body>

  <main> 
  
    <article>
      <section> 
      </section> 
    </article>
    
  </main> 
 
  <footer> </footer> 
  
</body>

</html>
```

- - - -
### CSS
All HTML elements can be considered as boxes. The CSS box model represents the design and layout of the site. It consists of margins, borders, paddings, and the actual content. 

Hence, it is a useful practice to initially set a colored border to visualize our box elements when in the early phases of structuring our web content e.g.:

```
  border: 2px solid red;
```


- - - -
### JavaScript
JavaScript variables are containers for data values. Objects are variables too, but they can contain many values. 

Think of an object as a list of values that are written as name:value pairs, with the names and the values separated by colons. 
```
let person = {
	name: 'John', 
	age: 31,
	favColor: 'green',
	height: 183
};
```

Can access age of our person in two ways: 

object.name <br>
object['name']

```
let x = person.age;
let y = person['age']
```

Output: 31



- - - -
### SQL
The syntax for the WHERE clause:

```
SELECT column_list 
FROM table_name 
WHERE condition 
```

The LIKE keyword is useful when specifying a search condition within your WHERE clause.

Additional Supplement from: https://www.w3schools.com/sql/sql_like.asp

There are two wildcards often used in conjunction with the LIKE operator:
* The percent sign (%) represents zero, one, or multiple characters
* The underscore sign (_) represents one, single character

```
WHERE CustomerName LIKE 'a%' 	Finds any values that start with "a"
WHERE CustomerName LIKE '%a' 	Finds any values that end with "a"
WHERE CustomerName LIKE '%or%' 	Finds any values that have "or" in any position
WHERE CustomerName LIKE '_r%' 	Finds any values that have "r" in the second position
WHERE CustomerName LIKE 'a_%' 	Finds any values that start with "a" and are at least 2 characters in length
WHERE CustomerName LIKE 'a__%' 	Finds any values that start with "a" and are at least 3 characters in length
WHERE ContactName LIKE 'a%o' 	Finds any values that start with "a" and ends with "o"
```

- - - -
### Python
1. Python supports the following data structures: lists, dictionaries, tuples, sets. 

| Data Structure | Ordered  | Mutable | Constructor | Example |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| List | Yes | Yes | [ ] | [1, 2, 3] 
| Tuple | Yes | No | ( ) | (1, 2, 3)
| Set | No | Yes | { } | {1, 2, 3}
| Dictionary | No | Yes | { } | {'One': 1, 'Two': 2, 'Three': 3} 


**When to use a dictionary:**
- When you need a logical association between a key:value pair.
- When you need fast lookup for your data, based on a custom key. 
- When your data is being constantly modified. Remember, dictionaries are mutable. 

**When to use the other types:**
- Use lists if you have a collection of data that does not need random access. Try to choose lists when you need a simple, iterable collection that is modified frequently. 
- Use a set if you need uniqueness for the elements. 
- Use tuples when your data cannot change. 
Many times, a tuple is used in combination with a dictionary, for example, a tuple might represent a key, because it's immutable. 




