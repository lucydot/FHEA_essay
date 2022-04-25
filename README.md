# FHEA essay (Lucy Whalley) 

## Introduction

In 2011 I started a PGCE in post-compulsory education and training. My PGCE was a little unusual as I trained in HMP Birmingham, an adult male category-B prison. The students in my numeracy class were a varied bunch, including men in later age who had not been in education for decades and men receiving opiate substitute treatment. The common thread running through almost all of my students was a lack of confidence in their ability - a feeling that they "cannot do mathematics". Later, working as a primary school mathematics teacher in Sparkbrook (one of the most deprived wards in Birmingham), I supported students who had already developed a similar lack of confidence in maths.

Fast-forward to 2019 and I am teaching computational skills to PhD researchers and staff at Imperial College London. Despite the difference in circumstance - these students are pursuing the highlest level of education at a prestigious university - I notice the same attitude. A nervousness in the classroom, a reluctance to answer questions, and apologies for asking "silly" questions (if asking them at all).

This observation, built gradually over 10 years of teaching, underpins my work as a lecturer now: my planning, delivery and assessment are designed to build student self-confidence and the belief that they can succeed in a discipline labelled by society as "difficult".

## Computational skills for a digital age [A1]

I am teaching the "Theory and Computation" component of an undergraduate module (KD5081) on the Physics and Physics with Astrophysics degree programmes, as this combines both my teaching expertise (mathematics and computational skills) and my research area (computational physics). Coursework results the previous year were poor, with an average student mark in the low 40s, and a significant minority of students submitting no work. This was the first year of Covid, which impacted on teaching and learning in various ways. For example, there was a sudden move to online learning, and increased stress levels for a proportion of our students. (K1/V4)

I requested that I build the course around the programming language Python, rather than the Matlab used in previous years, as Python is a more general-purpose language that is transferable to other academic disciplines and software careers. I worked with the Head of Subject for Physics to check that this switch would be workable within the context of the
 wider degree programme. The changes did not require University approval as they still fit within the module specification. (K1/V4)
 
Through discussion with the previous course instructor I established that a key challenge is the breadth of students' previous experience in programming; some students have related school-level qualifications, whilst others have no experience of programming. The second challenge is timing - students need to quickly learn how to analyse and plot data to support their experimental work, and all of the assessed content must be introduced before the coursework is set during teaching week 7. With these factors in mind I split the course into three parts: "Getting Started", "Getting Results", and "Getting it Out There". (V1/V2/K1/K2)

"Getting Started" covers the foundational concepts and introductory skills needed for scientific programming, including basic data analysis and plotting, reading documentation, and guidance on good coding style. "Getting Results" introduces a range of numerical methods and combines these with the skills developed in "Getting Started" to model physical systems using differential equations. "Getting it Out There" introduces the tools needed for sharing code with other people (writing documentation, software testing and version control). This part of the course is unassessed, however earlier topics from "Getting Started" are interleaved to re-inforce learning [Lang2021]. (K1/K3)

To develop course content I use backward design: using the course goals and summative assessment to inform design of the formative assessment, all of which are then used to design the tutorials and learning objectives [McTighe2013]. This design process is encouraged by the university moderation procedures that require all assessments to be submitted well in advance of course start. (K2/K6/V3)

The course content is designed to be "continuously incrementally useful to the learner" [Wilson2021]. For example, in the second lab students calculate the height of a satellite by translating a mathematical expression to code. In the third lab they combine this skill with data parsing to analyse experimental data. In the fourth lab they learn how to write simple tests to assert that their written code is correct. This all builds towards the end of the course where students document and publish the code they have written on a simple website. There is emphasis on computing skills that are transferable to other disciplines and industry, in response to "the onus on academia to make sure that physics departments are providing the specialist and transferable skills that graduates need and employers seek" [Ryan2020]. (K3/V3/V4)

## Practising what we preach: using the latest technologies to support teaching and learning [A4]

