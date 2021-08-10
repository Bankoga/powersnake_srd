# OSARE System

> TL;DR: ?

MEASUREMENT VS EVALUATION!!!!

The Ordinal (O) Score (S), and (A) Rank (R), Evaluation (E) System is a measurement system based on using the same ordinal scale, with 10 sub-dividing ranks, that is combined with a handful of scales, and dice based evaluation functions, to encapsulate the values of a great many things.

These are the 3 primary components of the system.

1. OSAR (Ordinal Scoring, and Ranking) System
1. Evaluation Functions
    1. D (Decimal) function
    1. ME2 (Exponential using a Modified Power of 2) function
    1. O (Ordinal) function
1. DiBSARC (Dice Based, Score and Rank Comparison) System

The ToV's don't seem to really have anything to do with the ESRa or teh ScRaDeRs.
Given that they were the reason we had multiple scraders to begin with, it seems like we can rework these two systems into one.

## OSAR (Ordinal Scoring, and Ranking) System

> TL;DR: ?

Most property ranges are represented by scores, and sub-dividing ranks.

Scores go from -infinity to infinity, though in practice scores will often be less 20.
Ranks go from 0 to 9.
Leveling is done by spending TP (transformation points) on the relevant property.

> TODO: How does foundation building effect stuff?

Leveling the rank past 9, increases the score, and returns the rank to 0.
Leveling the score directly, does not change the overall rank.
This means one can choose to grow capacity, or build foundation.
Ranks must be increased sequentially, and cannot be skipped.
So you can have a max score 10, using minimum rank, with rank a 2 at score 3.

> TODO: How do these alternate score/rank things effect cost, and failure/success/continued growth potential?

### Cost Scaling

> TL;DR: ?

All scores have universal baseline scaling costs for rank increases.
Each specific property uses a single value reference scale to determine these costs, and to help explain what the property roughly means.
However, all properties use the same scale to determine baseline TP cost.
The baseline amount of TP required per rank at a score, is equal to 10 * the ME2 scale value of the current score.

These costs thought are strongly modified by context.

Cost of some thing = (Score of the Cumulative TP Cost of all scored properties of said thing) - (Status Quo Highest Most Similar Topic Score - similarity difference) - familiarity (which is it's own scaling score, lol) - trainer skill - (cost reducing contextual modifiers) + (cost increasing contextual modifiers)

Tracking context is direct situational, and status quo is specifically social context?

Just going to use pyramidal tech/topic score increase rules for the context mod that reduces the cost of stuff instead of value based increases, so the cumulative tp cost score

### Contextual Cost Modifiers

TODO: Make this a table but we ain't even their yet

- Training
  - being trained
    - by a scrub trainer vs a master trainer
    - by a master practitioner vs a scrub practitioner
    - the intersection of the two bys
  - self training
- Absorption/Comprehension/Growth limits
  - how well something can adapt varies based on the specific being across several dimensions
  - Really small things, be it in form/mind/spirit, bind TP inefficiently
- Personally available support capacity
  - the amount of accessible information, tools, and other personal/interpersonal support system capacity strongly gates how quickly one can learn, and sometimes what it is reasonably possible to learn

### Breakthroughs, and TP-less Increases

> TL;DR: How to mid-crisis epiphany, or just epiphany?

All of these are character, and story, driven growth mechanisms that are not milestones, or XP.

### Epiphanies, and Realizations

Sometimes, one isn't doing anything in particular at all, and all of the sudden something will click.
This can happen in pretty much any context.
These sudden realizations can be seized on,  or delayed for a little while, in order to make sudden leaps in capacity.
Otherwise they are lost.
These can, in most cases, be missed without consequence.
However, failing these will almost always cause direct TP loss.

### Trial by Dice

In other cases, some properties have requirements before they can be increased, like spending amounts of time, only being able to do so at certain times, or under other arbitrary conditions.

## Evaluation Function

### D (Decimal) Scale

### ME2 (Modified Exponents of 2 Function) Scale

> TL;DR:

The score is ~2x the actual exponent.
It's modified because the fractional exponents (the ones for odd scores) are adjusted to be neat.

### MT (Metric Time) Scale

This uses a rough earth day in seconds, as the base unit for scaling, and 1/10,000th of that as the base unit for scoring.

Scaling Function = ?
Base unit = hour.

Duration Score | Bucket Label | Duration (seconds) | Duration (rounds)
----- | ----- | ----- | -----
-1 | Accelerated Phase 1 | 0.0864 seconds | ?
0 | Base Action Duration | 0.864 seconds | ?
1 | Action Round | 8.64 seconds | ?
2 | ??? | 86.4 seconds | ?
3 | ??? Round | 864 seconds | ?
4 | ??? Round | 8640 seconds | ?
5 | Day | 86400 seconds | ?

Num actions per turn
vs
Num actions per duration tracked

Movement speed score is the number of turns per round, whereas agility is the number of actions per turn?

## DiBSARC (Dice Based, Score and Rank Comparison) System

> TL;DR: A way of using a d12 to do nifty things

Dice based, score and rank comparison is the core of the DiBSARC System.
This is done using the appropriate set of rules for comparing the values associated with different scores using dice.
Each scale has it's own system

### What does a Dice Roll Mean?

> TL;DR: ?

A dice roll represents the qualitative feel of how one does something, or how something, that is feasible given the context happens when failure is either not possible, or isn't interesting in context.
If failure is an interesting possibility, then a roll also means whether or not failure, or success occurred, and to what degree.
The specifics of the representation vary based on what is being evaluated, when, and in what situations.

### When To Make Dice Checks

> TL;DR: Not all the time, and enough to be fun.
> This probably varies by group

Rolling dice can be a lot of fun!
However, for most familiar obstacles, when in a fair context, no checks are required.
The same goes for completing routine, or skill based, problems when of sufficiently high ability, or familiarity.

> Something should be on the line if dice are rolled, so make sure to clarify the stakes!

When dealing with problems, dice checks should be made when failure is contextually difficult, interesting, required for learning, or time sensitive.
Dice checks are always required in the case of contests, or disputes.
Typically this is when one or more entities resists one, or more, actions.
This also happens when one, or more, conflicting things would happen in the same space at the same time.

Sometimes we ask for unnecessary rolls as RMs.
In such cases, the proper solution is to apologize, then carry on as if the player had succeeded.

### What Do The Results Of Checks Mean?

> TL;DR: TODO: Really need to come up with a better way to represent this...

This is margin of success resolution.
Rolling for ranks, and scores have slightly different margin of resolution rules.
Score comparison rolls are made when doing things with a difficulty score lower, or higher, than the score of the action used.
Please keep in mind however, that some things are either impossible, or contextually impossible.
The value of rolling in such situations is unclear.

The Result Value (RV) of a score, and rank, comparison is a labeled number where the label is R or S, for rank or score respectively.
For score, RV is the difference between the score one succeeded at, and the difficulty score.
For rank, RV is the difference between the minimal success value, and the rolled value.

Failure, and Success cascades either enhance, or replace result value.
Score failure cascades lead to ghastly rank comparisons.
Imagine successfully picking up someone who was shrunk, only to realize you accidentally squished them to death.
Score success cascades however, are the result value.
Whereas rank resolution is more varied though thematically similar.

Rank Comparison Result Label | Result Value | RV Difference | Effect Possibilities
----- | ----- | ----- | -----
Failure Cascade | Rolled a 1 | N/A | Bounded exponential growth of ever more awful effects. The failure is so great that it moves into story territory
Near Miss | rolled less than the difficulty value by 1 | -1 | A) Painful Success B) Painful Draw C) Painful Failure
Minimal Success | rolled exactly the difficulty value | 0 | A) Draw Contest B) Near Miss Contest C) Meager Success
Modest Success | beat the difficulty value by 1 | +1 | A decent level of property expression - nothing shabby, nothing fancy
Great Success | beat the difficulty value by 5 or more | >= +5 | A great level of accuracy, and precision. Starting to get fancy
Maximal Success | the difference between the result, and the value that needed to be beaten, or met, is equal to the max possible base difference | 9 | AMAZING!
Success Cascade | Rolled a 12 | N/A | Bounded exponential growth of ever more awesome effects. The success is so great that it moves into being it's own story territory.

