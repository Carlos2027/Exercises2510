## <hl><U><CENTER><FONT SIZE="14"><FONT color="black"> <FONT face="aharoni">  HOMEWORK I </FONT> </FONT></FONT></CENTER> </hl></U><hr size="1" width="75%" style="color: red">

<i><b><FONT SIZE="6"> <center>-----Excercise 1, <strong>A Good First Program----- </center></strong> </FONT> </i></b>

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•Print </FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4">It is used to write text on screen</FONT></FONT>


```python
print("Hello World!")
print("I love programming")
print("arriba las chivas")
```

    Hello World!
    I love programming
    arriba las chivas
    

<i><b><FONT SIZE="6"> <center>-----Excercise 2, <strong>Comments and Pound Characters----- </center></strong> </FONT> </i></b>

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•# </FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4">It is used to write comments on the code whitout affect it</FONT></FONT>


```python

print("I could have code like this.") #print is used to write text on screen
print("This will run.")
```

    I could have code like this.
    This will run.
    

<i><b><FONT SIZE="6"> <center>-----Excercise 3, <strong>Numbers and Math----- </center></strong> </FONT> </i></b>

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•Mathematical operations </FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4">They are used to perform the operations we already know about math</FONT></FONT>




```python
print("I will now count my toys:")
print("cars", 25 + 30 / 6)
print("xbox", 100 - 25 * 3 % 4)
print("Now I will count the money:")
print(3 + 2 + 1 - 5 + 4 % 2 - 1 / 4 + 6)
```

    I will now count my toys:
    cars 30.0
    xbox 97
    Now I will count the money:
    6.75
    

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•False/True </FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4">It is used to know if what is written is correct or not</FONT></FONT>


```python
print("Is it true that 3 + 2 < 5 - 7?")
print("What is 3 + 2?", 3 + 2)
print("What is 5 - 7?", 5 - 7)
print("Oh, that's why it's False.")
print("How about some more.")
print("Is it greater?", 45 > -7)
print("Is it greater or equal?", 34 >= 45)
print("Is it less or equal?", 34 <= -56)
```

    Is it true that 3 + 2 < 5 - 7?
    What is 3 + 2? 5
    What is 5 - 7? -2
    Oh, that's why it's False.
    How about some more.
    Is it greater? True
    Is it greater or equal? False
    Is it less or equal? False
    

<i><b><FONT SIZE="6"> <center>-----Excercise 4, <strong>Variables and Names----- </center></strong> </FONT> </i></b>

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•Variables </FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4">The variables are used to declare a function, a mathematical operation or a value, to save space when programming</FONT></FONT>


```python
toys = 100

workers = 30
customers = 130
toyss=customers-toys
print("There are", toys, "toys in the store.")
print("There are only", workers, "workers available.")
print("We have", customers, "to attented")
print("We need to buy",toyss,"toys more")
```

    There are 100 toys in the store.
    There are only 30 workers available.
    We have 130 to attented
    We need to buy 30 toys more
    

<i><b><FONT SIZE="6"> <center>-----Excercise 5, <strong>More Variables and Printing ----- </center></strong> </FONT> </i></b>


```python
a=19
b='San luis'
c='dog'
d= 'Alvarez'
e=13
f=14
```

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•Variables inside a string </FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4">You embed variables inside a string by using a special {} sequence and then put the variable you want inside the {} characters. You also must start the string with the letter f for ”format”,as in f"Hello{somevar}".</FONT></FONT>



```python
print(f"Let's talk about {d}.")
print(f"He's from {b} ")
print(f"He has a {c} ")
print("his dog is so cute")
print(f"his dog weighs {f} kg")
print(f"he has lived {e} years whit him")
total = a + e + f
print(f"If I add {a}, {e}, and {f} I get {total}.")
```

    Let's talk about Alvarez.
    He's from San luis 
    He has a dog 
    his dog is so cute
    his dog weighs 14 kg
    he has lived 13 years whit him
    If I add 19, 13, and 14 I get 46.
    

<i><b><FONT SIZE="6"> <center>-----Excercise 6, <strong>More Variables and Printing----- </center></strong> </FONT> </i></b>


<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•f-string</FONT> </FONT></FONT></hl>


<FONT face="arial"><FONT SIZE="4"> it is used when we want to save into a string varibe in another varible</FONT></FONT>


