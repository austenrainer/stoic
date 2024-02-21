# Memoir in Software Engineering

## Aim and Objectives

The aims of this programme of work are to better understand the contribution that memoir can make to software engineering, to promote that contribution, and to use memoir to change thinking in software engineering.

From this aim, we formulate the following objectives:
1. To better understand the use of memoir as  a source of information into the software engineering process itself. The most obvious contribution of memoir is into the requirements engineering process, e.g., suggesting stakeholders, however memoir may also make a contribution into other areas of software engineering, e.g., database design and software testing.
2. To better understand _how_ memoir uses language to _represent_ the world, in contrast to how software engineering uses language (natural or artificial) to represent the world. For example, a metaphor is a kind of abstraction, but a kind of abstraction very different to object-oriented class-based inheritance.
3. To better understand the use of memoir as a mechanism for sharing experience and insights into software engineering. The most well-known memoir in this category is probably Fred Brook's [_The Mythical Man-Month_](https://en.wikipedia.org/wiki/The_Mythical_Man-Month), in which Brooks share's his experience of project-managing the development of IBM's OS/360 operating system, as well as reflecting on and proposing theoretical contributions, e.g., [Brook's Law](https://en.wikipedia.org/wiki/Brooks%27s_law). An indicative reference, which also challenges the contribution of experience, is Soyer and Hogarth's [The Myth of Experience](https://www.hachettebookgroup.com/titles/emre-soyer/the-myth-of-experience/9781541742055/).
4. To better understand whether and how memoirs can offer complex case studies for SE education. Many SE degree programmes encourage engagement with real world problems, e.g., as part of a final-year project or a team project. This raises challenges, such as: the challenge of securing real world clients who will sufficiently and consistently engage with the students; and the challenge of ensuring some kind of comparability across real world challenges (so that the student or team working on Problem A has a comparable problem to the student or team working on Problem B). Memoirs - the right kind of memoir - might provide a suitable alternative: providing a complex real world problem, with all the uncertainty and incompleteness that comes with such a problem, that can then be tackled by multiple students or student teams, whilst also potentially mitigating the challenges of client engagment and problem-comparability.

## Why memoir?

There are several reasons why memoir - the right kind of memoir - is relevant for software engineering:

1. A defining characteristic of memoir is that the memoir's author makes a _commitment_ to truth. Whilst truth is slippery - it's not easy to define and not easy to grasp - there is at least some grounding of the memoir in this actual world (as opposed to a fictional world). Because memoir (or certain kinds of memoir) present information about the actual world, memoir therefore presents, at least in principle, information more suited to software engineering. Consider, as a contrasting example, a requirements analyst interviewing a stakeholder. In such an interview, the stakeholder might offer information about their experience of the actual world. (In relation to [Rainer and Wohlin's credibility framework](https://www.sciencedirect.com/science/article/pii/S095058492200129X), the stakeholder is a more credible participant.) There are important differences, for example the interviewer has more direct and immediate influence on the information the stakeholder shares, yet there is also commonality: both sources (interviewee and memoirist) provide information about the world.
2. Like an interviewee, the memoirist may be sincere, however sincerity is not a sufficient characteristic for reliability. In other words, the memoirist is an unreliable narrator (sometimes deliberately so). This property - unreliability - potentially undermines the truth of the memoir, or parts of the memoir; yet, this is valuable for software engineering because it reminds the software engineer (more specifically, the requirements analyst) to be careful about the information they collect, and how they interpret it, and to remain aware that their models of the world (e.g., their databases, architectures, code) are also unreliable models. Box has famously said, "all models are wrong, but some are useful." One of the difficulties of models is that they may be useful from a software engineering perspective but can distort the human experience. 
3. Memoir presents complex, incomplete, ambiguous information about the world (just as an interviewee does). Thus, a memoir provides a relatively 'contained' case, providing helpful boundaries, e.g., for a student project, or a case study. Similarly, memoirs are often big case studies (book length memoirs are typically 200 pages or more, approximately 70,000 words) which help ensure that one is not working with a neat, simplistic description.
4. Memoirs can provide important insights on, and raise important questions about, society, the economy and the environment. Thus, they provide a way of thinking about technology, and its impact, in a wider context.
5. Memoirs require the reader to think differently, to think narratively or in and with story. Thus, memoirs 'force' a software engineer to think beyond computational thinking.

## _My Name is Why_, by Lemn Sissay

The main memoir used so far in this programme of work is Lemn Sissay's _My Name is Why_. Put very briefly, the memoir describes Sissay's experience as a Black person growing up in State-managed foster care in the UK during the late-1960s through early-1980s.

_My Name is Why_ memoir was selected because:

1. The memoir contains a large body of documentary evidence, collected independently of Sissay (and without his knowledge) during his childhood. Thus, in principle, the documentary evidence provides a different representation of the world - a different kind of representation of the world - compared to Sissay's personal experience of the world. (There is of course the issue that Sissay has _selected_ the documentary evidence to be included in the memoir.) Computational systems also represent the world. Consequently, the memoir supports the examination of different representations: the documentary evidence, Sissay's personal experience, possible computational representations. This connects to Contributions 2 and 3 above.
2. The memoir raises important questions about society, e.g., children living in foster care, the role of the State, prejudice (in particular, racism). This is important for challenging software engineers, and other computational thinkers, to think about to think both about a) the impact of computational systems on the world, and b) what can and cannot be represented in a computational system.
3. The memoir occurs at a time before computational systems were commonplace.

Many other memoirs were considered, including: Mohamedou Ould Slahi's _Guantánamo Diary_, Jackie Kohnstamm's _The Memory Keeper_, Colin Grant's _Homecoming_, Polly Curtis' _Behind Closed Doors_, Suad Aldarra's _I Don't Want To Talk About Home_, and Clyde W. Ford's _Think Black_. All of these raise important questions about society (criterion #2 above) and some occur before the pervasive use of computational systems (criterion #3) however none provide the extent of documentary evidence (criterion #1) comparable to Sissay's memoir.

A summary of the structure of the book is available [here](summary.md)

## Projects within the wider programme

Five projects have been successfully undertaken to date, or are being undertaken:
* An undergraduate final-year project that used the memoir to explore the design of a micro-services architecture to maintain information about foster children. This project assumed that the different institutions involved in the memoir (e.g., each school, each foster home) maintained their own information on children. The project looked at how these different institutions might create a way of sharing information between the institutions.
* An undergraduate final-year project that used the memoir to explore the design of a standalone software system in which children in care can raise concerns and requests about the behaviour of staff in a foster home.
* A taught postgraduate final-year project used the memoir to create an extensive set of user stories for two users, a foster child and a social worker, and then built a software system to satisfy those user stories.
* An MEng final-year research and development project that used the memoir to explore the limits of existing research on Personas, proposed a new method for constructing Personas and then developed a prototype software system to guide the interactive development of those Personas.
* In a taught final-year module with 150+ students, working in teams of 4-6 students, the students used the memoir as input into team-based software innovation. Each team identified a challenging 'problem' in the memoir, brainstormed ways to address that 'problem' and then prototyped a software solution for one of those ways.

## Bibliography

Rainer, A. and Wohlin, C., 2022. Recruiting credible participants for field studies in software engineering research. Information and Software Technology, 151, p.107002. https://www.sciencedirect.com/science/article/pii/S095058492200129X

