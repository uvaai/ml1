# Chinese Room

This week we’ll revisit the philosophical question from the written assignment
of the first week; “Can machines think?”, and try to relate it to the new
machine learning concepts you’ve learned in the past few weeks. To start, you
should read Searle’s article describing the Chinese Room thought experiment,
which is a classic text on the question.

[J.R. Searle - Minds, brains, and programs](chinese_room.pdf)

## Understanding Sentiment

Once you’ve read the article, consider what you think Searle would say about
the Naive Bayes sentiment analysis program you built in the programming
notebook this week.

I think we can state with certainty that Searle would argue that Naive Bayes
isn’t just naive, but actually has zero understanding. It is a weak AI, applied
to solve a specific problem, which in the end just consists of manipulating
formal symbols without any semantics to ascribe meaning to these symbols. You
could interpret these formal symbols to be the strings which represent the
words and the integers which count their relative occurrence, or all the way
down to the bit level, where the compiled machine code runs and simply
transforms sequences of bits into other sequences of bits in a deterministic
fashion. Either way, the algorithm (or the computer as a whole) does not know
or understand what these formal symbols mean in the context of sentiment
analysis, or in general, at all.

Next, consider to what degree you yourself are in fact a functional sentiment
analysis machine, which *is* capable of actual understanding. 

Here I think, again without much doubt, we can state that you *are*, given the
fact that you’re reading this sentence. You can probably predict if the
sentiment of any sentence is positive or negative with much higher accuracy
than the algorithm. But here we already start to run into trouble: When do we
say your prediction is correct or incorrect? Are we just assuming, because you
speak the English language, your answer is correct by definition? Do we compare
your answer to a panel of expert linguists? If so, how many linguists is enough
to give a conclusive answer for a very ambiguous or neutral sentence?

The trick, of course, is that we’re not using the Naive Bayes algorithm to
solve the general problem of sentiment analysis, but instead are simply trying
to model what is considered positive or negative *in this specific data set.*
In many ways, this is a much easier problem, as we don’t have to bother all the
English-speaking linguists in the world for their definitions in order to know
if we’ve even solved it. We can just assume the labels provided in the data set
to be the correct *ground truth* and focus on how to model those. However, if I
asked *you* to solve *this* version of the problem, you might say that reading
1.6 million tweets and building a cohesive mental model of how they are labeled
is beyond your capabilities.

Perhaps, with extraordinary patience and dedication, such a feat would be
possible, but the time and energy required would certainly far exceed the
afternoon you’ve spent programming Naive Bayes. So, we’ve got a program which
can process 1.6 million tweets in under a minute, but doesn’t have any sense of
their semantics, and a programmer with a good a understanding of the meaning of
words, but who is never going to have the time to physically process such a
volume of tweets one by one (I assume). Therefore, neither of these two
machines will ever be capable of extracting and understanding the entire
distribution of positive and negative labels within the data set.

Argue whether or not you think the conjuction of a computer running the Naive
Bayes algorithm and you, the programmer who wrote it and reports the results,
together *does* produce a system capable of understanding the entire
distribution of positive and negative labels within the data set, given that
neither system can produce understanding just by itself.