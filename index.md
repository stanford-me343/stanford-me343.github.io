## ME 343 Homepage

Welcome to this class. We hope you will enjoy it!

This is the first time this class is offered by the Mechanical Engineering Department so we will be experimenting with the content a bit. Here is the tentative content. We will make some adjustments as we go depending on interest and time left:

- Gaussian process regression
- Support vector machine for classification; kernel machines
- Deep learning
- Recurrent Neural Network
- Generative Adversarial Networks (GAN)
- Physics-informed learning machines (a new method specific to ME!)
- Reinforcement learning
- Markov decision processes, Bellman equation, Monte-Carlo tree search, and dynamic programming
- Temporal-difference learning (if time allows)

The material for this class is hosted on github. It can be downloaded from the main repository page
 [https://github.com/stanford-me343/stanford-me343.github.io](https://github.com/stanford-me343/stanford-me343.github.io)

 If you click on the green button "Clone or download" you can download all the files as a zip archive.

### Office hours

- Tuesday: 7 PM to 8 PM (Hojat)
- Wednesday: 10 AM to 11 AM (Ziyi/Hojat)
- Thursday: 10 AM to 11 AM (Ziyi)
- Friday: 9 AM to 11 AM (Prof. Darve)

Office hours with TAs are held in the Huang basement. Prof. Darve's office hours are in building 520, room 125.

### Course material and links

- [AlphaGo slides](AlphaGo.html)
- [Class feedback form](https://docs.google.com/forms/d/e/1FAIpQLSe2bZaO6MB8ubaKCBqbsEVCwOGArBsm2sAI6guunUpPU6jg2Q/viewform)
- [Final project](project/project.pdf)
- [Homework assignment folder](hwk.md)
- [Demo computer code](code.md)
- [Piazza forum](https://piazza.com/class/jqffwoswj8k50a)
- [Gradescope](https://www.gradescope.com/); used to submit your assignments, see your grades, and request regrades for assignments.
- [Mailing list](https://mailman.stanford.edu/mailman/listinfo/me343-winter1819); the instructors use this mailing list to send important messages; **please check that you are registered.**
- [Syllabus](syllabus.md)
- [Interactive polls on pollev](https://pollev.com/ericdarve886)

### Contact information

- Main instructor: Eric Darve, [darve@stanford.edu](mailto:darve@stanford.edu), office 520-125
- Lecturer: Hojat Ghorbanidehno, [hojjatgh@stanford.edu](mailto:hojjatgh@stanford.edu)
- TA: Ziyi Yang, [ziyi.yang@stanford.edu](mailto:ziyi.yang@stanford.edu)

### Reading material

[Curated list of scientific machine learning papers](http://www.cs.colorado.edu/~paco3637/sciml-refs.html) from Paul Constantine.

Contributors: Nathan Baker, Jed Brown, Reagan Cronin, Ian Grooms, Jan Hesthaven, Des Higham, Katy Huff, Mark Kamuda, Julia Ling, Vasudeva Murthy, Houman Owhadi, Christoph Schwab.

Curation criteria:

- has ML, AI, Big Data, or related terms in the title
- comes from a scientific journal
- bias toward broad audience journals
- claims application to a scientific field or problem
- bias toward computational sciences
- bias toward recent publications
- bias toward perspective/prospective-type articles (e.g., "opportunities and challenges") and surveys/reviews
- bias toward materials design, fluid dynamics, and some environmental sciences
- bias against arXiv papers and preprints
- bias against medicine and related fields
- bias against social sciences and related fields
- bias against fast algorithms or HPC implementations

General book about machine learning: [The Hundred-Page Machine Learning Book](https://leanpub.com/theMLbook), by Andriy Burkov. Relatively easy to read with a discussion of all the fundamental concepts. The book does not cover more advanced topics though.

### Reading by topics

### Reinforcement learning

- [AlphaGo](https://www.nature.com/articles/nature16961), "Mastering the game of Go with deep neural networks and tree search," by Silver et al.
- [AlphaGo Zero](https://www.nature.com/articles/nature16961), "Mastering the game of Go without human knowledge," by Silver et al.
- [AlphaZero](https://arxiv.org/abs/1712.01815), "Mastering Chess and Shogi by self-play with a general reinforcement learning algorithm," by Silver et al.
- [Reinforcement learning: an introduction](https://searchworks.stanford.edu/view/5320501) by R.S. Sutton and A.G. Barto; [draft of second edition](http://incompleteideas.net/book/bookdraft2017nov5.pdf).
- [Course on reinforcement learning](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html) by David Silver (2015). David was one of the lead researchers on AlphaGo.
- [Curated list of resources on reinforcement learning](https://github.com/aikorea/awesome-rl), by H. Kim and J. Kim.
- [OpenAI Gym](https://gym.openai.com/), toolkit for developing and comparing reinforcement learning algorithms

### Physics-informed learning

- [G.E. Karniadakis, physics-informed learning papers on arxiv](https://arxiv.org/search/advanced?advanced=&terms-0-operator=AND&terms-0-term=karniadakis&terms-0-field=author&terms-1-operator=AND&terms-1-term=physics&terms-1-field=title&terms-2-operator=AND&terms-2-term=informed&terms-2-field=title&classification-physics_archives=all&classification-include_cross_list=include&date-filter_by=all_dates&date-year=&date-from_date=&date-to_date=&date-date_type=submitted_date&abstracts=show&size=50&order=-announced_date_first)
- [G.E. Karniadakis, machine-learning papers on arxiv](https://arxiv.org/search/advanced?advanced=&terms-0-operator=AND&terms-0-term=karniadakis&terms-0-field=author&terms-1-operator=AND&terms-1-term=machine+learning&terms-1-field=abstract&classification-physics_archives=all&classification-include_cross_list=include&date-filter_by=all_dates&date-year=&date-from_date=&date-to_date=&date-date_type=submitted_date&abstracts=show&size=50&order=-announced_date_first)
- [Physics-Informed Generative Adversarial Networks for Stochastic Differential Equations](https://arxiv.org/abs/1811.02033) by L. Yang, D. Zhang, and G.E. Karniadakis
- [Neural-net-induced Gaussian process regression for function approximation and PDE solution](https://arxiv.org/abs/1806.11187)
by G. Pang, L. Yang, and G.E. Karniadakis

### GAN

- [GAN Lab](https://arxiv.org/pdf/1809.01587) by M. Kahng, N. Thorat, D.H. Chau, F.B. Viegas, and M. Wattenberg
- [GAN series](https://medium.com/@jonathan_hui/gan-gan-series-2d279f906e7b), blog by Jonathan Hui
- [An overview of gradient descent optimization algorithms](http://ruder.io/optimizing-gradient-descent/index.html), blog by Sebastian Ruder
- [GAN tutorial](https://github.com/tensorflow/models/blob/master/research/gan/tutorial.ipynb)
- [Generative adversarial nets](https://arxiv.org/pdf/1406.2661) by I.J. Goodfellow, J. Pouget-Abadie, M. Mirza, B. Xu, D. Warde-Farley, S. Ozair, A. Courville, Y. Bengio
- [Wasserstein GAN](https://arxiv.org/pdf/1701.07875) by M. Arjovsky, S. Chintala, L. Bottou
- [Improved training of Wasserstein GANs](https://arxiv.org/pdf/1704.00028) by I. Gulrajani, F. Ahmed, M. Arjovsky, V. Dumoulin, A. Courville
- [InfoGAN: interpretable representation learning by information maximizing generative adversarial nets](https://arxiv.org/pdf/1606.03657) by X. Chen, Y. Duan, R. Houthooft, J. Schulman, I. Sutskever, P. Abbeel
- [Conditional generative adversarial nets](https://arxiv.org/pdf/1411.1784) by M. Mirza, S. Osindero

### Deep learning

- LeCun, Yann, Yoshua Bengio, and Geoffrey Hinton. ["Deep learning."](https://www.cs.toronto.edu/~hinton/absps/NatureDeepReview.pdf) Nature 521.7553 (2015): 436.
- [Deep learning](http://www.deeplearningbook.org/) by I. Goodfellow, Y. Bengio, and A. Courville
- [Deep learning summer school, Montreal 2015](http://videolectures.net/deeplearning2015_montreal/), with many video presentations and tutorials
- [Deep learning for perception](https://computing.ece.vt.edu/~f15ece6504/), course from Virginia Tech
- [Deep learning methods and applications](https://drive.google.com/file/d/0B51wXUnyPM2ybVAwRXBrdFVPSk0/view), online book by L. Deng and D. Yu
- [Neural networks and deep learning](http://neuralnetworksanddeeplearning.com/index.html), online book by M. Nielsen
- ["Optimization methods for large-scale machine learning,"](https://arxiv.org/pdf/1606.04838.pdf) by L. Bottou. F.E. Curtis, and J. Nocedal. This paper discusses among other things the stochastic gradient method.

### SVM

- [A tutorial on support vector regression](https://link.springer.com/article/10.1023/B:STCO.0000035301.49549.88) by Smola and Scholkopf
- [A tutorial on support vector machines for pattern
recognition](https://link.springer.com/article/10.1023/A:1009715923555) by Burges. They have a very interesting mechanical analogy in terms of force and torque for the separating hyperplane.

### GPR

- [Gaussian processes for machine learning](http://www.gaussianprocess.org/gpml/) by Carl Edward Rasmussen and Christopher K. I. Williams, The MIT Press, 2006. ISBN 0-262-18253-X. This is a reference textbook on Gaussian Processes. Very extensive. Everything you ever wanted to know about GPR.
- Short review paper; [Gaussian processes for regression](http://papers.nips.cc/paper/1048-gaussian-processes-for-regression.pdf) by Williams and Rasmussen
- Intermediate review paper; [Introduction to Gaussian processes](https://www.ics.uci.edu/~welling/teaching/KernelsICS273B/gpB.pdf) by Mackay
- Intermediate review paper; [Prediction with Gaussian processes from linear regression to linear prediction and beyond](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.84.1226&rep=rep1&type=pdf) by Williams
- Longer review paper with an introduction to Gaussian processes on a fairly elementary level; [Gaussian processes for machine learning](https://infoscience.epfl.ch/record/161301/files/bayesgp-tut.pdf) by Seeger
