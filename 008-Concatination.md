# Concatination

## What is concatination?

Some operators can be used when dealing with strings, such as multiplcation and addition. This works very differently with strings than it does when dealing with integers or floating numbers. Adding two strings together squashes each string to the other one in a literal fashion. 

Take a look at this example:

<pre><code>"I would like to" + " visit Disney World in Florida."</code></pre>

Notice here we have two strings, with an addition operator in the middle of them. The resulting output of this, if we were to put a print statement in front of the strings, would look like this:

<pre><code>"I would like to visit Disney World in Florida."</code></pre>

Pay close attention to the original statements, I placed a space before the word visit, at the beginning of the second string. If I hadn't, then resulting output would look like this:

<pre><code>"I would like to" + "visit Disney World in Florida."
>>> "I would like tovisit Disney World in Florida."</code></pre>

Adding strings together is literal, and takes into consideration spaces, or a lack of spaces. 

## Some more examples of concatination

<pre><code>"I" + "am" + "happy" + "today"
>>> "Iamhappytoday"

"I" + " am" + " happy" + " today"
>>> "I am happy today"

"abcdefghijklmnopqrst" + "uvwxyz"
>>> "abcdefghijklmnopqrstuvwxyz"

"two" + " three"
>>> "two three"

"2" + "7" + "8" + "4"
>>> "2784"</code></pre>

## Answer this question yourself

Have a look at this input, and take a guess at what you think the output would be

<pre><code>print ("5" + "5" + 5)</code></pre>

🕐🕐🕐🕐🕐🕐🕐🕐🕐🕐🕐🕐🕐🕐🕐🕐🕐🕐🕐

Were you able to work it out? 

The out put would have actually been an error, and looked something like this:

<pre><code>TypeError: can only concatenate str (not "int") to str</code></pre>

This is because you cannot concatinate a string to an integer or floating point number, only strings can be concatinated to one another. 