Blackboard (the preferred platform at Northumbria) does not have some of the features needed for teaching programming, including syntax highlighting or the ability to hide/show code blocks. Instead I developed a website with these features to host course content (https://nu-cem.github.io/CompPhys). The website ensures that all materials are in one place and are available in advance of, during and after teaching - this is particularly important for students with additional learning needs. It is also "Covid proof" in that the resources can be delivered in-person or remotely. However I advocated for this teaching to be timetabled as in- person, given the key role peer-to-peer and one-to-one interaction plays in learning [Biggs2011], and the barriers to facilitating this online. (K2/K3/K4/V1/V2/V3/V4)

New programming tools have transformed computing in academia and industry over the last decade. I incorporate these technologies into my teaching so that students are better equipped for further study or employment. For example, I use the Github service (https://github.com/) to host the course website and Jupyter Notebooks (https://jupyter.org/) to write tutorials. These notebooks (a type of electronic lab-book) bring an additional learning curve that I judge to be worthwhile as they provide opportunities for code narration and, as a result, more robust and maintainable code [Knuth1992]. (K1/K2/K3/K4/V3/V4)

Given the range of student socio-economic backgrounds at Northumbria [OfS2020], I ensure that the students are able to participate using their own laptop or a university-provided desktop computer. The latter provides a challenge as I have to work with university IT to ensure that the relevant software is installed and tested on the faculty computers. In addition, due to the teaching methods I use (see below), the computer labs must have all students facing the front of the class. This is not a common setup at Northumbria as the majority of computer labs seem to be setup with small group work in mind. (V1/V2)

## Active and responsive teaching [A2/A4]

To work through the content of each class tutorial I use live coding, which has been established as the most effective way to teach programming [Rubin2013]. I write code at the front of the class, whilst students follow along on, typing and running the same code on their own computers. Live coding has several advantages over using slides including: i) allowing me to adjust teaching in response to student questions or unexpected events such as fire drills; ii) making me more aware of the quantity and speed of information being transferred; iii) more scaffolded support, with students writing code as a group before writing code in a pair or independently. (K2/K3/V3)

Another key advantage of this teaching method is that students learn how to diagnose and correct the inevitable mistakes I make whilst teaching; my favourite moments in class are when I make a mistake and the students jump in to fix it, calling out where the problem is and guessing at a solution. De-bugging is a key aspect of programming and so this forms an effective route for unintended knowledge transfer. It also normalises making mistakes and may give students more confidence when tackling similar challenges in their own code. (K3,V3)
   
To re-inforce the sense of collaboration I encourage students to suggest course improvements or report any website errors using the Github issues interface (https://github.com/NU-CEM/CompPhys/issues). In contrast, a more traditional "fixed" teaching resource such as a pdf does not lend itself to the on-going and iterative process of co-creation. I also invite students to talk us through a piece of code they have written at the front of the class, an example of collaborative learning that can improve student attainment through an increased sense of community and belonging [Beck2013]. My mentor observed this practice and noted it as "unusual", as in his experience students are not willing to be put on the spot. I believe that my efforts to normalise mistakes contributes to the success of this activity. (K2/K3/K4)
 
## Assessment for learning [A3/A4]

I use various forms of formative evaluation to assess student learning and guide my teaching, structuring each lab so that the students have opportunities to learn effectively through "appropriate and focused feedback early and often" [Cross1993]. (K3/V3)

To assess subject matter learning whilst live coding I display short questions for pair discussion, which is then followed by a quick class discussion. This enables me to identify and counter any misconceptions at an early stage. I also use post-its as a quick way to assess student understanding - students stick a green-for-go post-it on their computer if they are following the content or a red-to-stop post-it if they have fallen behind. I find that most students are more willing to use a red post-it than raise their hand. However the green post- its are used inconsistently if at all - this discrepancy might be because students are not used to affirming their understanding in class, whilst asking for help is more normalised. (K2/K3)

To recall the basic facts and practice the basic skills introduced in each tutorial I provide "quick-test" questions. These include multiple choice questions designed to identify misconceptions, "Parsons problems" in which learners are given jumbled lines of code, and fill-the-gap questions. The questions are suited to the beginner programmer who can find writing code from scratch an intimidating task [Parsons2006]. (K2/K3/V3)

To assess higher-level thinking as defined by Bloom's taxonomy (application and analysis) [Bloom1956] I provide a set of more extended activites for each lab session, alongside extension activities for those who are progressing at the fastest pace. These require students to write their own code, with some designed to produce a "digital artifact" that can be used (when combined with the relevant physics knowledge) for self-assessment. For example, in one task students are asked to simulate and plot the motion of a non-linear pendulum. From inspection of the resulting plot a physics student can then judge if the simulation is correct. I also encourage the students to self-assess via experimentation - for example, adjusting the mass of the pendulum and monitoring what impact this has on motion. This experimentation is enabled by the highly interactive nature of the Jupyter Notebooks. (K2/K3/K4/V3)
 
For all formative assessments I encourage students to use pair programming where one student "drives" (writes code), whilst the other "navigates" (suggests strategies and spots errors). This is shown to improve student outcomes as it enables peer-support and collaboration [Beck2013]. Whilst the students are completing the formative assessments I provide 1:1 or small group support, starting at the back of the computer lab to prioritise those who might be trying to hide. I have found this to be highly effective: re-focusing students who have disengaged and providing encouragement to those with less confidence. This is the part of teaching I have tried, but failed, to replicate when teaching online, with breakout rooms making some students less inclined to interact. (K2/K3/V3)

## Assessment of learning [A3/A4]

I have found facilitating summative coursework the most challenging aspect of teaching. Perhaps I should not find this surprising as i) I have not co-ordinated similar assessments earlier in my teaching career; ii) there is a challenge in designing coursework that differentiates student learning (with an average mark around 50%) and maintains student motivation.

