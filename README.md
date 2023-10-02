# Trying an iterated learning experiment in the classroom

I'm teaching a modeling class. I wanted to introduce the concept of an inductive bias in an interesting and memorable way.

This activity is inspired by a bunch of papers on iterated learning experiments. This one is a simple categorization experiment. The basic idea is to have one person categorize the objects based on limited information, and then transmit their categorization to the next person, with some loss of information along the way. This repeats for several people. If you make several of these transmission chains in the classroom, they will probably all converge on one or two solutions to the problem, regardless of the initial starting conditions.

The HTML doc generates a (noisy) 5 x 5 space of squares that can be categorized. [Link to live version here](). I printed out several sets of these and cut them into individual pieces of paper. 

From there, create initial categories by dividing the cards into two piles. This could be done randomly, or you could pick something less intuitive, like very dark and very light in one category, medium shades in the other. I suspect that it doesn't matter too much.

Before giving the piles to a student to begin, randomly pick some small number of examples from each category. These items the student will get as labeled examples of the two category types. For the rest, shuffle them together. Have the student sort the piles into two categories. The details of this process probably don't matter much, but I like doing this one at a time so they can't compare the whole distribution of items. I bet it works either way.

Once a student is done sorting, repeat the process. Have them randomly take some small number of items from each category as the labeled examples, shuffle the rest, and pass to the next person in the chain. After a small number of cycles, have the last person share their fully categorized set. It will probably follow a single dimension rule, big vs. small or light vs. dark. The tendency towards the simple rule is an example of an inductive bias.
