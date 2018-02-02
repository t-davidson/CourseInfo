# STSCI 4780 - Bayesian data analysis: principles and practice

**Lectures:**  Tuesdays & Thursdays, 1:25pm - 2:40pm, in Upson 206  
**Labs:**  Fridays, 2:55pm - 4:10pm, in Upson 222

**Instructor:**  
Tom Loredo  
Cornell Center for Astrophysics and Planetary Science, and Field of Statistics  
620 Space Sciences Building  
loredo@astro.cornell.edu  
Office hours:  Wednesdays, 3pm - 4pm, and by appointment

**Grader:**  
Kyrylo Chernyshov: <kc875@cornell.edu>

# Enrollment waiting list

Enrollment for STSCI 4780 is currently full. **If you are hoping to add the course if spaces open up, please email Tom**, so you can get access to course announcements and material in private repositories.


# Course goals

Provide all students:

- A basic understanding of the principles and foundations underlying the Bayesian approach
- Practical experience using basic/intermediate Bayesian methods
- Experience with widely-used tools and software development practices for producing and sharing collaborative, reproducible statistical research
- Exposure to the Bayesian academic research literature 
- An understanding of key differences between Bayesian and frequentist approaches


# Course instructional material

Most course material will be available via the GitHub organization hosting this document. Some material is hosted on the course's Blackboard page, particularly material requiring a CU netID for access (e.g., Lynda.com video links).

Please note that all original course material is **copyrighted** by the instructor (&copy; 2015, 2018 by Thomas Loredo).  Please do not post it publicly.


# Grading

*Grading will be based almost entirely on homework assignments* (current plan).
Note that assignments will have varying difficulty, and thus contribute different amounts to your grade.
The final assignment will be a challenging two-week assignment.

*Everyone has a rough week now and then.* The assignment that has the most negative effect on your grade will be dropped in everyone's final grade calculation (except that the final assignment will not be dropped). If you wish, you may skip an assignment without prejudice, but please do so cautiously.

