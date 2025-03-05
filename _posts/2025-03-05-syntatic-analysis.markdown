---
layout: post
title:  "Reading through Syntatic Analysis (Chomsky, 1957)"
date:   2025-03-05
categories: books linguistics
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
