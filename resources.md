## References 

### Algorithms are Biased

* [Turns Out Algorithms Are Racist](https://newrepublic.com/article/144644/turns-algorithms-racist)

   We are at a stage in technology where we need to make wide decisions of how we wish to learn from the past. Do we wish to 
   imitate it or bring about a change. We need to challenge the inequalities that are present in the society. The first stage 
   for this is the design process where the Data Scientist needs to understand which features are making the features bais. 
   One should not let the black box decide and offers pronouncements and that we are encouraged to obey.

* [Algorithms and bias: What lenders need to know](www.whitecase.com/publications/insight/algorithms-and-bias-what-lenders-need-know)

   This article provides a guide on what banks need to consider when using AIs to make decisions regarding lending. It details 
   several main points:

     * AIs learn by using preexisting data that has the desired result already determined through manual means, which is 
     subject to bias.
     * While consumers can view their own credit report and check for its accuracy, there could be data from nontraditional 
     sources which are not available to the consumer to check which lack transarency. This can even go as far as looking at 
     social patterns, such as where a person shops or who they interact with.
     * Recommendations are made that lenders monitor changing regulations and test for potential bias.
     * Any feature in the algorithm should be carefully justified.
     * Algorithms to examine bias in AI algorithms should be developed.

* [WHY AI IS STILL WAITING FOR ITS ETHICS TRANSPLANT](https://www.wired.com/story/why-ai-is-still-waiting-for-its-ethics-transplant/)

  This is an interview of Kate Crawford, a cofounder of AI Now, conducted by WIRED magazine. She is asked several questions 
  which include  the current state of ethics in AI, how AI developers need to both hire people outside of computer science to 
  better understand social implications, and the state of government funding of ethics research under the Trump adminstration.
     
* [The Dark Secret at the Heart of AI](https://www.technologyreview.com/s/604087/the-dark-secret-at-the-heart-of-ai/)

  This article goes into how, even though neural networks and deep learning algorithms have been designed by humans, humanity 
  does not really know how these AIs work. They could use reason or use instinct like real people do. The inherent dangers in 
  the unpredictability of AIs are summarized.

* [How do machines learning algorithms learn bias?](https://towardsdatascience.com/how-do-machine-learning-algorithms-learn-bias-555809a1decb)
   This is an article about how feeding biased data into a machine learning model leads to biases in model predictions.

* [Bias in software to predict future criminals - biased against blacks](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)

### Solutions 

* [Counterfactual Fairness](https://arxiv.org/pdf/1703.06856.pdf)

  Causal models capture social biases and make clear the implicit trade-off between prediction accuracy and fairness in an 
  unfair world.
  
  When is your model fair?
  
     * An algorithm is fair so long as any protected attributes A are not explicitly used in the decision-making process.
  
     * An algorithm is fair if it gives similar predictions to similar individuals.
  
     * A predictor Yˆ satisfies demographic parity if P(Yˆ |A = 0) = P(Yˆ |A = 1)
  
     * A predictor Yˆ satisfies equality of opportunity if P(Yˆ = 1|A = 0, Y = 1) = P(Yˆ = 1|A = 1, Y = 1).


* [How We Examined Racial Discrimination in Auto Insurance Prices](https://www.propublica.org/article/minority-neighborhoods-higher-car-insurance-premiums-methodology)

   As AI becomes more and more complex, it can become difficult for even its own designers understand why it acts the way it 
   does. A nationwide study by the Consumer Federation of America in 2015 found that predominantly African-American 
   neighborhoods pay 70 percent more, on average, for premiums than other areas do. We analyzed aggregate risk data by zip 
   code collected by the insurance commissioners of California, Illinois, Missouri and Texas from insurers in their states.

   * They found that some insurers were charging statistically significantly higher premiums in predominantly minority zip 
   codes, on average, than in similarly risky non-minority zip codes. 

   * Studies of auto insurance rates in Texas found that “drivers in poor and minority communities were disproportionately 
   rejected by standard insurers and forced into the higher cost non-standard” insurance plans that are designed as a last 
   resort for people who can’t otherwise buy insurance.

   Similar statistics were shown in other states as well. Insurance companies fight that it is completely based not risk and 
   they have removed racial features while training their model but demographies are the latent features that are strongly 
   correlated with communities. These latent features bring bais in the model.

* [How I'm Fighting Bias in Algorithms (Ted Talk)](http://www.ted.com/talks/joy_buolamwini_how_i_m_fighting_bias_in_algorithms)


   What if you go to the washroom and the tap does not respond to your hands but it does for your your friend’s. Computer 
   Vision uses images to recognize people and objects. But what if we train it with undiversified dataset[^[1]]. It will only 
   respond to white skin because that is only what it has seen. There have been reported indices when a webcam is not able to 
   detect black faces.[1] Not only this image recognition softwares have been associating cleaning or the kitchen with women, 
   for example and sports with men[^[1]].


	WHO CODES MATTERS? <sup>1</sup>
	HOW WE CODE MATTERS?[ ^ [1]]
	WHY WE CODE MATTERS?[ ^ [1]]

   There needs to be a system that audits the existing software for impact that it has on minorities. There is a need to 
   diversify our data. 
   
   [Here](https://www.ajlunited.org/fight) is a website where you can report discrimination that you’ve faced while using AI

* [Controlling machine learning algorithms and their biases](https://www.mckinsey.com/business-functions/risk/our-insights/controlling-machine-learning-algorithms-and-their-biases) 

* [Attacking Discrimination in ML- google research paper](https://research.google.com/bigpicture/attacking-discrimination-in-ml/)

* [Equality Opportunity](https://drive.google.com/file/d/0B-wQVEjH9yuhanpyQjUwQS1JOTQ/view)

* [Link to White Paper Containing Question Tool](https://cdt.org/issue/privacy-data/digital-decisions/)

### Involved Organizations and Communities

* [AI Now](https://ainowinstitute.org/)

  AI NOW is a research center based out of New York University focusing on the social implications of AI. Their research 
  focuses on studying biases made by AIs that are used to make decisions related to housing, criminal justice, and employment. 
  They also focus on determining the bias in datasets used to train AIs. Finally, they study how to safely integrate AIs into 
  algorithms used by critical infrastructures.

* [AI Now report](https://assets.contentful.com/8wprhhvnpfc0/1A9c3ZTCZa2KEYM64Wsc2a/8636557c5fb14f2b74b2be64c3ce0c78/_AI_Now_Institute_2017_Report_.pdf)

  The AI NOW report summaries several recommendations made by AI NOW in the implementation of AI algorithms for making 
  decisions in hiring, housing, as well as addressing biases in AI research itself. The report also contains a comprehensive 
  literature review summarizing recent work in studying the social implications of AI.

* [DeepMind Ethics Research Group - Google](https://deepmind.com/applied/deepmind-ethics-society/research/)


  DeepMind's Ethics & Society is a research unit within DeepMind that aims to explore and better understand the real-world    
  impacts of AI. It aims to help technologists put ethics into practice and help society anticipate and control the effects 
  of AI, by enlisting some questions around:
  * privacy
  * transparency 
  * fairness 
  * governence and accountability that should be addressed throughout the life cycle of projects. 

* [Why We Launched DeepMind Ethics & Society](https://deepmind.com/blog/why-we-launched-deepmind-ethics-society/)

  Quoting DeepMind's Ethics webpage:
  
  "The development of AI creates important and complex questions. Its impact on society—and on all our lives—is not something    that should be left to chance. Beneficial outcomes and protections against harms must be actively fought for and built-in 
   from the beginning. But in a field as complex as AI, this is easier said than done"
  
  
  DeepMind being the world leader in artificial intelligence research and its application for positive impact, provides clear   motivation and need to include ethics in AI. It is imperative to have similar ethics groups working hand in hand with the     development teams in all organizations. 
   
* [Responsible Data Science](http://www.responsibledatascience.org/)

  Responsible Data Science is a novel collaboration between principal scientists from 11 universities and research institutes 
  in the Netherlands. RDS aims to provide the technology to build in fairness, accuracy, confidentiality, and transparency in 
  systems thus ensuring responsible use without inhibiting the power of data science. They conduct seminars and workshops (so 
  far within Netherlands) and the material is available on their webpage as well. 

* [principles for accountable algorithms](https://www.fatml.org/resources/principles-for-accountable-algorithms)

* [IEEE standards for AI ethics](http://standards.ieee.org/develop/indconn/ec/autonomous_systems.html)

* [Fairness, Accountability, and Transparency in Machine Learning](https://fatconference.org/resources.html)

### Miscellaneous

* [make algorithms accountable](https://www.nytimes.com/2016/08/01/opinion/make-algorithms-accountable.html)

  This is an article about how there needs to be increased transparency and accountability when it comes to examining 
  data used by algorithms. A case of where an algorithm detecting the risk of criminal recidivism was biased against black 
  defendants is established as an example for such a need. The article goes over efforts by the European Union to regulate 
  such algorithms as well as recommendations from the White House on holding such algorithms accountable.

* [IEEE standards for AI ethics](http://standards.ieee.org/develop/indconn/ec/autonomous_systems.html)

  The IEEE has published standards for the ethical application of AI. They are group into these broad categories covering 
  social, privacy, and military impacts:

  * Executive Summary
  * General Principles
  * Embedding Values Into Autonomous Intelligent Systems
  * Methodologies to Guide Ethical Research and Design
  * Safety and Beneficence of Artificial General Intelligence (AGI) and Artificial Superintelligence (ASI)
  * Personal Data and Individual Access Control
  * Reframing Autonomous Weapons Systems
  * Economics/Humanitarian Issues
  * Law

* [Algorithmic accountability](https://techcrunch.com/2017/04/30/algorithmic-accountability/)

* [Partnership in AI](https://www.partnershiponai.org)

* [Book: What Algorithms Want - Ed Finn](https://mitpress.mit.edu/books/what-algorithms-want)