To develop the formative assessments I used the module descriptor and coursework questions from previous years as a starting point. This ensures that student attainment can be demonstrated at a level suitable for degree accreditation by the Institute of Physics.

At Level 5 (L5) I made two key changes to the coursework whilst keeping the mathematical context underlying the coursework largely the same. Firstly, I give marks for "code style" as effective variable names, comments and code structure underly success in any computational discipline and form a key learning goal for the course. Secondly, I make the relatively advanced mathematics more accessible by i) relating it to an everyday experience (making salad dressing) [Ambrose2010] and ii) developing a visual representation of the problem (an animation) [Buckley2020]. (K2/K3/K6)

The response from students was mixed. In one email a student wrote "The assessment looks great!" whilst another student commented "I had a heart attack when I saw the coursework". In response to emails asking for further support I arrange additional drop-in sessions to respond to any queries. For those who cannot attend for various reasons I invite questions in advance, summarise our discussion in a Jupyter Notebook, and publish this via Blackboard announcements. (V1/K4)
The L5 coursework had a negative "backwash effect" [Biggs2011] on teaching and learning as students prioritised their coursework above the new material being covered in the unassessed "Getting it out there" section of the course. Attendance dropped from around 25 students to around 5 students. I had underestimated the importance given to summative assessment; in future years I will re-focus this final third of the course so that it more directly re-inforces and builds on the learning from the second (assessed) part of the course. (V3)

## Open Source communities of practice [A5]

My continuing professional development as an educator and researcher owes much to the communities of practice [Wenger1998] in which I participate.