```python
r = 50
f= f"there are {r} shoes in my room" 

t = "parties"
e="running"
y = f"some are for {e} and another for {t}."

print(f)
print(y)
print(f"I said: {r}")
print(f"I also said: '{y}'")

g = True



```

    there are 50 shoes in my room
    some are for running and another for parties.
    I said: 50
    I also said: 'some are for running and another for parties.'
    

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•.format()</FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4">It is used when we want want to apply a format to an already created string</FONT></FONT>


```python
fut = "Isn't that joke so funny?! {}"
print(fut.format(g))
w = "This is the left side of..."
que = "a string with a right side."
print(w + que)
```

    Isn't that joke so funny?! True
    This is the left side of...a string with a right side.
    

<i><b><FONT SIZE="6"> <center>-----Excercise 7, <strong>More Printing ----- </center></strong> </FONT> </i></b>

<FONT face="arial"> <FONT SIZE="4">In this exercise, we only declared variables to finally get together and form a simple sentence</FONT></FONT>


```python
print("Carlos has a new bag.")
print("Its red like a {}.".format('tomato'))
print("." * 10) 

abc1 = "h"
abc2 = "e"
abc3 = "l"
abc4 = "l"
abc5 = "o"

abc7 = "w"
abc8 = "o"
abc9 = "r"
abc10 = "l"
abc11 = "d"

print(abc1 + abc2 + abc3 + abc4 + abc5, end=' ')
print(abc7 + abc8 + abc9 + abc10 + abc11 )
```

    Carlos has a new bag.
    Its red like a tomato.
    ..........
    hello world
    

<i><b><FONT SIZE="6"> <center>-----Excercise 8, <strong>Printing, Printing ----- </center></strong> </FONT> </i></b>

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•formatter</FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4">Formatters work by putting in one or more replacement fields and placeholders defined by a pair of curly braces {} into a string and calling the .format ()</FONT></FONT>


```python
formatter = "{} {} {} {}"

print(formatter.format(1, 2, 3, 4))
print(formatter.format("apple", "orange", "cucumber", "banana"))
print(formatter.format(True, False, False, True))
print(formatter.format(formatter, formatter, formatter, formatter))
print(formatter.format(
   "A poem by Patrick star:",
   "The roses are blue, ",
   "the violets are red, ",
   "and I have to go to the bathroom"
))
```

    1 2 3 4
    apple orange cucumber banana
    True False False True
    {} {} {} {} {} {} {} {} {} {} {} {} {} {} {} {}
    A poem by Patrick star: The roses are blue,  the violets are red,  and I have to go to the bathroom
    

<i><b><FONT SIZE="6"><center>----- Excercise 9, <strong>Printing, Printing, Printing ----- </center></strong> </FONT> </i></b>

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•\n</FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4"> The \n is used like the "enter" in our keyboards, is for give us a jump in the text</FONT></FONT>


```python
firstletters = "A B C D E F G H I J"
mylastgrades = "\nAU \nAU\nSA\nDE\nAU\nDE\nAU\nSA"
print("Here are the first letters: ", firstletters)
print("Here are my last grae: ", mylastgrades)
print("")
```

    Here are the first letters:  A B C D E F G H I J
    Here are my last grae:  
    AU 
    AU
    SA
    DE
    AU
    DE
    AU
    SA
    
    

<i><b><FONT SIZE="6"> <center>-----Excercise 10, <strong>What Was That?----- </center></strong> </FONT> </i></b>

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•\t</FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4"> it is used to simulate indentations</FONT></FONT>


```python
asx = "\t hello."
bsx = "I'm \n erick."
```

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black">•\ (backslash)</FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4"> It is used to create spaces in a text with a slash, very similar to the comma</FONT></FONT>


```python
csx = "i \\ want\\ eat."
```

<hl><FONT SIZE="6"><FONT color="black"> <FONT face="arial black"> •\t*</FONT> </FONT></FONT></hl>


<FONT face="arial"> <FONT SIZE="4"> It is used to create the points of a list</FONT></FONT>


```python

ssx = """
 I did a food list :
 \t* Pizza
 \t* tacos
 \t* tamales\n
 \t* Gorditas
 """

print(asx)
print(bsx)
print(csx)
print(ssx)
```

    	 hello.
    I'm 
     erick.
    i \ want\ eat.
    
     I did a food list :
     	* Pizza
     	* tacos
     	* tamales
    
     	* Gorditas
     
    
