Welcome to the course _Philosophical Logic_! It is given during the summer semester 2024 at _LMU Munich_ as part of the _Master in Logic and Philosophy of Science_. 


# Motivation 

Often, what is understood by 'logic' is classical logic (either classical propositional logic or classical first-order logic). Its typical features are, for example, that a sentence `p` is either true or false and that `not not p` is the same as `p`. In many situations, though, simply assuming classical logic is not appropriate. Such situations arise, as we'll see, in philosophy and neighboring disciplines (like mathematics, computer science,
and linguistics). For example, when reasoning with: vague concepts, incomplete or inconsistent data, conditionals (i.e., 'if, then' sentences), and what it means to be true. The course will be about exploring different logics to model these (and other) phenomena. A focus of the course is on using both algebraic and state-based (or 'possible world') semantics to mathematically describe the meaning of these different logics.

# General information

We have three sessions per week during the semester:

1. The _lecture_ given by me, [Levin Hornischer](https://www.mcmp.philosophie.uni-muenchen.de/people/faculty/hornischer_levin/index.html), on Thursdays from 10:15 to 11:45 in room 021 (Ludwigstr. 31).
Here the main content of the course is introduced. Below you find a schedule of when we cover which topic. (This is `10111 Philosophical Logic` on LSF.)

2. The _exercise class_ given by [Marta Esteves](https://www.mcmp.philosophie.uni-muenchen.de/people/doct_fellows/esteves_marta/index.html), on Mondays from 14:15 to 15:45 in room 028 (Ludwigstr. 31). Here the solutions to the homework exercises are discussed. (This is `10105 Additional Tutorial "Philosophical Logic"` on LSF.)
  
3. The _tutorial_ given by me, [Levin Hornischer](https://www.mcmp.philosophie.uni-muenchen.de/people/faculty/hornischer_levin/index.html), on Thursdays from 9:15 to 10:00 in room 021 (Ludwigstr. 31). Here we cover background material, but we can go into more detail of a particular topic of the lecture (based on your demand). (This is `10132 Exercise course "Philosophical Logic"` on LSF.) 



# Lecture Notes

You find the latest edition of the lecture notes in this file: [`phillog.pdf`](phillog.pdf). They are updated as the course progresses. 


# Formalities

All the organizational details for the course are described in this file: [`formalities.pdf`](formalities.pdf).


# Schedule

The schedule below describes in which week we will cover which material in, respectively, the lecture, the tutorial, and the exercise class. The 'Week Date' is the Monday of the week; this is when exercise class takes place, while the lecture and tutorial will take place on the Thursday of that respective week. 

We had a vote on which topics to cover in the last four weeks, and you opted for an overview of the four last topics in the syllabus below.

Week | Week Date | Chapter | Lecture | Tutorial | Exercise Class
---  | ---                 | ---     | ---     | ---      | --- 
 1   | 15 Apr    | 1   | until and including sec. 2.2 | _cancelled_ (since before first lecture)  | _cancelled_ (before first lecture) 
 2   | 22 Apr    | 2   | sec. 2.3 & 2.4 | Intro to partial orders (see appendix) | classical logic recap
 3   | 29 Apr    | 2   | sec. 2.5 | Recap Boolean algebras and algebraic semantics | Exercises on Boolean algebras (ex. 2.12, 2.13, maybe 2.14) 
 4   | 6 May     | 2   | _cancelled_ (Ascension Day) | _cancelled_ (Ascension Day) | Exercises from sec. 2.6
 5   | 13 May    | 3   | sec. 3.1 and most of 3.2 | More on Boolean algebras and Stone duality | Wrap up exercises from sec. 2.6
 6   | 20 May    | 3   | finished 3.2 until and including 3.3.2 | Exercises from ch. 3 | _cancelled_ (Whit Monday)
 7   | 27 May    | -   | _cancelled_ (Corpus Christi) | _cancelled_ (Corpus Christi) | _cancelled_ (substituted on June 4)
 8   | 3 Jun     | 3-4 | Finished 3.3 and covered 4.1 | Exercise 3.7-8 | More exercises from ch. 3
 9   | 10 Jun    | 4   | Start 4.2 until and including Gödel's theorem | Philosophical background of intuitionistic logic | Exercises on fuzzy logic
10   | 17 Jun    | 4   | Heyting algebra semantics | Double negation in intuitionistic logic | Exercises on intuitionistic logic
11   | 24 Jun    | 5   | Hyperintensionality | More on duality between Heyting algebras and Kripke models | Exercises on Heyting algebras (and, optionally, details of proof of Gödel's theorem)
12   | 1 Jul     | 6   | Counterfactuals | TBA | TBA
13   | 8 Jul     | 8   | Relevance logic | TBA | TBA
14   | 15 Jul    | 9   | Paradoxes | TBA | TBA


# Essay topic


Below are some possible essay topics. I'll extend this list as the course progresses.

* _State-based vs algebraic semantics_. We motivated these two approaches to semantics with their respective slogans 'States first, propositions later' and 'Propsositions first, states later'. Do you think one of the two is correct (e.g., states are conceptually prior to propositions)? Or do you think that states and propositions are just two sides of the same coin: as duality theory would say?
  
* _Higher-order vagueness_. What exactly is higher-order vagueness and can the logics that we've discussed adequately capture it? (Cf. exercise 3.e.) 

* _Fuzzy logic and the definitely operator_. Can fuzzy logic provide an interpretation of the definitely operator by interpreting it as the truth function that maps x to x^2? (Cf. exercise 4.b.)

* _Kripke semantics for intuitionistic logic_. We have discussed in the lecture whether the semantics for intuitionistic logic using Kripke models adequately captured the intuitive semantics suggested by the BHK interpretation. What is your verdict on this? 

* _Dummett's argument_. Based on the 'meaning is use' idea, Dummett and others argued that intuitionistic logic is the—more or less—one true logic (see the last paragraph of section 4.2.4). What do you make of this?

* _State-based semantics and subject matter_. Say you want to develop a state-based semantics that respects subject matter (i.e., equivalent sentences have the same atomic sentences occurring in them). So you define models consisting of states and say what the truth-value V(s,"phi") of a formula "phi" is at a state s in the model. In truthmaker semantics, for example, one uses the truthmaker states and four truth-values (made true and not false, made false and not true, neither made true nor false, both made true and false). Now, Hornischer (2020, thm 3) shows that you will fail in your goal once you make the following initially plausible assumptions:
   1) Your truth-values can be ordered by closeness to the truth and V(s,"phi and psi") is less or equal to V(s,"phi"), which in turn is less or equal to V(s,"phi or psi").
   2) We have what might be called weak absorpion: V(s,"phi and (phi or psi) = V(s,"phi or (phi and psi)").

Truthmaker semantics gives up on the first assumption. Discuss: Wouldn't it be more plausible to rather give up on the second assumption? (See Hornischer (2020, p. 791f.) for some first ideas.) How could such a semantics look like?

 
Just to be sure, these suggested topics are meant as first ideas. It is part of the task of writing an essay to turn an interesting aspect of the suggested topic into a precise research question and collect the relevant literature on it. Please take a look at the grading criteria mentioned in the file [`formalities.pdf`](formalities.pdf) to get a clear idea of what a good essay is expected to look like.