Score Comparison Result Label | Result Value | RV Difference | Effect Possibilities
----- | ----- | ----- | -----
Failure Cascade | 1 | N/A | A) Ghastly Success B) Ghastly Failure
Fair Chance Cutoff | rolling 1 or more below the Success Cutoff | VARIABLE | to either A) Go to the next score comparison, or B) Go to the rank comparison for the final comparison
Success Cutoff, Using Higher Score | rolling at, or above, 11 - Min(Max(applied score difference, or applied score rank*), 9) | VARIABLE | causes the party with the higher score to win, and the lower score to lose
Success Cutoff, Using Lower Score | rolling at, or above, 3 | VARIABLE | A lot of the time, over reaching just means failure, however this is for when that isn't the case, or when trade-offs can be made
Success Cascade | 12 | N/A | How many orders of (base 2) magnitude cooler does it get

> *: It is possible to raise score directly, without going through rank based ascension which can lead to the rank at a score being lower than if one was going through rank based ascension, which takes, at minimum, 10 times the effort.

### What Are Dice Cascades?

> TL;DR d12 -> d6 -> d4 -> d3 -> d2.
Divide d12 results by 1 -> 2  -> 3 -> 4 -> 6, respectively

Instead of having unbounded dice diminishment, or explosion, use bounded decay.
Rolling the max, or min value in a dice check typically means rerolling using the next lower die size in the progression, with interpretation of the results varying based on what was being rolled, and in what context the roll occurred.

#### Resource Usage Dice

> TL;DR: Getting real thirsty up on stage can surely be a terrible thing, or not.
It really depends

This can also be used to track resource consumption instead of counting every single arrow, bite of bread, swig of ale, quaffing of a healing draught, or other.
Typically resource dice will either be single use, or only decay when rolling a 1.
They are either rolled every time the resource is used, or once per some arbitrary measure of time, like arrows in a short fight.
For longer, or mixed, durations situations, do not make resource checks on the most granular level.
An on stage debate that lasts an hour, for instance, may only require a d6 water bottle resource checks every 10 minutes or so, while making more granular checks once a minute.

> Whether or not you use this, is up to the preferences of your group

### D DiBSARC

### ToV DiBSARC

### ME2 DiBSARC

There are two cases for handling ME2 score comparisons:

1. When all participants in a score comparison are currently assessing at the baseline, or same, score
1. When one or more participants in a score comparison need to first assess at different score from the baseline, or the others
