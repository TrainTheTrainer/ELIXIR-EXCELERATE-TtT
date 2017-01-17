#ELIXIR – EXCELERATE Train-the Trainer subtask

## Session 3: Session, course, and materials design

* [Training session design and plan;](#sessions)
* [From session to course design;](#design)
* [Training rooms for Bioinformatics, Reproducibility of training environments;](#rooms)
* [Training materials: designing, producing, delivering;](#mat1)
* [Training materials: Archival; Sharing; Making re-use possible;](#mat1)
* [Training materials repositories and resources: GOBLET, TeSS, GitHub, etc.](#mat1)
* [Preparatory steps for training delivery;](#preparatory)

In this session you will learn how to:

- design, prepare, deliver, get feedback, and review (according to feedback) a three-minute presentation;
- design a training session;
- design a training course;
- design and develop training materials;

## Concept maps

> From Ambrose et al (2010) "How learning works" - Appendix B
> 
> Concept maps are graphical tools for organising and representing knowledge (Novak and Cañas, 2008, "Theory underlying concept maps and how to construct them"). They are drawn as nodes and links in a network structure in which nodes represent concepts, usually enclosed in circles or boxes, and links represent relationships, usuallin indicatesd by lines drawn between two associate nodes. Words on the line, referred to as linking words or linking phrases, specify the relationship between the two concepts.
> Both your students and you can benefit from the construction of concept maps. You can ask students to draw concept maps to get insight into what they already know and how they represent their knowledge. You can then use that information to direct your teaching. You can also use concept map to design a talk, a lesson, a session or even an entire course.
> 
> The ["Theory underlying concept maps and how to construct them"](http://cmap.ihmc.us/Publications/ResearchPapers/TheoryUnderlyingConceptMaps.pdf) ([PDF](./docs/TheoryUnderlyingConceptMaps.pdf)) by Novak and Cañas is an excellent document to read if you want to know more about concept maps and learn how to construct them.
> 
> We cite from this Novak and Cañas:
> 
> The  starting  point   for  constructing  a  concept   map   can  consist  of  only  the   *focus  question*. It is important that a question be given (e.g. "What is the structure of the Universe?" and not just a topic (e.g. “make a concept map about the Universe”) since  answering  the  question  helps focus on your map. 
> 
>  A second step for the  construction of the concept map can be a  list of concepts  that  you want to  definitely include  in  your  map.  We  refer  to  a  list  of  concept  waiting  to  be  added  to  a  concept   map  as  the  parking  lot of concepts. 
> 
> **The beginning of a concept map with a focus question and a parking lot with concepts to be included in the map:**
> 
> 
> ![focus session and parking lot](fig/concept-map-parking-lot.tiff)
> 
> **An expert skeleton concept map**<br>
> The concept map deals with a key concept that needs to be understood as a foundation for learning science. It is based on the parking lot from the previous figure. Some comcepts were left in the parking lot for subsequent addition.
> 
> ![focus session and parking lot](fig/concept-map.tiff)


## Design of a three-minute presentation

- Choose a topic you think you can teach in three minutes. This can be **any** topic (how to make an origami bird, introduction to biochemistry, how bats recognise the presence of obstacles, the second law of Newton, how to draw a comic strip, etc);
- Set a learning goal and a learning outcome for your mini-session;
- Identify the target audience and prerequisites;
- Draw a concept map for your mini-session;
- Think if you want to make your presentation active and interactive (if you are going to teach how two draw, e.g., a stylised bicycle, you might want learners to do it while you show them how to do it);
- Think whether you need or want to use a visual support (e.g. slides/video/pictures/a web page);
- Think whether you need to distribute some material in advance to the audience (e.g. if you are teaching how to make an origami item, you might want provide learners with sheets of paper);
- Sketch the structure of your presentation (e.g., 40 secs introduction/2 mins on topic/20 secs conclusion);

> ## Challenge

> - You will be split into groups of 3 or 4;
> - Make sure your group has a laptop and a phone which can record video;
> - You need to each deliver your 3 minute session to the others;
> - One person delivers the session;
> - One person records on the phone;
> - One person notes down comments real-time;
> - You then provide feedback to each individual, and give your own comments on your delivery;
> - You then have time to revise your session, before delivering to the whole group.


<a name="sessions"></a>
## From a mini-session to an actual session design and plan

* Set learning objectives;
* Set learning outcomes;
* Identify the ideal target audience;
* Identify the required prior knowledge;
* Draw a concept map of the session's topic;
* Decide how much time to allocate for each activity and prepare an outline;
* Decide the order of activities;
* Try to include at least a warm-up session, a short lecture, a practical or group activity, and a wrap-up.

**Warm-up** <br>
Describe clearly your learning objectives and the expected outcomes. Describe what you are going to teach and how it relates to previous topics (if any).
Warm-ups may include an activity learners carry out. For example, solving an exercise, answering a small questionnaire, or making a prediction game. 

Purpose: activate prior knowledge, prepare the brain to learn, introduce a topic.

**Lecture** <br>
This is where you can transfer content. Have very clear learning objectives. Try to make it as interactive as possible. Consider using a short video, capturing images, appropriate citations, making examples from real life. 

**Practical or group activity**<br>
This could be a hands-on or a tutorial, one or more exercises, an instructional game, any group activity.
Allocate enough time to complete the assignment and be ready to allocate extra time if necessary. 
Show the solution of the exercises, or - even better - ask one or more learners to show it to the class.  

**Wrap-up**<br>
The wrap-uo can be used to repeat the main concepts illustrated during the teaching. This should be preferably done by learners. 
It can also be used to assess learning outcomes (for example using a questionnaire with questions similar to the questions of the warm-up questionnaire, or any other test).
In a course wrap-up, you can also assess learners' expectations and collect feedback from them.

Your plan for 1h15 session may look like this:

|Time|Activity|Description|Goal/Outcome|
|------|-------|-----------------------------|----------------|
|9.00-9.15|warm-up|Learners summarise the key points of each session from the previous day and answer questions from the audience. The instructor describes the plan of the day in detail.|Retrieval from memory, repetition, get prepared for new topics, expose learners|
|9.15-9.25|lecture|Python functions|Learning to write a function, about function input and output, and how to call a function.|
|9.20-10.00|practical activity|Two exercises two be solved in pairs on a single computer. After solving the first exercise, the "driver" and the "navigator" will swap. Two learners (one per exercise) will display their solutions to the audience. Questions and discussion.|Learners will be able to write and call a function calculating the distance between two points in the 3D space and a function taking the base and height of a triangle as input and returning its area.|
|10.00-10.15|wrap-up|Group test on functions (match input and output with specific functions; fill gaps in pieces of code). Game: repetition using ball throwing.|Assess learning. Do we need to work more on functions? Repeat meaning and usage of all Python objects introduced so far.|


> ## Challenge

> In your group…
> 
> - Take one session idea and expand to a “real” training session
> - You will need to:
>   - Identify target audience
>   - Define session structure (include indicative content, length, breakdown and timings)
>   - Set learning objectives and outcomes
>   - Decide learning activities  
>   - Suggest how you will assess trainee progress
> - Tell us anything else you think we need to know….


##Training material design and development

.......

<a name="mat1"></a>
### Training materials: designing, producing, delivering

You may find some inspiration in:
ftp://gtpb.igc.gulbenkian.pt/bicourses/posters/Calix_March2013.pdf


<a name="mat2"></a>
### Training materials: Archival; Sharing; Making re-use possible

Training materials developed ahead for a specific training event have a survival issue. If they reflect too much of a conne ction to other parts of the event they tend to loose autonomy. It also happens that true autonomy is not there if the materials are used out of the original environment, for example slides may not work without a narration (audio).

Designing and producing quality training materials (presentations, exercises, support texts, instructions, worked results, etc.) involve a lot of work. It is a pity not to make specific efforts to create them with autonomy (self sufficiency) in mind. They should be properly stored  (and backed-up) and made available in referenceable public repositories. 

<a name="mat3"></a>
###  Training materials repositories and resources: GOBLET, TeSS, GitHub, etc.
A general policy for re-use is not yet in place. However, with sharing principles in mind, GOBLET (the Global Organisation for Bioinformatics Learning Education and Training)  has pioneered a public repository within a training Portal in 2014  http://mygoblet.org/training-portal where a significant amout of work has already been deposited.

The need for referencing training materials in general, in the context of ELIXIR, has led to the development of TeSS, a training e-support system http://elixir-uk.org/elixir-uk-training-sectors/elixir-uk-training-platform. This is all about discovering, packaging and linking training materials, i.e. trying to deal with the excessive fragmentation of the materials, rather than providing a storage repository for them.

Many people involved in the production of training materials are finding it useful to adopt collaborative platforms to support their activity. Git and GitHub, on which this resource is developed and served, is not a de facto standard, but presently it seems to be the smartest choice, especially because updating is left in the hands of the authors. The extended capabilties to produce websites, e-books, etc. are also seen as strenths. 

Examples from GTPB:

* http://mygoblet.org/training-portal/courses/ngs-data-analysis-rnaseq-chipseq    (GOBLET ENTRY) 
* http://bioinformatics-core-shared-training.github.io/ndarc16/   (gitpages) 
* https://github.com/sdwfrost/mevr        (repository) 
* http://sdwfrost.github.io/mevr/         (gitbook) 

Alternatively, the use of electronic notebooks, namely Jupyter ( http://jupyter.org ) and its satellite services are gaining popularity.

"Notebook documents (or “notebooks”, all lower case) are documents produced by the Jupyter Notebook App, which contain both computer code (e.g. python) and rich text elements (paragraph, equations, figures, links, etc...). Notebook documents are both human-readable documents containing the analysis description and the results (figures, tables, etc..) as well as executable documents which can be run to perform data analysis."

Please have a look at this example:
http://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb


<a name="design"></a>
## From session to course design;

<a name="preparatory"></a>
### Preparatory steps for training delivery

It may be useful to consider building your own (or adapting from Pedro's) checklists:

####To prepare a new training course

* Define the main idea (matching a perceived need)
* Define the Ideal Target Audience
* Define pre-requisites for the participants
* Select potential instructors. One of them plays the leader role. Involve him/her in all discussions from this point on.
* Breakdown into skills and concepts needed
* for each skill {


    state learning objective(s) and wite them down (use SMART learning objectives) 

    consider exercise alternatives 

    gauge duration, tech. requirements, testing  

    pick the best suited exercise 

    design a short lecture to precede it
    
    adjust timing for an ideal training slot duration 

    prepare self-assessment questions

    }
* Compose a logical sequence of slots and distribute them in a course plan timetable
* for each training day {
    program a fist slot / 
    On the fist day, use that slot to break the ice and establish team work discipline / 
    On the other days, use it for the wrap-up of the content of the eve / 
    }
* Plan a final wrap-up discussion at the end of the course
* Distribute the time slots through the days of training, using duration to balance the learning effort
* Use breaks to induce periods of collective reflection
* Foresee some physical activity, a couple of walks, a deep breathing exercise, for example


####Course deployment (face-to-face)

* Prepare the workstations so that they have a uniform setups/installations.
* Ideally, prepare and test one machine and use disk cloning to ensure uniformity.
* Clean-up shared directories: To_Participant, From_Participant, Data, Installers
* Check projector, lamp, dust filter, focus and color mode.
* Check documentation that may need to be distributed in paper form
* Check name tags for the Participants
* Prepare a list of Participants
* Check training  room tidyness
* Check air conditioned, lighting
* Check for the availability of pens and paper pads for notes
* Check Felt Tip Markers and whiteboard



<a name="rooms"></a>
#### Training rooms for Bioinformatics, Reproducibility of training environments;

Bioinformatics training targets a wide range of subjects that have very different needs in terms of the machinery needed to run exercises. However, there are design constraints that every training room should respect. And these are important in the initial planning, and in improvements that one may consider in their lifetime.

Room geometry

The design of modern Bioinformatics training rooms should, primarily, be learner centered. Space to circulate, to allow for instructors to reach learners and interact with them is abolutely essential. Learner comfort comes next: the quality of the seats, the lighting, the room temperature control, the stability of power and network connections, these are all aspects that have serious impacts in learner satisfaction.

Functionality

Learners aceess to anything that is shared should be in the first line of priority. Access to shared storage space should be made easy. To communicate with the learners, video, audio, drawing surfaces (whiteboard, flipchart paper), a corkboard to pin materials, etc. should have premium access and ease of use.

Hardware neeeds
In some subjects, network connections providing simple browing (Port 80) or SSH acceess (Port 22) are more than sufficient. In that case, BYOD (bring your own device) can be adequate. The room must have easy power and network connections, including a good quality wifi access. 

Presently, playing with relatively demanding software in local machines is still needed. You may need to play with assemblers and mappers for NGS data, for example. For that, well configured workstations (enhaced  PCs) are still the best choice. Foreseeably virtualised environments on performant hardware will end-up reducing  this need to the level of lightweight terminal equipment, but we are still on the way to get such facilities in place with adequate quality.

The working environment for learners should be entirely reproducible. First, inside the training room, the environment must be the same for everybody. Secondly, the learners should feel that they can reproduce the same  environment when they go home after a training event. Again, virtualised environments can be a solution. However, the training room physical facilities will not travel, so one must think about what will and will not work in a home or a lab environment and at least explain what can be done.

