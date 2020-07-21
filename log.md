# 100 Days Of Code - Log

### Day 1: July 12th, 2020
##### 

Worked on reviewing my Express knowledge. Learned that we can utilize the route method on the app object. It helps reduce redundancies on creating separate routes for each HTTP request verb



### Day 2: July 13th - 14th, 2020
##### 

Brushing up on my vanilla javascript skills by implementing a simple mortgage payment calculator.

**Thoughts**: It could definitely use a facelift with some CSS. Perhaps tomorrow I can spruce it up.

**Link(s) to work**: github.com/louischrisorona/mortgage_calculator


### Day 3: July 14th - 15th, 2020

**Today's Progress**: Went back into my mortgage calculator to add an amortization schedule. Still need a little tweaking on the algorithm.

**Thoughts** Need to tweak the styling for the amortization schedule table. Going back to use vanilla js is so much harder than I remember.

### Day 4: July 16th, 2020
**Today's Progress**: I wanted to practice some algorithms on codewars. I picked a random one and it's removing duplicates from an array, but leaving the first occurence starting from the back of the array.

**Thoughts**  This first one is just like removing duplicates from an array using the Set Object. So, I approached it by reversing the array and creating a set from the reverse and then manipulating the set back into an array and reversing it. If I did not reverse the array before creating the set, then I would end up with the wrong answer.
Codewars link:https://www.codewars.com/users/tfp33184/completed_solutions   This kata was only a 7th Kyu, which is extremely easy. I'll do another.

Found a great kata that seems challenging: Unique digits sequence
link to kata: https://www.codewars.com/kata/599688d0e2800dda4e0001b0/train/javascript
Essentially, there's a unique series that is built by finding the next lowest unique number that does not include the digits of the previous number found.
We have to return the index of the given number within this unique series. Since this deals with unique numbers, then I might consider starting with a Set.
I'm not familiar with all of the Set.prototype methods, but I'll figure this out.

I could not figure out this algorithm for producing the series. I need to do some more research.

### Day 5: July 18th - 19th, 2020
**Today's Progress**: **Note: I'm a little behind on my 100daysofcode and have not quit! **

I just learned that I was creating a table wrong using vanilla JS! No wonder my rows were elements, but the <td> was text... Table DOM elements have methods available. Make sure to double check everything available to you.
#DOMObjects #VanillaJS


DOM Object methods like 'createElement', but there are actually Table Object methods like 'insertRow()' or 'insertCell()'

Yup you can create rows by selecting your Table then using its built-in methods and properties.

This is so much easier than the way I attempted.

Frameworks really hold our hands on some things.

### Day 6: July 20th - 21st, 2020
**Today's Progress**: I was able to re-create my amortize schedule in a proper table using the correct DOM methods rather than simple element creation in JavaScript. Utilizing these DOM methods in JavaScript allows for styling unlike before where the data was rendered as simple text.

**bug found**: Amortization schedule array is ending before it calculates a balance at $0. Need to rework the logic to correct this. Need another pair of eyes.
