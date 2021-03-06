# What is code?

"
code

noun \ˈkōd\

: a set of laws or regulations

: a set of ideas or rules about how to behave

: a set of letters, numbers, symbols, etc., that is used to secretly send messages to someone"

[Merriam-Websiter Dictionary](http://www.merriam-webster.com/dictionary/code) 


"Coding, or programming, is a way of writing instructions for computers that bridges the gap between how humans like to express themselves and how computers actually work." 

T.S. ["What is Code?"](http://www.economist.com/blogs/economist-explains/2015/09/economist-explains-3) The Economist. September 8, 2015. 


"A sequence of symbols (using typical keyboard characters, saved to a file of some kind) that someone typed in, or copied, or pasted from elsewhere. That doesn’t mean the other kinds of coding aren’t valid or won’t help you achieve your goals. Coding is a broad human activity, like sport, or writing. When software developers think of coding, most of them are thinking about lines of code in files. They’re handed a problem, think about the problem, write code that will solve the problem, and then expect the computer to turn word into deed." 

Ford, Paul. ["What is Code?"](http://www.webopedia.com/TERM/C/code.html) Bloomberg. June 11, 2015. 


# Code is Plural
 
Code is not a single term. It is a "big tent" as we like to say about Digital Humanities. For our purposes, we are going to look at two categories - markup languages and scripting languages. Keep in mind that exactly how they are categorized is a point of debate.

# Markup Languages

Code for marking, structuring and laying out text.  Think HTML, LaTeX, XML and even docx.

For example, DH Quarterly requires articles in Extensible Markup Language (XML).  The language has a set of rules for encoding documents and allows machines to read the text. It is pretty flexible and allows people to develop new tags for different tasks.  

DHQ:
[XML for Digital Humanities Quarterly](https://github.com/statsmaths/dhq-paper/blob/master/xml/PhotogrammarArticle_Submitted.xml)


During Elizabeth Dillion's talk on the Early Carribean Digital Archive, she mentioned that they are developing TEI for each document. What did she mean by TEI?

TEI is the Text Encoding Initiative. 

"The TEI Guidelines for Electronic Text Encoding and Interchange define and document a markup language for representing the structural, renditional, and conceptual features of texts. They focus (though not exclusively) on the encoding of documents in the humanities and social sciences, and in particular on the representation of primary source materials for research and analysis. These guidelines are expressed as a modular, extensible XML schema, accompanied by detailed documentation, and are published under an open-source license. The Guidelines are maintained and developed by the TEI Consortium, through its Technical Council, with the support and participation of the TEI community." [TEI: Guidelines. Text Encoding Initiative. ](https://github.com/statsmaths/dhq-paper/blob/master/xml/PhotogrammarArticle_Submitted.xml)


So, let's look at an example:
[Dedication: To Edward John Trelawny. ](http://wwp.northeastern.edu/outreach/seminars/_current/handouts/tei_samples/swinburne/items_within_volumes/acs0000001-03-i098.xml)

[Dedication: To Edward John Trelawny. ](http://webapp1.dlib.indiana.edu/swinburne/view#docId=swinburne/acs0000001-03-i098.xml;query=Dedication:%20To%20John%20Trelawny;brand=swinburne)

[TEI Rules. ](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/index.html)

TEI is just one way to markup.  For example, the document converter program Pandocs can move between a large number of markup languages. Here is a diagram:
![](http://s3.amazonaws.com/bundlr-app-production/content_images/images/large/53734e328a9d53000200000e/diagram.png?1400065587 "Markup Languages. Courtesy: Pandocs")



# Scripting Languages

It is a language that gets called inside of another program. The focus is on having an existing program act in a way you'd like through scripts.  You tell a program what to do. 

Ex. R

Let's look at R:
```{r}
 print ("hello world")


 for(x in 1:10) {
   print (x)
 }
```
# Compiled Languages
It is a language that gets converted directly into machine code. You tell a computer what to do. 

Ex. C

Let's look at an example.

```{c}
#include <stdio.h>

 int main() {

 int i;
 for (i=0; i < 10; i++)
 {
  printf("%d\n", i);
 }
 
 return 0;
}
```

And now let's compile this program. 
```{sh}
gcc 110.c
```

Now we see it creates a.out, which is our program. Now let's look at our program.

```{sh}
./a.out
```

And for those who want to see what happens when you compile C, [ check this out!](http://gcc.godbolt.org/)

Now, [it's your turn to play with some code!](http://tryr.codeschool.com/levels/1/challenges/1)
