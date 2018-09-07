# The Incomplete Deep Learning Guide

From Self-Driving Cars to Alpha Go to Language Translation, Deep Learning seems to be everywhere nowadays. While the debate whether the hype is justified or not continues, Deep Learning has seen a rapid surge of interest across academia and industry over the past years.

With so much attention on the topic, more and more information has been recently published, from various MOOCs to books to YouTube Channels. With such a vast amount of resources at hand, there has never been a better time to learn Deep Learning.

Yet a side effect of such an influx of readily available material is choice overload. With thousands and thousands of resources, which are the ones worth looking at?

Inspired by Haseeb Qureshi&#39;s excellent [Guide on Learning Blockchain Development](https://medium.freecodecamp.org/the-authoritative-guide-to-blockchain-development-855ab65b58bc), this is my try to share the resources that I have found throughout my journey. As I am planning on continuously updating this guide with updated and better information, I deemed this work in progress an _incomplete guide_.

As of now, all the resources in this guide are all free thanks to their authors.

The link to my original blog post can be found [here](https://medium.freecodecamp.org/the-incomplete-deep-learning-guide-2cc510cb23ee).


**Target Audience**

- Anybody who wants to dive deeper into the topic, seeks a career in this field or aspires to gain a theoretical understanding of Deep Learning

**Goals of this Guide**

- Give an overview and a sense of direction within the ocean of resources
- Give a clear and useful path towards learning Deep Learning Theory and Development
- Give some practical tips along the way on how to maximize your learning experience

**Outline**

This guide is structured in the following way:

- **Phase 1** : Prerequisites
- **Phase 2** : Deep Learning Fundamentals
- **Phase 3** : Create Something
- **Phase 4** : Dive Deeper
- **Phase X** : Keep Learning

How long your learning will take depends on numerous factors such as your dedication, background and time-commitment. And depending on your background and the things you want to learn, feel free to skip to any part of this guide. The linear progression I outline below is just the path I found to be useful for myself.

**Phase 1: Pre-Requisites**

Let me be clear from the beginning. The prerequisites you need depend on the objectives you intend to pursue. The foundations you need to conduct research in Deep Learning will differ from the things you need to become a Practitioner (both are of course not mutually exclusive).

Whether you don&#39;t have any knowledge of coding yet or you are already an expert in R, I would still recommend acquiring a working knowledge of Python as most of the resources on Deep Learning out there will require you to know Python.

**Coding**

While Codecademy is a great way to start coding from the beginning, MIT&#39;s 6.0001 lectures are an incredible introduction to the world of computer science. So, is CS50, Harvard&#39;s infamous CS intro course, but CS50 has less of a focus on Python. For people who prefer reading, the interactive online book _How To Think Like A Computer Scientist_ is the way to go.

- [MIT Lecture 6.0001](https://www.youtube.com/watch?v=ytpJdnlu9ug&amp;list=PLUl4u3cNGP63WbdFxL8giv4yhgdMGaZNA)
- [CodeCademy](https://www.codecademy.com/learn/learn-python)
- [How to think like a Computer Scientist](http://interactivepython.org/runestone/static/thinkcspy/index.html)
- [Harvard CS50](https://www.edx.org/course/cs50s-introduction-computer-science-harvardx-cs50x)

**Math**

If you simply want to apply Deep Learning techniques to a problem you face or gain a high-level understanding of Deep Learning, it is not necessary to know its mathematical underpinnings. But, in my experience, it has been significantly easier to understand and even more rewarding to use Deep Learning frameworks after getting familiar with its theoretical foundations. For such intentions, the basics of Calculus, Linear Algebra and Statistics are extremely useful. Fortunately, there are plenty of great Math resources online.

Here are the most important concepts you should know:

1. Multivariable Calculus

- Differentiation
- Chain Rule
- Partial Derivatives

2. Linear Algebra

- Definition of Vectors &amp; Matrices
- Matrix Operations and Transformations: Addition, Subtraction, Multiplication, Transpose, Inverse

3. Statistics &amp; Probability

- Basic ideas like mean and standard deviation
- Distributions
- Sampling
- Bayes Theorem

That being said, it is also possible to learn these concepts concurrently with Phase 2, looking up the Math whenever you need it.

If you want to dive right into the Matrix Calculus that is used in Deep Learning, take a look at [The Matrix Calculus You Need For Deep Learning](https://arxiv.org/abs/1802.01528) by Terence Parr and Jeremy Howard.

**Calculus**

For Calculus, I would choose between the MIT OCW Lectures, Prof. Leonard&#39;s Lectures and Khan Academy. The MIT Lectures are great for people who are comfortable with Math and seek a fast-paced yet rigorous introduction to Calculus. Prof. Leonard Lectures are perfect for anybody who is not too familiar with Math as he takes the time to explain everything in a very understandable manner. Lastly, I would recommend Khan Academy for people who just need a refresher or want to get an overview as fast as possible.

- [MIT 18.01 Single Variable Calculus](https://www.youtube.com/watch?v=jbIQW0gkgxo&amp;t=1s)
- [Prof Leonard Calculus 1](https://www.youtube.com/watch?v=fYyARMqiaag&amp;list=PLF797E961509B4EB5)
- [Khan Academy Calculus 1](https://www.khanacademy.org/math/calculus-1)

**Linear Algebra**

For Linear Algebra, I really enjoyed Professor Strang&#39;s Lecture Series and its accompanying book on Linear Algebra (MIT OCW). If you are interested in spending more time on Linear Algebra, I would recommend the MIT lectures, but if you just want to learn the basics quickly or get a refresher, Khan Academy is perfect for that.

For a more hands-on coding approach, check out Rachel Thomas&#39; (from fast.ai) Computational Linear Algebra Course.

- [MIT 18.06 Linear Algebra](https://www.youtube.com/watch?v=ZK3O402wf1c&amp;list=PLE7DDD91010BC51F8)
- [Khan Academy Linear Algebra](https://www.khanacademy.org/math/linear-algebra)
- [Rachel Thomas&#39; Computational Linear Algebra](https://www.youtube.com/watch?v=8iGzBMboA0I&amp;index=1&amp;list=PLtmWHNX-gukIc92m1K0P6bIOnZb-mg0hY)

At last, this [review](http://cs229.stanford.edu/section/cs229-linalg.pdf) from Stanford&#39;s CS229 course offers a nice reference you can always come back to.

For both Calculus and Linear Algebra, 3Blue1Brown&#39;s Essence of Calculus and Linear Algebra series are beautiful complementary materials to gain a more intuitive and visual understanding of the subject.

- [3Blue1Brown Essence of Calculus](https://www.youtube.com/watch?v=WUvTyaaNkzM&amp;list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)
- [3Blue1Brown Essence of Linear Algebra](https://www.youtube.com/watch?v=kjBOesZCoqc&amp;list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

**Statistics and Probability**

Harvard has all its Stats 110 lectures, which is taught by Prof. Joe Blitzstein, on YouTube. It starts off with Probability and covers a wide range of Intro to Statistics topics. The practice problems and content can be challenging at times, but it is one of the most interesting courses out there.

Beyond Harvard&#39;s course, Khan Academy and Brandon Foltz also have some high-quality material on YouTube.

- [Harvard Statistics 110](https://www.youtube.com/watch?v=KbB0FjPg0mw&amp;list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo)
- [Khan Academy Statistics &amp; Probability](https://www.khanacademy.org/math/statistics-probability)
- [Brandon Foltz&#39; Statistics 101](https://www.youtube.com/user/BCFoltz/videos)

Similarly to Linear Algebra, Stanford&#39;s CS229 course also offers a nice [review](http://cs229.stanford.edu/section/cs229-prob.pdf) of Probability Theory that you can use as a point of reference.

**Phase 2: Deep Learning Fundamentals**

With the plethora of free deep learning resources online, the paradox of choice becomes particularly apparent. Which ones should I choose, which ones are the right fit for me, where can I learn the most?

**MOOCs**

Just as important as learning theory is practicing your newfound knowledge, which is why my favorite choice of MOOCs would be a mix of Andrew Ng&#39;s [_deeplearning.ai_](https://www.coursera.org/specializations/deep-learning) (more theoretical) and Jeremy Howard&#39;s and Rachel Thomas&#39; [_fast.ai_](http://course.fast.ai/) (more practical). Andrew Ng is excellent at explaining the basic theory behind Deep Learning, while fast.ai is a lot more focused on hands-on coding. With the theoretical foundations of deeplearning.ai, Jeremy Howard&#39;s code and explanations become a lot more intuitive, while the coding part of fast.ai is super helpful to ingrain your theoretical knowledge into practical understanding.

fast.ai Part I

Since deeplearning.ai consists of five courses and fast.ai consists of two parts, I would structure my learning in the following way:

1. Watch Deep Learning.ai&#39;s Course Lectures I, II, IV and V
2. Take Fast.ai Part I
3. Watch Deeplearning.ai Course III
4. Optional: Take deeplearning.ai assignments
5. Repeat Steps 1–4 or Go to Phase III

The reason I would first skip the deeplearning.ai assignments is that I found fast.ai&#39;s coding examples and assignments to be a lot more practical than the deeplearning.ai assignments. If you want to reiterate the deeplearning.ai course material (i.e. repetition to strengthen your memory), then give the assignments a try. Unlike fast.ai, which uses PyTorch and its own fastai library, they primarily use Keras. So, it&#39;s a good opportunity to get familiar with another Deep Learning Framework.

Fast.ai Part 2 deals with quite advanced topics and requires a good grasp of theory as wells as the coding aspects of Deep Learning, which is why I would put that one in Phase IV of this guide.

**Tip:** You can freely watch deeplearning.ai videos on Coursera, but you need to purchase the specialization to do the assignments. If you can&#39;t afford the coursera specialization fee, apply for a [scholarship](https://learner.coursera.help/hc/en-us/articles/209819033-Apply-for-Financial-Aid)!

For people who prefer reading books, Michael Nielsen published a free [Intro book on Deep Learning](http://neuralnetworksanddeeplearning.com/) that also incorporates coding examples in Python.

To really take advantage of fast.ai, you will need a GPU. But lucky us, Google offers an environment similar to Jupyter Notebooks called [_Google Colaboratory_](https://colab.research.google.com/) that comes with free GPU access. Somebody already made a tutorial on how to use Colab for Fast.ai. So, check that out [here](https://towardsdatascience.com/fast-ai-lesson-1-on-google-colab-free-gpu-d2af89f53604). Kaggle has also started providing accessto a free Nvidia K80 GPU on their [_Kernels_](https://www.kaggle.com/dansbecker/running-kaggle-kernels-with-a-gpu).

AWS also provides students with up to 100$ in credits (depending on whether your college is part of their program), which you can use for their GPU instances.

**Complementary Non-Mooc Material**

Do not solely rely on one means of information, combine watching videos with coding and reading.

**YouTube**

Just like in his series on Calculus and Linear Algebra, 3Blue1Brown gives one of the most intuitive explanations on Neural Networks. Computer Phile and Brandon also offer great explanations of Deep Learning, each from a slightly different perspective. Lastly, sentdex can be helpful as he instantly puts concepts into code.

- [3Blue1Brown Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)
- [Computer Phile Neural Networks](https://www.youtube.com/playlist?list=PLzH6n4zXuckoezZuZPnXXbvN-9jMFV0qh)
- [Brandon Rohrer Neural Networks](https://www.youtube.com/watch?v=ILsA4nyG7I0)
- [Practical Machine Learning sentdex](https://www.youtube.com/watch?v=OGxgnH8y2NM&amp;list=PLQVvvaa0QuDfKTOs3Keq_kaG2P55YRn5v)

**Beginner-Friendly Blogs**

Blogs are also a phenomenal way of reiterating over newly acquired knowledge, exploring new ideas or going in-depth into a topic.

[Distill.pub](https://distill.pub/) is one of the best blogs I know in the Deep Learning space and beyond. The way its editors approach topics like [Feature Visualization](https://distill.pub/2017/feature-visualization/) or [Momentum](https://distill.pub/2017/momentum/) is simply clear, dynamic and engaging.

Although not updated anymore, [Andrej Karpathy&#39;s old Blog](http://karpathy.github.io/) has some classic articles on things such as [RNNs](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) that are worth checking out.

Finally, Medium Publications like FreeCodeCamp and Towards Data Science regularly publish interesting posts from [Reinforcement Learning](https://simoninithomas.github.io/Deep_reinforcement_learning_Course/) to [Objection Detection](https://towardsdatascience.com/deep-learning-for-object-detection-a-comprehensive-review-73930816d8d9).

**Coding**

Get familiar with code! Knowing how to graph plots, deal with messy data and do scientific computing is crucial in Deep Learning, which is why libraries such as Numpy or Matplotlib are ubiquitously used. So, practicing and using these tools will definitely help you along the way.

Jupyter Notebook

- [Introduction, Setup and Walkthrough](https://www.youtube.com/watch?v=HW29067qVWk)
- [DataCamp Comprehensive Jupyter Notebook Tutorial](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook?utm_source=adwords_ppc&amp;utm_campaignid=1366776656&amp;utm_adgroupid=57448230227&amp;utm_device=c&amp;utm_keyword=&amp;utm_matchtype=b&amp;utm_network=g&amp;utm_adpostion=1t1&amp;utm_creative=265681164941&amp;utm_targetid=aud-364780883969:dsa-429603003980&amp;utm_loc_interest_ms=&amp;utm_loc_physical_ms=9042585&amp;gclid=Cj0KCQjwxtPYBRD6ARIsAKs1XJ4XsOoAhoDXVUIxahP5aX2Ign1X8w1IKQ3RSAvfwnzh9m6rSPLMX1waAs3NEALw_wcB)

Jupyter Notebooks can be a great tool but definitely carry some drawbacks. Take a look at Joel Grus&#39; informative and meme-filled presentation [_I don&#39;t Like Notebooks_](https://docs.google.com/presentation/d/1n2RlMdmv1p25Xy5thJUhkKGvjtV-dkAIsUXP-AL4ffI/preview?slide=id.g362da58057_0_1) to be aware of those pitfalls.

Numpy

- [Stanford CS231 Numpy Tutorial](http://cs231n.github.io/python-numpy-tutorial/)
- [DataCamp Numpy Tutorial](https://www.datacamp.com/community/tutorials/python-numpy-tutorial)

Pandas

- [Data School Comprehensive Tutorial Series on Data Analysis Pandas](https://www.youtube.com/watch?v=yzIMircGU5I&amp;list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y)
- [Code Basics Short Tutorial Series on Pandas](https://www.youtube.com/watch?v=CmorAWRsCAw&amp;list=PLeo1K3hjS3uuASpe-1LjfG5f14Bnozjwy)

Scikit-learn

- [Data School scikit-learn Tutorial Series](https://www.youtube.com/watch?v=elojMnjn4kk&amp;list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A)

Matplotlib

- [Sentdex Matplotlib Series](https://www.youtube.com/watch?v=q7Bo_J8x_dw&amp;list=PLQVvvaa0QuDfefDfXb9Yf0la1fPDKluPF)
- [Matplotlib Video Tutorials](https://www.youtube.com/watch?v=b3lK639ymu4&amp;list=PLNmACol6lYY5aGQtxghQTq0bHXYoIMORy)

And if you ever get stuck with a concept or code snippet, google it! The quality of the answers will be highly variable, but sites such as Quora, Stackoverflow or PyTorch&#39;s excellent Forum are certainly sources you can leverage. Reddit can sometimes offer nice explanations as well, in formats such as [ELI5](https://www.reddit.com/r/explainlikeimfive/) (Explain Me Like I&#39;m Five) when you&#39;re completely perplexed by a new topic.

**Phase 3: Create Something**

While you should definitely play around with code and use it with external datasets/problems while taking the fast.ai course, I think it&#39;s crucial to implement your own project as well. The deeplearning.ai course III is an excellent guide on how to structure and execute a Machine Learning Project.

**Brainstorm Ideas**

Start with brainstorming ideas that seem feasible to you with the knowledge you just acquired, look at openly available datasets and think about problems you might want to solve with Deep Learning. Take a look at these [Projects](https://github.com/NirantK/awesome-project-ideas) to get some inspiration!

**Or Use Kaggle**

Otherwise, an easy way to start with a project is participating in a [Kaggle competition](https://www.kaggle.com/competitions) (current or past) or exploring their vast amount of [open datasets](https://www.kaggle.com/datasets). Kaggle offers an excellent gateway into the ML community. People share Kernels (their walkthrough of a given problem) and actively discuss ideas, which you can learn from. It becomes especially interesting after the end of a competition, when teams start to post their solutions in the Discussion Forums, which often involves creative approaches to the competition.

**Choose a framework**

Whatever Deep Learning Framework you feel most comfortable, choose one! I would go for either PyTorch or Keras as they are both relatively easy to pick up and have a very active community.

**Reflect**

After completing your project, take a day or so to reflect on what you have achieved, what you have learned and what you could improve upon in the future. This is also the perfect time to write your first blog post! It&#39;s one thing to think that you understand something and another to convey it to other people. Quincy Larson, the founder of FreeCodeCamp, gave a really helpful presentation on how to write a technical blog post [here](https://www.youtube.com/watch?v=YODPgBadj80).

**Phase 4: Dive Deeper**

Now that you built some fundamental Deep Learning knowledge and went through your first Practical Experience, it&#39;s time to go deeper!

From here on, there are tons of things you can do. But the first thing I would do is go through Fast.ai Part 2 [Cutting Edge Deep Learning For Coders](http://course.fast.ai/part2.html). As the name suggests, you&#39;ll learn some of the cutting edge stuff in Deep Learning: from GANs to Neural Translation to Super Resolution! The course will give you an overview of some of the hottest topics in Deep Learning right now with a strong focus on Computer Vision and Natural Language Processing (NLP). I particularly appreciate the course as Jeremy Howard not only gives very clear explanations but also really goes into the code that is needed to enable these ideas.

After fast.ai, here are some of the things you can do:

- Take a deep dive into one topic such as Computer Vision, NLP or Reinforcement Learning
- Read papers and/or reimplement ideas from a paper
- Do more projects and/or gain work experience in Deep Learning
- Follow blogs, listen to podcasts and stay up to date

**Deep Dives**

**Computer Vision**

The best place to continue your Computer Vision path is definitely Stanford&#39;s CS231n Course, also called _Convolutional Neural Networks for Visual Recognition_. They not only have all their lecture videos online, but their website also offers [course notes](http://cs231n.github.io/) and [assignments](http://cs231n.stanford.edu/2017/syllabus.html)! Fast.ai Part 2 and deeplearning.ai will give you a good foundation for the course as CS231n will go a a lot further in terms of the theory behind CNNs and related topics.

While both versions cover mostly the same topics, which also means _choose whichever version&#39;s teaching style you like better_, the final lectures differ slightly. For example, 2017 incorporates a Lecture on Generative Models and 2016 has a guest lecture by Jeff Dean on Deep Learning at Google. If you want to see how Computer Vision was before Deep Learning took off, the University of Central Florida (UCF) has a Computer Vision course from 2012 teaching about concepts such as SIFT features.

- [Stanford CS231n (2017)](https://www.youtube.com/watch?v=vT1JzLTH4G4&amp;list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk)
- [Stanford CS231n (2016)](https://www.youtube.com/watch?v=NfnWJUyUJYU&amp;list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC)
- [UCF Computer Vision (2012](https://www.youtube.com/watch?v=715uLCHt4jE&amp;list=PLd3hlSJsX_ImKP68wfKZJVIPTd8Ie5u-9))

**Natural Language Processing**

Stanford has quite an extensive course called CS224n _Natural Language Processing with Deep Learning_, which similarly to CS231n not only uploaded its lecture videos but also hosts a handy website with [lecture slides, assignments, assignment solutions](http://web.stanford.edu/class/cs224n/syllabus.html) and even students&#39; [Class Projects](http://web.stanford.edu/class/cs224n/reports.html)!

Oxford also has a very nice lecture series on NLP in cooperation with DeepMind. While it does have a helpful [GitHub repository](https://github.com/oxford-cs-deepnlp-2017/lectures) with slides and pointers to further readings, it lacks the assignment part of Stanford&#39;s CS224. The courses overlap to some extent, but not to the extent that it&#39;s not worth looking at both courses.

- [Stanford NLP with Deep Learning (2017)](https://www.youtube.com/watch?v=OQQ-W_63UgQ&amp;list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6)
- [Oxford Deep Learning for NLP with DeepMind (2017)](https://www.youtube.com/watch?v=RP3tZFcC2e8&amp;list=PL613dYIGMXoZBtZhbyiBqb0QtgK6oJbpm)

**General Deep Learning**

For people who are still unsure about what in Deep Learning excites them the most, Carnegie Mellon University (CMU) has a course on _Topics in Deep Learning_, which introduces a broad range of topics from Restricted Boltzmann Machines to Deep Reinforcement Learning. Oxford also has a Deep Learning Course, which can give you a firmer mathematical grasp of concepts you learned in deeplearning.ai and fast.ai, meaning things such as Regularization or Optimization. A book that could help you in any Deep Learning field is _The Deep Learning Book_ byIan Goodfellow et al., which is the most comprehensive book on Deep Learning theory I know of. Classes such as Oxford&#39;s NLP course also use this book as complementary material. Noteworthy as well is that top-tier research conferences such as NIPS or ICML, which disseminate the state-of-the-art Deep Learning papers, regularly publish their keynote and tutorial videos.

- [CMU Topics in Deep Learning Course (2017)](https://www.youtube.com/watch?v=fDlOQrLX8Hs&amp;list=PLpIxOj-HnDsOSL__Buy7_UEVQkyfhHapa)
- [Oxford Deep Learning Course (2015)](https://www.youtube.com/watch?v=PlhFWT7vAEw&amp;list=PLjK8ddCbDMphIMSXn-w1IjyYpHU3DaUYw)
- [Deep Learning Book by Ian Goodfellow et al.](https://www.deeplearningbook.org/)
- [NIPS](https://nips.cc/Conferences/2017/Videos) (2017), [ICML](https://icml.cc/Conferences/2017/Videos) (2017), [ICLR](https://www.facebook.com/pg/iclr.cc/videos/) (2018) Conference Videos

**Reinforcement Learning**

As Reinforcement Learning (RL) is neither covered by deeplearning.ai nor fast.ai, I would first watch Arxiv Insight&#39;s Intro to RL and Jacob Schrum&#39;s RL videos, which are extremely understandable explanations of the topic. Then head to Andrej Karpathy&#39;s blog post on Deep Reinforcement Learning and read Chapter 1–2 of Andrew Ng&#39;s PhD Thesis (as suggested by[Berkeley&#39;s CS 294 website](http://rll.berkeley.edu/deeprlcoursesp17/#prerequisites)) to get a primer on Markov Decision Processes. Afterward, David Silver&#39;s (Deep Mind) Course on RL will give you a strong foundation to transition to Berkeley&#39;s CS294 Course on Deep RL. Alternatively, there are recorded sessions of a Deep RL Bootcamp at Berkeley and an RL Summer School at the Montreal Institute for Learning Algorithms with speakers like Pieter Abbeel and Richard Sutton. The latter also co-authored an introductory textbook on RL, which currently can be accessed openly in its 2nd edition as a draft (chapter 3 &amp; 4 are pre-readings for CS294). Additionally, Udacity has a fabulous [GitHub repo](https://github.com/udacity/deep-reinforcement-learning) with tutorials, projects and a cheatsheet from their _paid_ Deep RL course. Another resource that was published recently is Thomas Simonini&#39;s ongoing Deep RL course that is very easy to follow and hands-on in its coding methodology.

- [Arxiv Insight&#39;s Intro To RL Video](https://www.youtube.com/watch?v=JgvyzIkgxF0)
- [Jacob Schrum&#39;s Intro To RL](https://www.youtube.com/watch?v=3T5eCou2erg&amp;list=PLWi7UcbOD_0u1eUjmF59XW2TGHWdkHjnS)
- [Andrej Karpathy&#39;s Blog Post on Deep Reinforcement Learning](http://karpathy.github.io/2016/05/31/rl/)
- [Chapter 1–2 of Andrew Ng&#39;s PhD Thesis on Markov Decision Processes](http://rll.berkeley.edu/deeprlcoursesp17/docs/ng-thesis.pdf)
- [David Silver&#39;s Course on Reinforcement Learning](https://www.youtube.com/watch?v=2pWv7GOvuf0&amp;list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-)
- [Berkeley CS294 Deep Reinforcement Learning Course(2017](http://rll.berkeley.edu/deeprlcoursesp17/))
- [Berkeley CS294 Deep Reinforcement Learning (2018, ongoing session)](http://rail.eecs.berkeley.edu/deeprlcourse/)
- [Reinforcement Learning: An Introduction (Book Draft, 2018)](http://incompleteideas.net/book/bookdraft2018jan1.pdf)
- [Berkeley Deep RL Bootcamp (2017)](https://www.youtube.com/watch?v=qaMdN6LS9rA&amp;list=PLAdk-EyP1ND8MqJEJnSvaoUShrAWYe51U)
- [MILA Reinforcement Learning Summer School (2017](https://mila.quebec/en/cours/deep-learning-summer-school-2017/))
- [Udacity Deep RL GitHub Repo](https://github.com/udacity/deep-reinforcement-learning)
- [Thomas Simonini&#39;s Deep RL Course](https://simoninithomas.github.io/Deep_reinforcement_learning_Course/)

**Machine Learning (that is not necessarily Deep Learning)**

There is certainly value to knowing various Machine Learning ideas that came before Deep Learning. Whether Logistic Regression or Anomaly Detection, Andrew Ng&#39;s classic Machine Learning Course is a great starting point. If you want a more mathematically rigorous course, Caltech has a superb MOOC that is more theoretically grounded. Professor Ng is also writing a book with ML best practices, for which you can access the first chapters of his draft.

- [Andrew Ng&#39;s Machine Learning course (2012)](https://www.coursera.org/learn/machine-learning)
- [Caltech CS156 Machine Learning course (2012)](http://work.caltech.edu/telecourse.html)
- [Machine Learning Yearning Book by Andrew Ng](http://www.mlyearning.org/)

**Self-Driving Cars**

Self-Driving Cars are one of the most interesting areas of application for Deep Learning. So, it&#39;s quite amazing that MIT offers its own course on that topic. The course will give you a breadth of introductions to topics such as perception and motion planning as well as provide you with insights from industry experts such as the Co-Founder of Aurora. If you&#39;re further interested in the Computer Vision part of Autonomous Driving, a few researchers from ETH Zurich and the Max Planck Institute for Intelligent Systems have written an extensive survey on the subject matter. Moreover, ICCV uploaded the slides from an 8-Part Tutorial Series, which have some useful information on Sensor Fusion and Localization. Regarding projects I would take a look at projects from Udacity&#39;s _paid_ Self-Driving Car Nanodegree, which you can _freely_ find on GitHub. Udacity does consistently offer scholarships. For instance, [last year](https://www.udacity.com/scholarships/lyft) in cooperation with Lyft for its Self-Driving Cars Intro Course. So, be on the lookout for that as well!

- [MIT Self-Driving Cars Course (2018)](https://www.youtube.com/watch?v=-6INDaLcuJY&amp;list=PLrAXtmErZgOeiKm4sgNOknGvNjby9efdf)
- [Computer Vision for Autonomous Vehicles: Problems, Datasets and State-of-the-Art (2017)](https://arxiv.org/pdf/1704.05519.pdf)
- [ICCV Tutorial on Computer Vision for Autonomous Driving (2015)](https://sites.google.com/site/cvadtutorial15/materials)
- [Udacity Self-Driving Car Project Ideas](https://github.com/ndrplz/self-driving-car)

**Strengthen your understanding of Fundamental Concepts**

You will keep encountering fundamental concepts such as Losses, Regularizations, Optimizers, Activation Functions and Gradient Descent, so gaining an Intuition for them is crucial. Two posts that expound Gradient Descent and Backpropagation very well:

- [Sebastian Ruder Gradient Descent Blog Post](http://ruder.io/optimizing-gradient-descent/)
- [CS231n Backpropagation](http://cs231n.github.io/optimization-2/)

**Read Papers**

While Arxiv is of paramount importance in the fast and open dissemination of Deep Learning research ideas, it can get overwhelming very quickly with the influx of papers on the platform. For that reason, Andrej Karpathy built [_Arxiv Sanity_](http://www.arxiv-sanity.com/), a tool that lets you filter and track papers according to your preferences. Here are just a few seminal papers from recent years, starting with the ImageNet Papers (AlexNet, VGG, InceptionNet, ResNet) that have had a tremendous influence on the trajectory of Deep Learning.

- [AlexNet](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf) (2012), [VGG](https://arxiv.org/abs/1409.1556) (2014), [InceptionNet](https://arxiv.org/pdf/1409.4842.pdf) (2014), [ResNet](https://arxiv.org/abs/1512.03385) (2015)
- [Generative Adversarial Networks (2014)](https://arxiv.org/abs/1406.2661)
- [Yolo Object Detection Paper (2015)](https://arxiv.org/abs/1506.02640)
- [Playing Atari with Deep Reinforcement Learning (2013)](https://arxiv.org/pdf/1312.5602.pdf)

**YouTube Channels**

_Arxiv Insights_,_CodeEmperium_ and _Yannic Kilcher_ are the most under-appreciated YouTube Channels on Deep Learning with some of the clearest explanations on Autoencoders and Attention. Another YouTube Channel that should be mentioned is _Lex Fridman, who_ is the main instructor MIT&#39;s Self-Driving Course, but also taught MIT&#39;s course on Artificial General Intelligence, which has some fascinating lectures on Meta-Learning, Consciousness and Intelligence. And finally, no such YouTube list could leave out _Siraj Rival_. Some hate him, some love him. It really depends on what you prefer and what you want to get out of such videos. For me, I&#39;m not that compatible with his way of teaching, but I do appreciate the variety of content he publishes and the entertainment value he provides.

- [Arxiv Insights](https://www.youtube.com/channel/UCNIkB2IeJ-6AmZv7bQ1oBYg/videos)
- [CodeEmperium](https://www.youtube.com/channel/UC5_6ZD6s8klmMu9TXEB_1IA/videos)
- [Yannic Kilcher](https://www.youtube.com/channel/UCZHmQk67mSJgfCCTn7xBfew/videos)
- [Lex Fridman](https://www.youtube.com/user/lexfridman)
- [Siraj Rival](https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A/featured)

**Podcasts**

Podcasts are quite a nice way to hear from various people on a diverse range of topics. Two of my favorite podcasts, which produce a lot of Deep Learning related content, are T_alking Machines_ and _This Week in ML &amp; AI_ (TWiML&amp;AI). For example, listen to Talking Machine&#39;s recent [podcast](https://www.thetalkingmachines.com/episodes/icml-2018-jennifer-dy) at ICML 2018 or TWiML&#39;s [podcast](https://twimlai.com/twiml-talk-176-openai-five-with-christy-dennison/) with OpenAI Five&#39;s Christy Dennison!

- [Talking Machines](https://www.thetalkingmachines.com/)
- [This Week in ML &amp; AI](https://twimlai.com/)

**Blogs**

As mentioned previously, I am a huge fan of _Distill.pub,_ and _o_ne of its Editors, _Chris Olah_, has some other high-quality posts on his personal blog as well. Another really promising blog is _The Gradient_, which provides well-written and clear overviews of the newest research findings as well as perspectives on the future of the field. Sebastian Ruder is one of the contributing authors of The Gradient and like Chris Olah, his blog has some awesome content as well, in particular for NLP-related topics. The last blog is not really a blog, but rather a hub for study plans to specific papers such as AlphaGo Zero or InfoGans. For each of these topics, _Depth First Learning_ publishes curriculums that allow you to learn the ideas of the papers at their cores.

- [pub](https://distill.pub/)
- [Chris Olah](http://colah.github.io/)
- [The Gradient](https://thegradient.pub/)
- [Sebastian Ruder](http://ruder.io/#open)
- [Depth First Learning](http://www.depthfirstlearning.com/)

**Cheatsheets**

Cheatsheets are awesome. After learning new concepts or programming commands, you can always refer back to them in case you forget, for example, how to retrieve array dimensions in Numpy. 

- [Deep Learning](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-deep-learning)
- [PyTorch](https://www.sznajdman.com/pytorch-cheat-sheet/)
- [Numpy](https://www.datacamp.com/community/blog/python-numpy-cheat-sheet)
- [Pandas](https://www.datacamp.com/community/blog/python-pandas-cheat-sheet)
- [Matplotlib](https://www.datacamp.com/community/blog/python-matplotlib-cheat-sheet)
- [Scikit-Learn](https://www.datacamp.com/community/blog/scikit-learn-cheat-sheet)
- [Jupyter Notebook](https://www.datacamp.com/community/blog/jupyter-notebook-cheat-sheet)

**Requests for Research**

In case you want to get started with your own research, here are some pointers to topics other people have requested for research.

- [Sebastian Ruder NLP](http://ruder.io/requests-for-research/)
- [OpenAI Reinforcement Learning](https://blog.openai.com/requests-for-research-2/)
- [AI Open Network](https://ai-on.org/)

**Stay Up to Date**

Believe it or not, but one of the best ways to stay updated on the progress of Deep Learning is Twitter. Tons of researchers use the platform to share their publications, discuss ideas and interact with the community.

Some of the people worth following on Twitter:

- [hardmaru](https://twitter.com/hardmaru)
- [Jeremy Howard](https://twitter.com/jeremyphoward)
- [Rachel Thomas](https://twitter.com/math_rachel)
- [Sebastian Ruder](https://twitter.com/seb_ruder)
- [Fei Fei Li](https://twitter.com/drfeifei)
- [Smerity](https://twitter.com/Smerity)
- [François Chollet](https://twitter.com/fchollet)

**Phase X: Keep Learning**

The field is changing rapidly, so keep learning and enjoy the ride.