The Carpentries (https://carpentries.org/) is an international volunteer project dedicated to teaching basic computing skills to researchers. In 2019 I completed my Software Carpentry Instructor training and I continue to deliver training, most recently to librarians in the NHS. We deliver the training as a team: this allows me to work with, and learn from, other instructors from across the UK. To follow international developments I attend the biennial CarpentryCon conference and read the stready-stream of publications from The Carpentries community members [e.g. Wilson2017,Wilson2020]. The Software Sustainability Institute (SSI, https://www.software.ac.uk/) is summarised through its motto "Better Software, Better Research". I won a competitive SSI fellowship in 2019 and am using this to develop education resources for researchers who want to publish their research software. This includes working with the CodeRefinery (https://coderefinery.org/), which has impacted my undergraduate teaching as I have incorporated elements of their training resources into my teaching. In exchange I have had a little influence on their instructor training programme (https://coderefinery.github.io/instructor-training/welcome/). (V3/K3)

Software Carpentry and the SSI are strong proponents of open source software and open education. I follow the same philosophy, openly developing all of my teaching resources (https://lucydot.github.io/teaching/) and making them available to other for re-mix and re-use via a Creative Commons license. I promote these resources via social media; an online tool I developed for student self-assessment has engaged educators from the UK, US and India (https://bit.ly/3zmuqmw). I work openly so that I can build on the work of others, rather than re-inventing the wheel, and so that my teaching resources are more sustainable over the long-term. This view is informed by my software development practice; when other researchers use my software I receive valuable feedback that improves the software over time - I hope that the same will happen as my teaching resources evolve. (K2/V2/V4)

These networks have been particularly useful as they have improved my pedagogical content knowledge - they have guided me not only in my general teaching (for example, using post-its for assessment), but in my teaching of computational skills specifically (for example, using live coding). This is particularly useful as I am working in a field (computational science) that is in it's infancy when compared to more established domains, yet growing at incredible speed [Rude2014].

The POSS scheme has been valuable for understanding the policies, procedures and technologies that are specific to Northumbria. For example, my peer partner teaches in hybrid format, with some students on-campus and some in China. I was not confident using the technologies that faciliate this (Blackboard and Panopto); as a result of our peer discussion I am now better prepared if my own teaching is moved online [K4]. Meetings with my mentor have allowed me to place my teaching in the larger framework of the physics degree programmes, and guided me through the exam moderation procedures on e-vision. (K4/K6)

Student feedback for my teaching has been positive. The student reps reported in a meeting that "Computational part is going well and good lectures" and that "the website for the computational course content is quite a unique approach and very helpful". I am encouraged by students who have asked for further engagement: one student has asked to work with me on a summer project, and the students at L4 have requested that I run an optional Python seminar series through the spring term.

## Mini case-study: "I know I'm being stupid" - improving student attitudes to programming [A2/A4]

Many students have a negative attitude towards programming, and both my teaching experience and the literature suggests that lack of confidence is a particular barrier [Wilson2019]. This is a gendered problem as "women with prior exposure [to programming] outperformed their male peers in all areas of introductory programming courses, but were consistently less confident in their abilities" [Wilcox2018]. This is re-inforced by my classroom experience; I have noticed that women are particularly apologetic when asking for support (despite invites to do just this), qualifying their requests with phrases such as "sorry to ask this" or "I know I'm being stupid". (V3)

I have observed on various occassions how installation problems can de-motivate students at the important early stage of a course [Wilson2019], and that this effect can be even more stark when teaching a short course as a significant proportion of time might be spent fixing installation problems rather than demonstrating the utility and excitement of programming. To help improve student attitudes towards programming I provided an online environment via the Binder service (https://mybinder.org/) for L4 students taking my 8-hour "Programming in Python" introductory course (https://lucydot.github.io/python_novice/). The Binder environment allows students to run through the tutorials on their web browser without installing any software. (V2/V3/K4)

I used a Likert questionnaire at the beginning and end of the course to measure the change in student attitudes. This was adapted from a similar questionnaire reported in the literature [Menke2020]. The individual questions are formed from word pairs for response to this prompt: "using computers for physics is....". For example, students would choose between "uncomfortable" and "comfortable" using a 1 (uncomfortable) - 7 (comfortable) scale. Cohen's standardised mean difference (CSMD) can be used to quantify the change in attitude. In this case there appears to be little and conflicting changes in attitude toward using computers for physics: there is a positive shift towards "easy", "good", "attractive" and "worthwhile" and a negative shift towards "worthless", "complicated", "confusing", "frustrating" and "unpleasant". These are either medium (CSMD between 0.5 and 0.8) or small (CSMD between 0.2 and 0.5) shifts. There were no large (CSMD more than 0.8) shifts and the majority of questions suggest that there is no shift in attitude. A more extensive analysis is available online (https://github.com/lucydot/changing_attitudes/blob/main/Likert\_analysis.ipynb). Whilst disappointing, these results may be expected given that the course is only 8-hours long. I plan to use the same questionnaire with the same students on the full term Computational Physics course in Autumn 2022. (V3/K5)

Word count: 3289 

## References

- [Lang2021] James M. Lang. Small Teaching. Jossey-Bass (2021). ISBN: 978-1118944493. Interleaving is discussed in Chapter 3.
- [McTighe2013] Jay McTighe and Grant Wiggins. Understanding by Design Framework. Association for Supervision & Curriculum Development (2013). ISBN: 978-1-4166-0035-0.
- [Wilson2021] Greg Wilson. The Essence of Teaching. Blog post (2021). https://third- bit.com/2021/01/27/essence-of-teaching/ (accessed on 30/12/2021).
- [Ryan2020] Sean Ryan and Veronica Benson. Closing the Skills Gap. Institute of Physics (2020). https://physicsworld.com/a/closing-the-skills-gap/ (accessed on 30/12/2021).
- [Biggs2011] John Biggs and Catherine Tang. Teaching for Quality Learning at University. (2011). ISBN: 978-0335211692. Social learning is discussed in Chapter 4, the "Backwash effect" is discussed in Chapter 10.
- [Knuth1992] Donald Knuth. Literate Programming. Center for the Study of Language and Information (1992). ISBN: 0937073806.
- [OfS2020] Northumbria University Northumbria University Access and Participation Plan. Web page (2020). https://northumbria-cdn.azureedge.net/- /media/universityofnorthumbriaatnewcastleapp2020-21_finalofsapproval.pdf (accessed on 2/1/2022). Statistics showing that lower socio-economic groups are better represented at Northumbria University (compared to other universtities) are on page 2.
- [Rubin2013] Marc J. Rubin. The Effectiveness of Live-coding to Teach Introductory Programming. In 2013 Technical Symposium of Computer Science Education (2013). https://doi.org/10.1145/2445196.2445388.
- [Beck2013] Leland Beck and Alexander Chizhik. Cooperative Learning Instructional methods for CS1: Design, Implementation and Evaluation. In ACM Transations on Computing Education (2013). https://doi.org/10.1145/2492686.
- [Cross1993] Patricia Cross and Thomas A. Angelo. Classroom Assessment Techniques. Wiley (1993). ISBN: 978-1555425005. The quote is taken from the third of seven assumptions outlined in the book.
- [Parsons2006] Dale Parsons and Patricia Haden. Parson's Programming Puzzles: A Fun and Effective Learning Tool for First Programming Courses. In 2006 Australasian Conference on Computing Education (2006). https://dl.acm.org/doi/10.5555/1151869.1151890.
- [Bloom1956] Benjamin S. Bloom. Taxonomy of Educational Objectives, Handbook I: The Cognitive Domain. David McKay (1956). ISBN: 978-0582280106
- [Ambrose2010] Susan A. Ambrose et al. How Learning Works. Jossey-Bass (2010). ISBN: 978-0470484104. Students' prior knowledge and experience as a tool (and hindrance) for learning is discussed in Chapter 1.
- [Buckley2020] Charles Buckley and Chrissi Nerantzi Effective Use of Visual Representation in Research and Teaching within Higher Education, In International Journal of Management and Applied Research (2020). https://doi.org/10.18646/2056.73.20-014.
- [Wilson2017] Greg Wilson et al. Good Enough Practices in Scientific Computing. In PLOS Computational Biology (2017). https://doi.org/10.1371/journal.pcbi.1005510.
- [Wilson2019] Greg Wilson. Teaching Tech Together. Taylor and Francis (2019). https://teachtogether.tech/en/. The impact of installation problems is discussed in Chapter 10.
- [Wenger1998] Etienne Wenger. Communities of practice: Learning, meaning, and identity . Cambridge University Press (1998). https://doi.org/10.1017/CBO9780511803932.
- [Rude2018] Ulrich Rude et al. Research and Education in Computational Science and Engineering. In Society for Industrial and Applied Mathematics (2018). https://doi.org/10.1137/16M1096840.
- [Wilcox2018] Chris Wilcox and Albert Lionelle: Quantifying the Benefits of Prior Programming Experience in an Introductory Computer Science Course. In 2018 Technical Symposium on Computer Science Education (2018). https://doi.org/10.1145/3159450.3159480.
- [Menke2020] Erik J. Menke. Series of Jupyter Notebooks Using Python for an Analytical Chemistry Course. In Journal of Chemical Education(2020). https://doi.org/10.1021/acs.jchemed.9b01131.
       
 
