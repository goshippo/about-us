# Shippo's Mentoring Program

This is an experimentation, but we want to make it easy for Shippos to mentor each other on any topics that might be interesting.  To facilitate this, we've created a simple "template" to track interests between people.  This is dubbed a "bam/sam" or a "be a mentor / seek a mentor" file.

The key to this is its a `knowledge sharing program` over a strict "mentor vs mentee" program.  Hence, we want to pair two people who can learn from __each other__.

## Bam/Sam

The format is YAML, it is a human and machine readable.  It is broken up into several parts and here's a walkthrough of the full example of this [file](batmany13.yml).

### About

This part is to cover basic things like your name (duh!), hobbies, as in, we are humans first, and its ok to have interests outside of work ([be authentic](../behavior/authentic.md)) and can be a way for people to bond.  Finally, favorite resources are just a simple way to share key books/blogs/tools that you used for your own growth.

```
about:
  name: Bruce Wang
  dept: engg
  hobbies:
    - "Eating all kinds of diff foods"
    - "Traveling"
    - "BBQing and cooking"
    - "Hiking, biking, snowboarding, anything that lets me be outdoors"
  favorite_resources:
    - "Drive by Daniel Pink"
    - "Lean Startup"
    - "GitPrime Newsletter"
```

### Be A Mentor

Fairly self explainatory, pick 3-4 items in which you think you'd be a strong mentor to someone.  Now, this can be tricky because, this really depends on the level you consider yourself at, and the level your mentee is at.  The rule of thumb is, if its something you've done at least 2-3 times and you think you can help someone learn about it, then put it on the list. (You do NOT need to be able to teach a course to be someone's mentor)

```
# list 3-4 items you'd be keen on mentoring someone on
be_a_mentor:
  - "Leading and growing technical teams through strong culture and lightweight processes"
  - "Building a startup from scratch, and understanding business and technical aspects"
  - "Translate business requirements into bit-sized executable technical chunks"
  - "Microservice architecture design and methodology"
```

### Seek A Mentor

Here, pick 3-4 items that you are interested in learning more about.  Once again, seeking a mentor depends on your own level, but if this is something you don't feel confident on or is something that you know but is new (done 1-2 projects, worked with for less than a year), then you can probably seek a mentor on.  In reality, "seeking a mentor" is probably easier to set.

```
# list 3-4 items you'd want to learn more about
seek_a_mentor:
  - "Frontend development with React and Redux"
  - "Managing and shipping docker containers at scale (I really don't want to just say Kube :))"
  - "Golang development at scale (running 10+ interconnected services)"
```

## Putting it in action

Here are some easy steps to get started

* Fill out your bam/sam.  Submit it via slack to @bruce or @batman
* Look through the bam/sams and figure out who'd be a good pair match (@bruce or @batman will share with you the full list of participants)
* Setup an intro meeting (30 mins)
  * 10 minutes : Person A, as the mentor will interview Person B and learn what they want to get out of the program, what they want to learn.  It is important the mentor LISTENS to this
  * 10 minutes: Switch sides, and now Person B will interview Person A to determine what Person A wants to get out of the program.  Once again LISTEN as the interviewer.
  * Person A will spend 5 mins to confirm back to Person B what they'd like to get out
  * Person B will spend 5 mins to confirm back to Person A what they'd like to get out
* Take your time (up to a week) and think through what the both want to get out of this program.  This is your chance to do two things:
  * Determine if you'd be a fit as mentors to each other
  * Determine the best program to build for the mentee based on the conversation and create a "lesson plan"; a list of things the mentee should do to get started
* Share the lesson Plan Meeting (1 hour)
  * 30 minutes : Person A will go over the lesson plan, and let Person B ask questions
  * 30 minutes : Person B will go over their lesson plan with Person A, and let Person A ask questions
* Build a candence (at least once a month)
  * Based on the specific lesson plans, sync up with each other, and then check up on how things are going.
  * Each are making a __commitment__ to each other that they will take the time to work on this skill and grow it.

There is no obligation, and this is not a forced interaction.  If at anytime, one person feels like its not working out or it doesn't make sense, they can stop the program and there will be no hard feelings.