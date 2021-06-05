My primary research interests lie in several areas:
* [Healthcare applications](#healthcare)
* [Multimodality](#multimodality)
* [Creative language](#creative-language)

&nbsp;  

Below, I provide a brief overview of the ongoing and previous projects in which I've been involved; for additional details, refer to the relevant papers listed (if applicable) or feel free to send me a message.  My recent work has been conducted in UIC's [Natural Language Processing Laboratory](https://nlp.lab.uic.edu/), which I co-direct.  Most of my earlier research was conducted in UNT's [Human Intelligence and Language Technologies Laboratory](http://hilt.cse.unt.edu/).

&nbsp;  

---

&nbsp;  

### Healthcare Applications {#healthcare}

My work at the intersection of natural language processing and healthcare has to date focused on cognitive assessment and support, as well as (more recently) identification and analysis of health-related behavior.  My current and past collaborators in this area include researchers from UIC, UI Health, the University of California, San Diego, and the University of North Texas.
&nbsp;  
&nbsp;  

In my group's work towards automated cognitive assessment, we have developed feature-based and deep learning approaches for course- and fine-grained dementia detection, predicting both general Alzheimer's disease or related dementia (ADRD) status and Mini Mental State Examination (MMSE) scores based on participants' linguistic patterns in their transcribed speech samples.  Some of our recent publications in this area include:
* Shahla Farzana and Natalie Parde. [Exploring MMSE Score Prediction Using Verbal and Non-Verbal Cues](http://www.interspeech2020.org/uploadfile/pdf/Wed-SS-1-6-11.pdf). In the *Proceedings of the 21st Conference of the International Speech Communication Association (INTERSPEECH 2020)*. Shanghai, China, October 25-29, 2020.
* Shahla Farzana, Mina Valizadeh, and Natalie Parde. [Modeling Dialogue in Conversational Cognitive Health Screening Interviews](http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.147.pdf). In the *Proceedings of the 12th International Conference on Language Resources and Evaluation (LREC 2020)*. Marseilles, France, May 11-16, 2020.
* Flavio Di Palo and Natalie Parde. [Enriching Neural Models with Targeted Features for Dementia Detection](https://www.aclweb.org/anthology/P19-2042.pdf). In the *Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, Student Research Workshop (ACL SRW 2019)*. Florence, Italy, July 28-August 2, 2019.

&nbsp;  
&nbsp;  

<p align="center">
    <img src="/images/projects/reading-with-robots.png" alt="A robot sitting on a couch, reading a book." width="300" />
</p>

In my earlier work towards providing cognitive health support, I developed a human-robot book discussion system, implemented using NAO robots.  The robots processed fiction literature and generated questions about the novel uses of figurative language within, which they then posed to their human conversation partners.  Some publications regarding this project include:
* Natalie Parde and Rodney D. Nielsen. [AI Meets Austen: Towards Human-Robot Discussions of Literary Metaphor](https://link.springer.com/chapter/10.1007/978-3-030-23207-8_40). In the *Proceedings of the 20th International Conference on Artificial Intelligence in Education (AIED 2019)*. Chicago, Illinois, June 25-29, 2019.
* Natalie Parde and Rodney D. Nielsen. [User Perceptions of a Conversational Robot Interface](http://www.natalieparde.com/papers/parde_speechchi.pdf). In the *Proceedings of the CHI 2019 Workshop on Mapping Theoretical and Methodological Perspectives for Understanding Speech Interface Interactions (SpeechCHI 2019)*. Glasgow, United Kingdom, May 5, 2019.
* Natalie Parde and Rodney D. Nielsen. [Automatically Generating Questions about Novel Metaphors in Literature](http://www.aclweb.org/anthology/W18-6533). In the *Proceedings of the 11th International Conference on Natural Language Generation (INLG 2018)*. Tilburg, The Netherlands, November 5-8, 2018.
* Natalie Parde. [Reading with Robots: Towards a Human-Robot Book Discussion System for Elderly Adults](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16173/16438). In the *Proceedings of the Thirty-Second AAAI Conference on Artificial Intelligence (AAAI 2018) Doctoral Consortium*. New Orleans, Lousiana, February 2-7, 2018.

&nbsp;  
&nbsp;  

<table>
  <thead>
    <tr>
      <th style="text-align: left">Class</th>
      <th style="text-align: left">Example</th>
      <th style="text-align: left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #f4f5f6;">
      <td style="text-align: left">No SD</td>
      <td style="text-align: left">1) <em>I wish you all the strength x.</em> <br /> 2) <em>Cheers and happy new year!</em></td>
      <td style="text-align: left">No disclosure of medical issue.</td>
    </tr>
    <tr>
      <td style="text-align: left">Possible SD</td>
      <td style="text-align: left">1) <em>I’m not angry, I’m not even sad as such, I’m just tired…</em> <br /> 2) <em>I do think my rib pain is from bad posture. I have worked at a computer for years.</em></td>
      <td style="text-align: left">General, non-specific mention of or allusion to medical issue.</td>
    </tr>
    <tr style="background-color: #f4f5f6;">
      <td style="text-align: left">Clear SD</td>
      <td style="text-align: left">1) <em>Metoprolol gave me the most horrendous headaches, so I had my doctor take me off.</em> <br /> 2) <em>I did the ultrasound a couple times now since this started 2 yrs ago I’d like to find a good ortho doc.</em></td>
      <td style="text-align: left">Clear disclosure of specific symptom, diagnosis, and/or treatment.</td>
    </tr>
  </tbody>
</table>

Very recently, my research group has begun to explore self-disclosure behavior in the context of healthcare support.  We created a dataset of health-related posts from online forums, annotated for self-disclosure status, and performed a series of experiments to establish a performance benchmark for this task.  A publication on this project, including details for accessing the dataset, can be found here:
* Mina Valizadeh, Pardis Ranjbar-Noiey, Cornelia Caragea, and Natalie Parde. [Identifying Medical Self-Disclosure in Online Communities](https://www.aclweb.org/anthology/2021.naacl-main.347.pdf). In the *Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (NAACL 2021)*. Online, June 6-11, 2021.

&nbsp;  

---

&nbsp;  

### Multimodality {#multimodality}

My work in multimodal natural language processing has primarily centered on language and vision.  One interesting thread of work investigated by my research group is the task of visual storytelling, in which natural language stories are generated for sequences of images.  A paper addressing this topic can be found here:
* Yatri Modi and Natalie Parde. [The Steep Road to Happily Ever After: An Analysis of Current Visual Storytelling Models](https://www.aclweb.org/anthology/W19-1805). In the *Proceedings of the NAACL 2019 Workshop on Shortcomings in Vision and Language (SiVL 2019)*. Minneapolis, Minnesota, June 6, 2019.

&nbsp;  
&nbsp;  

<p align="center">
    <img src="/images/projects/i-spy.png" alt="A robot standing in front of a white surface containing a variety of household objects." width="300" />
</p>

In my earlier work, I focused on grounded language learning, which seeks to model language leveraging non-linguistic experience in additional to more traditionally-examined word co-occurrence.  I implemented a human-robot guessing game using NAO robots that facilitated language learning through interactive gameplay.  Some publications regarding this project include:
* Natalie Parde, Adam Hair, Michalis Papakostas, Konstantinos Tsiakas, Maria Dagioglou, Vangelis Karkaletsis, and Rodney D. Nielsen. [Grounding the Meaning of Words through Vision and Interactive Gameplay](https://www.ijcai.org/Proceedings/15/Papers/269.pdf). In *Proceedings of the 2015 International Joint Conference on Artificial Intelligence (IJCAI 2015)*, Buenos Aires, Argentina, July 25-31, 2015.
* Natalie Parde, Michalis Papakostas, Konstantinos Tsiakas, and Rodney D. Nielsen. ["Is It Rectangular?" Using I Spy as an Interactive, Game-Based Approach to Multimodal Robot Learning](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/viewFile/9565/9727). In *Proceedings of the AAAI-15 Conference on Artificial Intelligence Student Program*, Austin, Texas, January 25-30, 2015.
* Natalie Parde, Michalis Papakostas, Konstantinos Tsiakas, Maria Dagioglou, Vangelis Karkaletsis, and Rodney D. Nielsen. [I Spy: An Interactive Game-Based Approach to Multimodal Robot Learning](https://www.aaai.org/ocs/index.php/WS/AAAIW15/paper/view/10074/10210). In *Proceedings of the AAAI-15 Workshop on Knowledge, Skill, and Behavior Transfer in Autonomous Robots*, Austin, Texas, January 25, 2015.

&nbsp;

---

&nbsp;

### Creative Language {#creative-language}

My work on creative language has primarily focused on metaphor and sarcasm processing.  In the context of metaphor processing, I have specifically examined automated detection of metaphor novelty---that is, the distinction between conventionalized and novel metaphor usage.  I created a large, publicly available dataset of syntactically-related word pairs labeled for metaphor novelty on a continuous scale, and performed a series of experiments to establish proof-of-concept for the task as well as a performance benchmark.  Some publications regarding this work include the following:
* Natalie Parde and Rodney D. Nielsen. [A Corpus of Metaphor Novelty Scores for Syntactically-Related Word Pairs](http://www.lrec-conf.org/proceedings/lrec2018/pdf/242.pdf). In the *Proceedings of the 11th International Conference on Language Resources and Evaluation (LREC 2018)*. Miyazaki, Japan, May 7-12, 2018.
* Natalie Parde and Rodney D. Nielsen. [Exploring the Terrain of Metaphor Novelty: A Regression-based Approach for Automatically Scoring Metaphors](https://ojs.aaai.org/index.php/AAAI/article/view/11940). In the *Proceedings of the Thirty-Second AAAI Conference on Artificial Intelligence (AAAI 2018)*. New Orleans, Louisiana, February 2-7, 2018. 
* Natalie Parde and Rodney D. Nielsen. [Finding Patterns in Noisy Crowds: Regression-based Annotation Aggregation for Crowdsourced Data](http://www.aclweb.org/anthology/D17-1204). In the *Proceedings of the Conference on Empirical Methods in Natural Language Processing (EMNLP 2017)*. Copenhagen, Denmark, September 7-11, 2017.

&nbsp;  
&nbsp;  

In my work on sarcasm detection, I developed a domain-general approach that distinguished between sarcasm and other forms of emotional communication in Twitter and Amazon product reviews.  Some papers describing this work include:
* Natalie Parde and Rodney D. Nielsen. [Detecting Sarcasm is Extremely Easy ;-)](https://www.aclweb.org/anthology/W18-1303.pdf). In the *Proceedings of the NAACL 2018 Workshop on Computational Semantics Beyond Events and Roles (SemBEaR 2018)*. New Orleans, Louisiana, June 5, 2018. 
* Natalie Parde and Rodney D. Nielsen. [#SarcasmDetection is soooo general! Towards a Domain-Independent Approach for Detecting Sarcasm](https://www.aaai.org/ocs/index.php/FLAIRS/FLAIRS17/paper/download/15421/14939). In *Proceedings of the 30th International FLAIRS Conference (FLAIRS 2017)*. Marco Island, Florida, May 22-24, 2017.

&nbsp;

---

&nbsp;

### Other Prior Research

In addition to my main areas of interest, I have previously collaborated with cybersecurity and cognitive science researchers on several projects.  My research group has conducted a small amount of work on video generation, and as an undergraduate I was part of the team developing [UNTANGLED](https://untangled3.unt.edu/home.php), an award-winning online game that sought to harness human intuition to solve real-world hardware mapping problems by abstracting them as puzzles.  More details about all of these projects can be found on my publications page.
