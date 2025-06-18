Welcome to the course _Philosophical Logic_! It is given during the summer semester 2025 at _LMU Munich_ as part of the _Master in Logic and Philosophy of Science_. (Past editions: summer 2023, summer 2024 and previously at the University of Amsterdam.)


# Motivation 

Often, what is understood by 'logic' is classical logic (either classical propositional logic or classical first-order logic). Its typical features are, for example, that a sentence `p` is either true or false and that `not not p` is the same as `p`. In many situations, though, simply assuming classical logic is not appropriate. Such situations arise, as we'll see, in philosophy and neighboring disciplines (like mathematics, computer science,
and linguistics). For example, when reasoning with: vague concepts, incomplete or inconsistent data, conditionals (i.e., 'if, then' sentences), and what it means to be true. The course will be about exploring different logics to model these (and other) phenomena. A focus of the course is on using both algebraic and state-based (or 'possible world') semantics to mathematically describe the meaning of these different logics.

# General information

The instructor of the seminar is me, [Levin Hornischer](https://www.mcmp.philosophie.uni-muenchen.de/people/faculty/hornischer_levin/index.html). During the semester, we meet on Thursdays from 14:00 to 16:00 in room 028 (Ludwigstr. 31). Below you find a schedule of when we cover which topic.


# Lecture Notes

You find the latest edition of the lecture notes in this file: [`phillog.pdf`](phillog.pdf). They are updated as the course progresses. 


# Formalities

All the organizational details for the course are described in this file: [`formalities.pdf`](formalities.pdf).


# Schedule

The schedule below describes in which week we will cover which material. The sections refer to the lecture notes. The exercises are recommended to do for the next session.


Week | Week Date | Chapter | Lecture | Exercises
---  | ---       | ---     | ---     | ---      
 1   | 24 Apr    | 1-2 | until and including sec. 2.2 | Recap sec. 2.2 and do exercises therein
 2   | 1 May     | -   | _cancelled_ (Labor Day) | 
 3   | 8 May     | 2   | until first parts of sec. 2.3.2 | in-text exercises  
 4   | 15 May    | 2   | finishing sec. 2.3.2 (Boolean algebras) | in-text exercises
 5   | 22 May    | 2   | sec. 2.4 (includes sec 2.5 in the older version of the notes) | exercises 2.a-e (as many as you want) 
 6   | 29 May    | -   | _cancelled_ (Ascension Day)
 7   | 5 Jun     | 3   | until an including sec. 3.2.1 | the in-text exercises and 3.b.  
 8   | 12 Jun    | 3   | Finishing ch. 3 | exercises 3.c, d, f.
 9   | 19 Jun    | -   | _cancelled_ (Corpus Christi)
10   | 26 Jun    | TBA | 
11   | 3 Jul     | TBA | 
12   | 10 Jul    | TBA | 
13   | 17 Jul    | TBA | 
14   | 24 Jul    | TBA | 


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
