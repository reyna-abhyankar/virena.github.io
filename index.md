## Welcome to My GitHub Page

Written entirely in Markdown, this page was created for a software engineering project course at the University I attend! My name is Viren Abhyankar, and I am a computer science student at UC San Diego.

The following is a list of things I have to add to this site:

- [ ] Pictures
- [ ] Links
- [ ] Headings
- [ ] Styling text
- [ ] Quoting text
- [ ] Quoting code
- [ ] Section links
- [ ] Relative links
- [ ] Lists
- [x] Task lists
- [ ] Tables
- [ ] Embedding Images
- [ ] Embedding HTML

Looks like I already have a task list! However, it isn't exactly rendering the way I want it to. I'll probably have to debug that at a later time. 

Let's start with **Headings**

### Headings

I'm actually going to use headings throughout this page, so there's no need to devote an entire section to just talk about headings. There is a pretty important head*line* today, however. The Democrats have [flipped the US Senate](https://www.businessinsider.com/georgia-senate-runoff-election-results-democrats-regain-control-2020-10), and President-elect Joe Biden's victory has been certified by Congress!

Raphael Warnock had this to say after he defeated Republican candidate Kelly Loeffler:

> The other day, because this is America, the 82-year-old hands that used to pick somebody else's cotton went to the polls and picked her youngest son to be a United States senator.

Pretty powerful stuff. Here's a picture of his mom!

![](warnock.jpeg)

Looks like we already got pictures, links, and styling/quoting text done! Time to move on to some code. 

### Code

I love the FizzBuzz problem because it's so simple, but people think too fast. The objective is as follows:
For all numbers from 1 to n, 
   print "Fizz" if the number is divisble by 3
   print "Buzz" if the number is divisible by 5
   print "FizzBuzz" if the number is divisible by both 3 and 5
   print the number if none of the above conditions apply 
Here's the solution:
```
def fizzbuzz(n):
    for i in range(1,n+1):
        if i % 3 == 0:
            print("Fizz")
        if i % 5 == 0:
            print("Buzz")
        if (i % 3 != 0) and (i % 5 != 0):
            print(i)
```

I also love Breadth First Search, but I will save that for another day.

### README

Yes, there is more to this site than meets the eye. Checkout the [README](README.md) of this project to find out what my favorite programming language is (if you already couldn't tell).

### Lists

Now, I do need an actual list because the task list doesn't really look that clean. So here is a list of my favorite 49ers players:
- Fred Warner: Niners seem to always have some amazing linebackers
- Brandon Aiyuk: Massive wingspan and real deep threat
- Jimmy Garoppolo: Won 5 straight games at the end of 2017 and injected real hope into the organization (not to mention, took us to the Super Bowl???). He'll be playing out of his mind next year
- Jason Verett: Man has battled every week this year and kept this defense alive
- George Kittle: he's on every football fan's list. No questions asked, best tight end in the game.

### Tables

I love tables. Not as much as I love graphs, but I love tables. I also love football, so here's a table of Super Bowl opponents and eventual winners from since I started watching (this is all from memory, by the way):

| Season | AFC Champion | NFC Champion | Winner |
| ----------- | ----------- | ------- | ------ |
| 2019      | Kansas City Chiefs       | San Francisco 49ers | KC |
| 2018   | New England Patriots        | Los Angeles Rams | NE |
| 2017 | New England Patriots | Philadelphia Eagles | PHI |
| 2016 | New England Patriots | Atlanta Falcons | NE |
| 2015 | Denver Broncos | Carolina Panthers | DEN |
| 2014 | New England Patriots | Seattle Seahawks | NE |
| 2013 | Denver Broncos | Seattle Seahawks | SEA |
| 2012 | Baltimore Ravens | San Francisco 49ers | BAL |
| 2011 | New England Patriots | New York Giants | NYG |
| 2010 | Pittsburgh Steelers | Green Bay Packers | GB |
| 2009 | Indianapolis Colts | New Orleans Saints | NO |
| 2008 | Pittsburgh Steelers | Arizona Cardinals | PIT |
| 2007 | New England Patriots | New York Giants | NYG |
| 2006 | Indianapolis Colts | Chicago Bears | IND |

### Embedding HTML

This is actually pretty easy. I'm gonna make all the text in the next paragraph blue.

<div style="color:blue">
I'm a politics enthusiast with an interest in using technology for social good. I started a mentorship program 9 months ago for students from my high school, and I've turned it into a nonprofit with the help of a few of my friends. 
</div>

That's because Markdown supports HTML without any special formatting needs. 