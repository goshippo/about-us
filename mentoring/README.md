# Shippo's Mentoring Program

This is an experimentation, but we want to make it easy for Shippos to mentor each other on any topics that might be interesting.  To facilitate this, we've created a simple "template" to track interests between people.  This is dubbed a "bam/sam" or a "be a mentor / seek a mentor" file.

## Bam/Sam

The format is YAML, it is a human and machine readable.  It is broken up into several parts and here's a walkthrough of the full example of this [file](batmany13.yml).

### About

This part is to cover basic things like your name (duh!), hobbies, as in, we are humans first, and its ok to have interests outside of work ([be authentic](../behavior/authentic.md)) and can be a way for people to bond.  Finally, favorite resources are just a simple way to share key books/blogs/tools that you used for your own growth.

```
about:
  name: Bruce Wang
  dept: engg
  hobbies:
    - "Discovering eating all kinds of diff foods"
    - "Traveling"
    - "BBQing"
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

Ok, so, how does this all work?  Well, we're still figuring it out, as its an experiment.  But, the idea is to find two people interested in mentoring _each other_.  So that's the trick, the idea is to pair two people up who can learn from each other.  Now, over long term, it might be hard to find a double match, but this process is to show that mentor/mentee can learn from each other.  Mentors will find that they can learn a lot from mentees, and mentees will find that they have something to offer and help be the mentor as well.  Really, we just want the process to be a two way thing, and encourage that model rather than some strict person A is the higher status "mentor" while person B is lower status "mentee".