*Class involvement is important.* As statisticians, clear communication of understanding and uncertainty is something that will be expected of you, and you need to be able to do this verbally as well as in documents. I'll be keeping track of participation (in class, labs, and outside-of-class discussion). I don't care about you giving the "right" or "wrong" answer to a question (indeed, many questions won't have a unique right answer); I just want to see you genuinely engaged with the material, and with the class. Although class participation will not formally enter the grade calculation, for students at a boundary between grades, participation will be a factor influencing the assignment of the final grade.

# Textbooks

We will not be following the content of any one book. Lecture and lab notes (mine and yours), as well as assigned readings from various sources, should suffice for completing the course with a high grade if you're a good note-taker.

That said, if you plan on using Bayesian methods in your career, you should invest in at least one good book on Bayesian methods. One that's close in spirit to this course is:

*Doing Bayesian Data Analysis, Second Edition: A Tutorial with R, JAGS, and Stan*  
By John Kruschke

* [Amazon.com](http://smile.amazon.com/Doing-Bayesian-Data-Analysis-Second/dp/0124058884/ref=sr_1_1?s=books&ie=UTF8&qid=1421086218&sr=1-1&keywords=doing+bayesian+data)
* [Publisher's site (currently on sale)](http://store.elsevier.com/Doing-Bayesian-Data-Analysis/John-Kruschke/isbn-9780124059160/)
* [Author's book site (with discount link)](https://sites.google.com/site/doingbayesiandataanalysis/)
* [Author's blog (free chapter)](http://doingbayesiandataanalysis.blogspot.com/)
* [Via BigWords.com](http://www.bigwords.com/details/book/Doing_Bayesian_Data_Analysis_Second_Edition_A_Tutorial_with_R_JAGS_and_Stan/9780124058880/0124058884) (a new/used textbook search service)

Note it is the newer, 2nd edition, that I recommend. The library currently has only the first edition as a physical book; it will be available on reserve at the Math Library. However, both editions are available as eBooks.

If you believe Bayesian methods will play an important role in your career, consider purchasing what has become the standard reference:

*Bayesian Data Analysis, Third Edition*  
By Andrew Gelman, et al.

* [Amazon.com](http://www.amazon.com/Bayesian-Analysis-Chapman-Statistical-Science/dp/1439840954/)
* [Authors' site](http://www.stat.columbia.edu/~gelman/book/)
* [Publisher's site](http://www.crcpress.com/product/isbn/9781439840955)

This book covers BDA at an advanced level, suitable for a statistics PhD student.  However, much of it should be accessible to you, if not now, then at least after you've completed this course. Earlier editions may be available cheaply, but there is quite a bit of important material new to the third edition.

For Bayesian computation via *Markov chain Monte Carlo methods*, which will play a key role in this course, the following recent collection of tutorial chapters is becoming a standard reference:

*Handbook of Markov Chain Monte Carlo*  
By Steve Brooks, et al.

* [Amazon.com](http://www.amazon.com/Handbook-Chapman-Handbooks-Statistical-Methods/dp/1420079417)
* [Authors' site](http://www.mcmchandbook.net/HandbookTableofContents.html)
* [Publisher's site](http://www.crcpress.com/product/isbn/9781420079418)

Many of the chapters cover advanced methods, beyond what we will cover, but there are also good chapters on the basics. The book is quite expensive, but *four chapters are available for free* at the authors' site; the first two are essential reading. This will be on reserve at the Math Library.

Various scientific and engineering disciplines have produced books covering Bayesian methods tailored to specific fields. Cornell's library has quite a few of these; I'll mention some as the opportunity arises.

In my own fields of physics and astronomy, and in AI/computer science, one of the most influential texts on Bayesian foundations is:

*Probability Theory: The Logic of Science*  
By Edwin T. Jaynes; ed. by G. Larry Bretthorst

* [Amazon.com](http://www.amazon.com/Probability-Theory-The-Logic-Science/dp/0521592712)
* [Publisher's site](http://www.cambridge.org/asia/catalogue/catalogue.asp?isbn=0511059582)

Jaynes started working on this book in the late 1950s; I knew him and had access to some early versions. Unfortunately, he was such a perfectionist that he never felt happy with the book, and he left it unpublished at his death. His former student, Larry Bretthorst, did some final editing so the book could be published posthumously. The first three chapters are available on Bretthorst's web site: 
[PTLOS chapters 1-3 (PDF)](http://bayes.wustl.edu/etj/prob/book.pdf).

This book offers probably the clearest and most thorough modern account of the principles of Bayesian inference, and fundamental analytical developments. It has little content relevant to computational implementation of Bayesian methods, but of course a deep understanding of foundations and fundamentals is a great help for practical use. The book is quite polemical in places (reflecting its history). Persi Diaconis, an influential mathematician and Bayesian statistician (and former Cornellian, and magician!), wrote a wonderful, frank, and very positive review that is worth reading:

["A Frequentist Does This, A Bayesian That" (Diaconis's review of Jaynes's PTLOS)](http://www.siam.org/news/news.php?id=81)

I've put several other useful books on reserve; see the Blackboard site for a list.


# Lecture plan

 Lec # | Date   | Topic
---|--------|------
1|	Jan	25 | Course intro; Motivation: Models, measurements, arguments
2|	Jan	30 | Assessing deductive arguments: Propositional logic, Boolean algebra
3|	Feb 1 | Assessing inductive arguments:  Probability theory
4|	Feb	6 | Key theorems
5|	Feb	8 | Bayes with binary hypotheses and data
6|Feb	13|	 More models for discrete data:  Bernoulli, binomial/beta
7|Feb	15| Discrete data, cont'd:  Poisson/gamma, multinomial

After the Feb break, we'll synthesize what we've learned to a general prescription for inference with parametric models, and then continue with more sophisticated models---Bayesian counterparts to multi-parameter conventional regression models.

Next we'll focus on Bayesian computation, culminating with Markov chain Monte Carlo (MCMC).

With flexible computational tools in hand, we'll explore richer model structures---*hierarchical Bayesian models* (also known as multilevel models, or probabilistic graphical models).

I have a menu of further topics we'll address as time allows.  If you've encountered particular BDA topics you'd like to learn more about, please let me know; I may be able to work them into the schedule.


# Lab plan

For the first few weeks, the labs will operate somewhat separately from the lectures, aiming to build familiarity with the tools we'll use to implement nontrivial Bayesian computations later in the course.

 Lab # | Date   | Topic
---|--------|------
1|	Jan	26 | Markdown, Git, GitHub
2|	Feb 2 | IPython notebook
3|	 Feb 9 | The PyData stack
4| Feb	 16 | Bayesian computation for single-parameter models

As the lectures move beyond fundamental, analytically tractable examples, the labs and lectures will mesh more strongly, with labs implementing computational methods and flexible models covered in lecture.


