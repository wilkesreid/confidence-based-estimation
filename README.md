# Confidence-Based Estimation of Programming Time

A function of the programmer’s confidence in the task and the length of time it has taken to complete similar tasks.

The programmer/developer provides his confidence in his ability to complete the tasks with no hiccups. 10 = complete confidence that there will be no barriers to completion (i.e. he/she has completed this task many times before). 0 = absolutely certain that the task cannot be completed. 5 = he/she believes the task can be completed, but there may be some significant road blocks, or he/she may not have all the knowledge, resources, or experience needed to do it.

Estimated Time To Completion = ( Experiential Estimate * 10 ) / Confidence

e.g.

Programmer estimates a task will take 10 hours to complete based on experience, but his/her confidence level is only a 5 because the task involves modifying someone else’s code and working in a framework he/she has no experience with. So the resulting estimate is (10 * 10) / 5, which is 20. So in this case, the estimated time is doubled because of the low confidence level.

- A confidence level of 0 means the task cannot be completed at all.

- A confidence level of 1 will mean the estimate will be 10 times the experiential estimate.

- A confidence level of between 1 and 5 will mean the estimate will be between 2 and 10 times the experiential estimate.

- A confidence level of 5 will mean the experiential estimate will be doubled.

- A confidence level of between 5 and 10 will mean the estimate will be more than the experiential estimate, but less than double the experiential estimate.

- A confidence level of 10 will mean the estimate will be the same as the experiential estimate.

Confidence Levels

**10** I can do this easily. I’ve done it plenty of times before, and I am completely confident that I won’t run into any issues whatsoever.

**9** I am confident that this will not be difficult, and any issues I run into will be easily solvable, maybe by a quick Google search.

**8** I know that this will not be too difficult, but I will probably run into some issues here and there and should account for the extra time it’s going to take to work through them.

**7** I feel the same way I would if I gave an 8, but I’d like to give myself some extra time, or I feel the same way I would if I gave a 6, but I don’t think I’ll need quite as much time.

**6** This is a bit outside my comfort zone. I’ve either never done this before, or I’ve done it very few times, or the times I have attempted it have not gone so well. I will need to allow myself a bit of extra leeway in order to work my way through this.

**5** This task is going to be a problem. However long this seems like it should take, I need twice as long. I have very little experience with this, or I’m dealing with a particularly difficult situation like working in someone else’s code or in a framework that I’ve never used before.

**4** If I was in charge, I would probably want to just drop this entirely or give the task to someone else because the current task seems too difficult for me or I just don’t have the necessary experience/knowledge. I need to provide myself a lot of extra time, and even then I’m not sure I’ll actually be able to get it done. But I am willing to give it a try. I might recommend that someone more experienced with this kind of thing do it instead.

**3** I have so little experience with this, or it seems like so many issues are going to come up, that I’m not confident that my time estimate will be anywhere close to accurate, so I just need a ton of extra time. I’m not even sure how long it will take me to do all the needed research before I can start working on it. I’d rather not do it at all.

**2** This has possibly never been done before by anybody, and I have no idea how to even start going about getting it done. Whatever estimate I give is only a bare minimum, and I definitely can’t promise that I am actually capable of doing this at all.

**1** I’m almost certain that I can’t do it, or that it just can’t be done. I’m pretty confident that nobody else would be able to do it either.

**0** I’m completely certain this is impossible. This level is reserved for “Write a computer program that creates money out of thin air” type impossible things. This level means coming up with an estimate is pointless because the task simply cannot be done.
