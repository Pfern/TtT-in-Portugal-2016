#ELIXIR – EXCELERATE Train-the Trainer subtask

## Session 3: Session, course, and materials design

* [Training session design and plan;](#sessions)
* [From session to course design;](#design)
* [Training rooms for Bioinformatics, Reproducibility of training environments;](#rooms)
* [Training materials: designing, producing, delivering;](#mat1)
* [Training materials: Archival; Sharing; Making re-use possible;](#mat1)
* [Training materials repositories and resources: GOBLET, TeSS, GitHub, etc.](#mat1)
* [Preparatory steps for training delivery;](#preparatory)

<a name="sessions"></a>
### Training session design and plan;
<a name="design"></a>
### From session to course design;
<a name="rooms"></a>
### Training rooms for Bioinformatics, Reproducibility of training environments;

PEDRO

Bioinformatics training targets a wide range of subjects that have very different needs in terms of the machinery needed to run exercises. However, there are design constraints that every training room should respect. And these are important in the initial planning, and in improvements that one may consider in their lifetime.

Room geometry

The design of modern Bioinformatics training rooms should, primarily, be learner centered. Space to circulate, to allow for instructors to reach learners and interact with them is abolutely essential. Learner comfort comes next: the quality of the seats, the lighting, the room temperature control, the stability of power and network connections, these are all aspects that have serious impacts in learner satisfaction.

Functionality

Learners aceess to anything that is shared should be in the first line of priority. Access to shared storage space should be made easy. To communicate with the learners, video, audio, drawing surfaces (whiteboard, flipchart paper), a corkboard to pin materials, etc. should have premium access and ease of use.

Hardware neeeds
In some subjects, network connections providing simple browing (Port 80) or SSH acceess (Port 22) are more than sufficient. In that case, BYOD (bring your own device) can be adequate. The room must have easy power and network connections, including a good quality wifi access. 

Presently, playing with relatively demanding software in local machines is still needed. You may need to play with assemblers and mappers for NGS data, for example. For that, well configured workstations (enhaced  PCs) are still the best choice. Foreseeably virtualised environments on performant hardware will end-up reducing  this need to the level of lightweight terminal equipment, but we are still on the way to get such facilities in place with adequate quality.

The working environment for learners should be entirely reproducible. First, inside the training room, the environment must be the same for everybody. Secondly, the learners should feel that they can reproduce the same  environment when they go home after a training event. Again, virtualised environments can be a solution. However, the training roo physical facilities will not travel, so one must think about what will and will not work in a home or a lab environment and at least explain what can be done.


<a name="mat1"></a>
### Training materials: designing, producing, delivering;



<a name="mat2"></a>
### Training materials: Archival; Sharing; Making re-use possible;
PEDRO

Training materials developed ahead for a specific training event have a survival issue. If they reflect too much of a conne ction to other parts of the event they tend to loose autonomy. It also happens that true autonomy is not there if the materials are used out of the original environment, for example slides may not work without a narration (audio).

Designing and producing quality training materials (presentations, exercises, support texts, instructions, worked results, etc.) involve a lot of work. It is a pity not to make specific efforts to create them with autonomy (self sufficiency) in mind. They should be properly stored  (and backed-up) and made available in referenceable public repositories. 


ALLEGRA
<a name="mat3"></a>
###  Training materials repositories and resources: GOBLET, TeSS, GitHub, etc.
A general policy for re-use is not yet in place. However, with sharing principles in mind, GOBLET (the Global Organisation for Bioinformatics Learning Education and Training)  has pioneered a public repository within a training Portal in 2014  http://mygoblet.org/training-portal where a significant amout of work has already been deposited.

The need for referencing training materials in general, in the context of ELIXIR, has led to the development of TeSS, a training e-support system http://elixir-uk.org/elixir-uk-training-sectors/elixir-uk-training-platform. This is all about discovering, packaging and linking training materials, i.e. trying to deal with the excessive fragmentation of the materials, rather than providing a storage repository for them.

Many people involved inthe production of training materials are finding it useful to adopt collaborative platforms to support their activity. Git and GitHub, on which this resource is deveoped and served, is not a de facto standard, but presently it seems the smartest choice, especiually because updating is left in the hands of the authors. The extended capabilties to produce websites, e-books, etc. are also seen as strenths. 

Examples from GTPB:

http://mygoblet.org/training-portal/courses/ngs-data-analysis-rnaseq-chipseq    (GOBLET ENTRY)
http://bioinformatics-core-shared-training.github.io/ndarc16/   (gitpages)
https://github.com/sdwfrost/mevr        (repository)
http://sdwfrost.github.io/mevr/         (gitbook)




<a name="preparatory"></a>
### Preparatory steps for training delivery;
PEDRO




