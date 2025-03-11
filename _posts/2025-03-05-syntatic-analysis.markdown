---
layout: post
title:  "Reading through Syntatic Analysis (Chomsky, 1957)"
date:   2025-03-05
categories: books linguistics
usemathjax: true

---

# First some context...

Before Chomsky, structural linguistics (influenced by [Bloomfield](https://en.wikipedia.org/wiki/Leonard_Bloomfield)) dominated. This approach focused on classifying linguistic elements based on distribution and behaviour, avoiding mentalistic explanations. The key methods were:
- *Immediate Constituent Analysis*: Breaking sentences into hierarchical parts.
- *Finite-State Models*: Using simple sequential rules to describe language.

However, these approaches struggled to explain complex sentence structures and recursion.

# My approach reading the book

This blog is going to contain the notes I took while reading the book. It is a rather short book with less than 130 pages, but is known for being one of the most influential books of the XX century.
So I believe I'll be doing it justice by going one chapter a time and writing the key topics of the chapter + my ideas from it.

## *The introduction (chapter 1)*

In this chapter, Chomsky introduces what he believes the concept of *syntax* is. He presents the following definition:

```
Syntax is the study of the principles and processes by which senten-
ces are constructed in particular languages. Syntactic investigation
of a given language has as its goal the construction of a grammar
that can be viewed as a device of some sort for producing the
sentences of the language under analysis.
```

Ok... Let's dissect what he meant there. First he defines the concept of **Syntax** as being *the study of the principles and processes by which sentences are contructed in particular languages*. By that, he means that the internal mechanism that we, humans, use to build sentences in our heads is studied by syntax.

Then, he says that **Syntactic investigation** of a given language aims to build (actually understand) a grammar such that can be used to generate valid sentences of the language.

And then, in the couple next sentences, Chomsky, explains that the goal of this *investigations* is to build an unified theory of linguistics, such that we can study the grammar of different languages abstractly. One of the outcomes of this abstract theory is that we will end up crafting a method for selecting a grammar for each language, given that we have the corpus of that language.

## *The Independence Of Grammar (chapter 2)*

Chomsky defines a **language** formally as:

- A set of sentences.
- Each sentence is finite in length.
- Each sentence is made from a finite set of elements (e.g., phonemes, letters).
-Despite the finite number of elements, the number of possible sentences can be infinite.

This definition applies to both *natural* languages (like English) and *formal* languages (like mathematical or programming languages).

### The goal of Linguistics (on grammars)

In the text, he states that the goal of linguistic analysis is to:

- Distinguish **grammatical** sequences (sentences) from **ungrammatical** ones.
- Study the structure of grammatical sentences.
- Develop a grammar that generates all and only the correct sentences.

His point, is that a grammar should be a generative device, so it should be able to produce grammatically correct every valid sentence of a given language (and reject invalid ones).

### How do we test a Grammar's adequacy?

According to Chomsky, a grammar is useful if:

- The sentences it generates match what the native speaker would consider correct
- Reject sequences that are clearly **not** sentences.

In order to model this, Chomsky suggests a simple approach.

1. We start with the clear cases (sentences that are clearly grammatical or not).
2. The grammar should be able to capture those clear cases correctly (all the time).
3. For borderline cases (where it is not clear) we let the grammar follow it's simplest rules.

This method follows the scientific method in some sense, were we identify clear examples, postulate a law that encompasses them, then we generalize and refine to ensure it matches the odd cases and reality.

For any single language, multiple grammars might work. But Chomsky wants a more general theory that applies to all languages. He proposes a stronger test:

- Instead of just creating grammars for individual languages, we should develop a universal method to construct grammars.
- Every language’s grammar should follow the same underlying principles.
- This would provide a general explanation of what makes a sequence grammatical across all languages.
- This leads to the idea of a [universal grammar](https://en.wikipedia.org/wiki/Universal_grammar), which underpins Chomsky’s later work.

## A Language is More Than Just Observed Speech

When a linguist decides to study a given language, and he collects a finite set of utterances (spoken sentences), he needs to know that, obviously, this corpus does **not** define the whole language.

*A language consists of infinitely many **possible** sentences, even those that have never been said before.*

## The Role of Grammar

A grammar does more than just describe the sentences people have spoken. The grammar is a **system** that is able to build all the possible sentences of a given language. Therefore, it allows for new, never-before-heard sentences to be generated and understood.
This is similar to how a speaker of a language, having only heard a finite number of sentences in their life, can still understand and create entirely new ones.

For example, you’ve probably never heard the sentence:
"The blue elephant elegantly tap-danced on the moon last night."
Yet, you immediately recognize it as grammatical because your mind applies rules rather than memorizing sentences.

## Grammar as an Explanation of Linguistic Creativity

- One of the most remarkable aspects of human language is that we can produce and understand an infinite number of new sentences.

- This ability comes from knowing the underlying rules of a language, not just memorizing sentences.

- A good grammar should explain this creativity—it should show how finite experience leads to infinite capability.

This is Chomsky’s major break from [behaviorism](https://en.wikipedia.org/wiki/Behaviorism) (the dominant psychological theory at the time). Behaviorists like Skinner argued that language was just a set of learned responses, but Chomsky counters that humans must have an internalized generative system to explain how we form new sentences.

## Grammatical does not mean Meaningful

Then, Chomsky puts forward 6 sentences:

1. Colorless green ideas sleep furiously.
2. Furiously sleep ideas green colorless.
3. have you a book on modern music?
4. the book seems interesting.
5. read you a book on modern music?
6. the child seems sleeping.

He argues that both senteces (1) and (2) are non-sensical, but (1) is clearly grammatical. Therefore, we cannot postulate that *"What is grammatical is what is semantically sensible."*

Similarly, there is no semantic reason to prefer (3) to (5) or (4) to (6), but only (3) and (4) are grammatical sentences of english.

## The Problem with Statistical Models of Language

Before Chomsky, some linguists (especially behaviorists) tried to describe language using statistical models. The idea was:

- The more frequently a sequence of words appears, the more “grammatical” it is.
- Rare or unseen word sequences might be considered “ungrammatical.”

### Refutation

Consider two sequences, sequence A and B. A is a grammatically correct but non-sensical sentence (that was never used before), B is a completely ungrammatical list of words.
By using a statiscal method, both sequences would be considered **equally** *"ungrammatical"* as the other, which is obviously wrong.

### How Humans Process These Sentences Differently

- A native speaker will read the grammatical sentence with normal intonation.
- A native speaker will read the ungrammatical sentence as a sequence of disconnected words.
- The grammatical sentence is easier to memorize and recall.
- The ungrammatical sentence feels unnatural, even if every word in it is common.

This suggests that our brains use rules, not probabilities, to determine grammaticality.

## The Whale vs. Of Example

To refute it even further, Chomsky gives another example of why statiscal methods are wrong.

- Consider the phrase "I saw a fragile ---".
- If you complete it with "whale" -> it sounds fine
- If you complete it with "of" -> it sounds wrong

Even if both words have equal **zero** probability of appearing in this exact context, we instantly recognize that one is grammatical and the other is not.
This cannot be explained by statistical frequency alone.

## The Fallacy of “Possible Sentences”

Some linguists defined grammatical sentences as those that “can occur” in language.

- But “possible” does not mean “probable.”
- Even if a sentence is extremely unlikely, it can still be grammatical.

Chomsky argues that ranking sentences by statistical approximation to English will not separate grammatical from ungrammatical ones.
They appear randomly scattered in the list.

## The Conclusion: Grammar is Autonomous from Meaning

- Grammar is not just about meaning—a sentence can be meaningless but still grammatical.
- Grammar is not based on probability—even extremely rare sentences can be grammatical.
- Statistical models may help with some aspects of language (e.g., predicting the next word in a sentence) but cannot define what is grammatical and what is not.

This leads to Chomsky’s famous conclusion: Grammar is an **independent system**, and understanding it requires formal rules, not just statistical analysis

## *An Elementary Linguistic Theory (chapter 3)*

In this chapter, Chomsky begins by asking the question:

```
Assuming the set of grammatical sentences of English to be
given, we now ask what sort of device can produce this set (equi-
valently, what sort of theory gives an adequate account of the
structure of this set of utterances).
```

Then, he explains that if we think of a sentence as being a finite sequence of phonemes, and that if we want to define the **language as the set of possible phonemes** the **grammar** would be so huge that render it pratically useless.

Given that, Chomsky introduces what he calls *levels of representations* which, for us, computer scientists is, nothing more than, levels of **abstraction**. So that instead of reasoning about **phonemes** linguists should study morphemes and states separately the morphemic structure of sentences and the phonemic structure of morphemes

### Finite languages

Chomsky goes through, one requirement of grammars is that it has to be finite. Since otherwise, a grammar could be defined as just the list of all morpheme sequences (it would be absurd since there are infinite morpheme sequences).

From that, he goes on to provide the definition of state machines. He says the following:

```
Suppose that we have a machine that can
be in any one of a finite number of different internal states, and
suppose that this machine switches from one state to another by
producing a certain symbol (let us say, an English word). One of
these states is an initial state; another is a final state. Suppose that
the machine begins in the initial state, runs through a sequence of
states (producing a word with each transition), and ends in the final
state.
```

Using this definition, he says that this machine is capable of generating sentences (english). And he says that each language that can be generated from a state machine like so is called a *finite state language*.
And the machine itself is called a *finite state **grammar***

Usually finite state grammars are represented through state diagrams, here is the example for a grammar that generates the sentences: *"the man comes"* and *"the men come"*.

![The man comes (state machine)]({{site.url}}/assets/syntatic-analysis/the-man-comes.png)

If we want to extend this grammar to handle an infinite number of senteces, such as: *the old man comes* or *the old old men come*, etc. We could use the following grammar

![The old man comes (state machine)]({{site.url}}/assets/syntatic-analysis/the-old-man-comes.png)

To build sentences in the languages defined by those machines, we start at the left, and procceed to the right, each "word" we generate leads us to a different internal state of the machine.
The machines that produce theese languages are called [*"finite state Markov processes*](https://stats.libretexts.org/Bookshelves/Probability_Theory/Probability_Mathematical_Statistics_and_Stochastic_Processes_(Siegrist)/16%3A_Markov_Processes/16.01%3A_Introduction_to_Markov_Processes#:~:text=A%20Markov%20process%20is%20a,important%20of%20all%20random%20processes.)

Here is some simple code that implements the given state machine:

{% highlight python %}
initial = 0
final   = {4}
states  = {0, 1, 2, 3, 4}
state   = initial
table   = {
    (0, 'the'): 1,
    (1, 'old'): 1,
    (1, 'man'): 2,
    (1, 'men'): 3,
    (2, 'comes'): 4,
    (3, 'come'): 4,
}

acc = ''
while state not in final:
    word = input('Enter a word: ')
    acc += ' ' + word

    if (state, word) in table:
        state = table[(state, word)]
    else:
        print('Invalid word')
        break

if state in final:
    print('Accepted:', acc)    
else:
    print('Rejected:', acc)
{% endhighlight %}

### English is **not** a finite state language.

- English has dependencies between words that cannot be captured by a simple state transition system.
- For example, in "If the man comes, the party will start", the word comes depends on if, even though other words separate them.
- Finite-state grammars cannot handle long-distance dependencies like this, since it can't know the path it took to get to a certain point since it doesn't have **'memory'**

### Where does finite-state grammars fail

Chomsky provides 3 examples of languages we cannot use finite state grammars to recognize. They are:

1. ab, aabb, aaabbb, ..., and in general, al sentences consisting of n occurrences of a followed by n occurrences of b and only these;

2. aa, bb, abba, baab, aaaa, bbbb, aabbaa, abbbba, ..., and
in general, al sentences consisting of a string X followed
by the 'mirror image' of X (i.e., X in reverse), and only these;

3. aa, bb, abab, baba, aaaa, bbbb, aabaab, abbabb, ..., and in
general, all sentences consisting of a string X of a's and b's
followed by the identical string X, and only these.

Since they all would require some sort of memory to know how did the state machine ended up where it did.

### English Sentences and Non-Regular Structure

Chomsky then shows that English has similar patterns that require more than a finite-state grammar.

1. Conditionals & Logical Dependencies
- Example: "If S₁, then S₂"
- "If" requires "then" later in the sentence.
- The dependency remains even if S₁ is arbitrarily complex.
- A finite-state grammar cannot enforce such dependencies because it only looks at the last word.

2. Subject-Verb Agreement Across Embeddings
- Example: "The man who said that the boy is leaving arrives today."
- The verb "arrives" depends on "man," not on "boy."
- The finite-state grammar gets confused by the nested structure.
- This is similar to (aⁿbⁿ), where dependencies span across intervening material.

3. Recursive Nesting of Sentences

- Example: "Either S₁ or S₂, but if S₃ then S₄."
- The structure resembles (mirror image patterns) where dependencies exist across arbitrary-length insertions.
- Finite-state grammars cannot track these nested structures.

Thus, Chomsky concludes:
```
"English is not a finite-state language."
Instead, English requires a context-free grammar
(or more powerful models like transformational grammar).
```

### The Pumping Lemma

If a language L is **regular**, then there exists a constant p (called the **pumping length**) such that any string $$w ∈ L$$ with $$ \|w\|≥p $$ can be split into three parts:

$$ w = xyz $$

Such that:

1. **(Pumping condition)** $$ xy^nz ∈ L $$ for all $$ n ≥ 0$$ (i.e we can "pump" $$y$$ any number of times, including 0 times, and still get a valid string in the language.)
2. **(Non-empty pump)** $$ \|y\| > 0 $$ (the middle part must contain at least one character).
3. **(Bounded first two parts)** $$ \|xy\| ≤ p $$ (ensures that the "pumped" section is within the first p characters).

### Proving that $$ L = \{a^nb^n | n ≥ 0\} $$ is not Regular

We want to show that the language:

$$ L = \{a^nb^n | n ≥ 0\} $$

is **not** regular.

#### Assume L is regular
By the pumping lemma, there exists a pumping length 

#### Choose a string w in L
Let’s take:

$$ w = a^pb^p = aaaaa...aabbbbb...bb$$

where there are p a’s followed by p b’s.

#### Split w into xyz
Since $$ \|xy\| ≤ p $$, and $$ y ≠ ε $$, the segment xy must be made up of only a's (because we haven't reached the b's yet).
So we assume:

$$ x = a^m $$

$$ y = a^k $$

$$ z = a^{p-m-k}b^p $$

where $$ y = a^k $$ (at least one a)

#### Pump y (increase or remove copies of a)

- If we pump up (e.g. repeat y twice), we get:
$$ xyyz = a^{m+k+k}a^{p-m-k}b^p = a^{p+k}b^p $$

Which has more a's than b's - this is **not** in L.

#### Contradiction

Since $$ xy^nz ∉ L $$ for some n, the pumping lemma does not hold.
Thus, L is not regular.

### Back to the chapter

After this detour, Chomsky argues the following:
1. Arbitrary Limits Do Not Reflect Language Reality
- One could artificially impose a limit on recursive sentence structures (e.g., allowing only sentences up to a fixed length), making English a finite-state language.
- But such an arbitrary restriction does not align with how language actually works—people can form sentences of arbitrary length in principle.

2. Finite-State Grammars Cannot Capture Recursive Processes
- English sentences can be formed by recursive rules, such as embedding clauses inside other clauses:
    The man who said [that the woman who saw [the child who ran]] is arriving today.
- A finite-state grammar, which generates sentences by moving from one word to the next in a step-by-step process, cannot track such long-range dependencies.

3. Two Failures of Finite-State Grammars
- Overgeneration: If an FSG is designed to generate all English sentences, it will also produce many ungrammatical sentences.
- Undergeneration: If an FSG is made more restrictive, it will fail to generate many valid English sentences.

4. Finite-State Grammars Are the Simplest Model, but Still Inadequate
- They are the minimal theory worth considering since they can, in a limited way, generate infinite sentences.
- However, their limitations force the search for a more powerful grammar, such as phrase-structure grammars or transformational grammars.

5. A More Abstract Model of Grammar is Needed
- Language cannot be fully described as a simple left-to-right sequence of words.
- Instead, a grammar must account for hierarchical structures (e.g., nested phrases, dependencies across clauses).
- This requires a more general theory of linguistic levels, rather than just finite sequences of symbols.

## *Phrase Structure (chapter 4)*

### A stronger model for linguistic analysis

In this chapter, Chomsky begins by defining the concept of **constituent analysis** a.k.a *parsing*.
Then, he proceeds to says that a **grammar** defined by this sort is much more powerful than the finite state model described above.

### A cool example

- (**I**) Sentence -> NP + VP
- (**II**) NP -> T + N
- (**III**) VP -> Verb + NP
- (**IV**) T -> the
- (**V**) N -> man, ball, etc.
- (**VI**) Verb -> hit, took, etc.

Chomsky says, that we think of those rules as *replacement* rules. So we should mentally think of X -> Y "rewrite X as Y".
To build sentences from this grammar, we perform a process called **derivation**. There are an infinite number of possible derivations from a given grammaer, here is one example:

![Derivation example)]({{site.url}}/assets/syntatic-analysis/derivation.png)

We can also represent a derivation using a tree-like diagram, but we end up losing some information on the order the rules were applied when we represent it like that.

![Derivation example)]({{site.url}}/assets/syntatic-analysis/tree-like-derivation.png)

Here is some simple python code to recognize said grammar:
{% highlight python %}
class Parser:
    def __init__(self, toks):
        self.toks = toks
        self.i = 0

    def is_grammatical(self):
        l = self.parseSentence()
        return self.i == len(self.toks) and l

    def parseSentence(self):
        return self.parseNP() and self.parseVP()
    
    def parseNP(self):
        return self.parseT() and self.parseN()
    
    def parseT(self):
        el = self.toks[self.i]
        self.i += 1
        return el == "the"
    
    def parseN(self):
        el = self.toks[self.i]
        self.i += 1
        return el in ['man', 'ball']
    
    def parseVP(self):
        return self.parseVerb() and self.parseNP()
    
    def parseVerb(self):
        el = self.toks[self.i]
        self.i += 1
        return el in ['hit', 'took']

{% endhighlight %}

```
A sequence of words of this sentence is a constituent
of type Z if we can trace this sequence back to a single point of
origin in (15), and this point of origin is labelled Z. 
```

Therefore, *"hit the ball"* can be traced back to **VP** in the tree diagram above, so, "hit the ball" is a **VP** in the derived sentence.
"man hit" cannot be traced back to any single point, hence, it is not a constituent at all.

He also provides the definition of **equivalent** derivations, they are: *two derivations that reduce to the same diagram of the form (15, tree diagram)*

He then defines the concept of ambiguous grammar, that is, when a grammar permits us to construct nonequivalent derivations for a given sequence, we call that **constructional homonymity** and if the grammar is correct, the sentence is said to be **ambiguous**.

### A generalization of the grammar

He then says, that we must be able to generalize the example grammar that we have been dealing with in this chapter, that **T** must be rewritten as *a* if the noun is singular, but not if it is plural.
So, in general, if we want to limit the rewriting of X as Y to the context X - W, we can state the following rule:

$$Z + X + W → Z + Y + W$$

So, in the case of singular and plural verbs, we can have an additional rule:

$$NP_{sing} + Verb → NP_{sing} + hits$$

With this power, we can describe more generarly the form of grammar associetad with "constituent analysis". So, each such grammar is defined by a finite set Σ of inital strings and a finite set F of 'instruction formulas'(rules) of the form $$X→Y$$ (X does not need to be a single symbol, but only a single symbol of X can be rewritten in forming Y). In the example grammar we were talking about, $$Σ=\{Sentence\}$$ and F was:

$$ F = \{ Sentence → NP + VP, NP → T + N, VP → Verb + NP, T → the, N → man, ball, etc, Verb → hit, took, etc. \} $$

He then proceeds to, elegantly, define **derivations**:
```
Given the grammar [Σ, F], we define a derivation as a
finite sequence of strings, beginning with an initial string of Σ, and
with each string in the sequence being derived from the preceding
string by application of one of the instruction formulas of F.
```

If a string is the last line of a terminated derivation, we say that it is a **terminal string**. I.e. If there are no more rules to expand, the result is a **terminal string**.

A set of strings is called a **terminal language**if it is the set of **terminal strings** for some grammar [Σ, F].

### On finite state machine x Systems of the form [Σ, F]

In chapter 3, we looked into **finite state languages** i.e. languages that were generated by finite state *Markov* processes. And in the current chapter we have been loking into **terminal languages**.

Those two types of languages are related in the following way:

```
Every finite state language is a terminal language, but
there are terminal languages which are not finite state languages.
```

Making, therefore, the current model more powerfull than *Markov* processes.
Here is a language discussed previously (in chapter 3) as a *terminal language*.

$$ Σ: Z $$

$$ F: Z → ab $$

$$ F: Z → aZb $$

Using this language, we can model 'ab', 'aabb', 'aaabbb'...

### Phrase Structure vs. Morphophonemics

In this part, Chomsky discusses the hierarchy of lower level linguistiscs and higher level through a disussion of **Morphophonemics** and **Phrase Structure**. In this discussion he shows that one cannot process the **morphophonemic** rules before the Syntatic Rules expansion.

## *Limitations Of Phrease Structure Description (chapter 5)*

TODO