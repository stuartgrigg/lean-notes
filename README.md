# Implementing Lean Software Development Notes

Stuart Grigg 2019

These are my notes on Implementing Lean Software Development by Mary and Tom
Poppendieck https://www.amazon.co.uk/Implementing-Lean-Software-Development-Addison-Wesley/dp/0321437381.
The notes are ordered as they were taken from the book.

| Note                                                                                                                                                                                                                                                                                             | Page Reference |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------- |
| Empirical design - start with a concept not a full product definition and iterate                                                                                                                                                                                                                |                |
| Have an early release of a minimum feature set to customers                                                                                                                                                                                                                                      |                |
| Avoid analysis paralysis                                                                                                                                                                                                                                                                         |                |
| Eisenhower - planning is essential but plans are useless                                                                                                                                                                                                                                         |                |
| A lean organisation optimizes the whole value stream from a customer order to deployed software addressing the need                                                                                                                                                                              | 39             |
| Use higher level measurements to prevent neglecting things and local optimisation                                                                                                                                                                                                                |                |
| Understand the value stream timeline from concept to cash                                                                                                                                                                                                                                        |                |
| Release a feature before it is fully refined                                                                                                                                                                                                                                                     | 45             |
| Have a mind-meld between business and tech                                                                                                                                                                                                                                                       |                |
| Seven wastes - Partially Done Work, Extra Features, Relearning, Handoffs, Task Switching, Delays, Defects                                                                                                                                                                                        | 74             |
| Have some developers who can drop work to deal with issues/urgent requests                                                                                                                                                                                                                       | 87, 88         |
| Process cycle efficiency = Value-added time / Cycle time                                                                                                                                                                                                                                         |                |  |
| The recommendation to a team who's backlog is the biggest time waste in their value stream is to purge the backlog of features                                                                                                                                                                   | 90             |
| Have customer support in development teams and backlog grooming                                                                                                                                                                                                                                  | 98             |
| Have maximum six month project sizes                                                                                                                                                                                                                                                             | 99             |
| Reduce cycle time with: even arrival of work, minimum amount WIP, minimum size of WIP, regular cadence, limiting work to capacity, pull scheduling                                                                                                                                               | 103            |
| Keep the backlog to two iterations worth of work                                                                                                                                                                                                                                                 | 105            |
| Everybody's job is nobody's job                                                                                                                                                                                                                                                                  |                |
| When multiple people/teams are working on the same thing have regular synchronization events                                                                                                                                                                                                     |                |
| Lava lamps for monitoring                                                                                                                                                                                                                                                                        |                |
| Don't let iterations just be waterfall in timeboxed increments                                                                                                                                                                                                                                   |                |
| One week hackathons                                                                                                                                                                                                                                                                              | 152            |
| Focus everyone on the biggest problem                                                                                                                                                                                                                                                            |                |
| Find the critical problem that is stopping you making money                                                                                                                                                                                                                                      | 153            |
| Reports on a study, design of an MVP or an incident investigation should fit on an A3 sheet and be stuck up to preserve and share knowledge                                                                                                                                                      |                |
| Set based design - to deal with very critical deadlines, build three versions of the product to different standards to ensure that at least one will be done by the deadline - developing multiple options is less waste than missing critical deadlines                                         | 160            |
| Stop the line the minute a defect is detected                                                                                                                                                                                                                                                    |                |
| Strangle legacy code by slowly replacing it with new code                                                                                                                                                                                                                                        |                |
| Story about a team with a big backlog - the solution was to cull features heavily, propose alternatives to users rather than add to the backlog and keep the backlog at around four iterations of work                                                                                           | 169 to 172     |
| Apply the scientific method in retros - define, analyse, hypothesis, experiments, verify, follow-up/standardise                                                                                                                                                                                  | 169            |
| Kaizan event - a small special team to solve a problem over a few days                                                                                                                                                                                                                           |                |
| Succinct product roadmap rather than a long queue of things to do                                                                                                                                                                                                                                | 185            |
| Stories should contain sample tests                                                                                                                                                                                                                                                              |                |
| Aggressively avoid a backlog of code for review - pair programming can avoid this                                                                                                                                                                                                                | 195            |
| CI should be fast and painless                                                                                                                                                                                                                                                                   |                |
| Maximise the amount of full system synchronizations                                                                                                                                                                                                                                              |                |
| Everyone should faithfully stop to fix problems as soon as they are detected                                                                                                                                                                                                                     |                |
| Set days aside to analyse the system and make key decisions and plan                                                                                                                                                                                                                             | 204            |
| Eliminate barriers that rob people of their right to pride in workmanship                                                                                                                                                                                                                        | 210            |
| Have concise readable code committed into the system in very small pieces                                                                                                                                                                                                                        |                |
| Nobody really tells open source developers what to do                                                                                                                                                                                                                                            |                |
| Over the wall communication seldom works well - rotate people between development and customer facing teams                                                                                                                                                                                      |                |
| Four questions - How do you create value and make a profit?, What is you main problem right now?, What threatens your continued existence? What do you really believe about people?                                                                                                              | 223            |
| Companies should base decisions on a long range vision                                                                                                                                                                                                                                           | 227            |
| Better to enhance the workers rather than replace them with tech as this ensures the process still has the capability to change                                                                                                                                                                  | 228            |
| Standardise the process to have something to question and change                                                                                                                                                                                                                                 | 229            |
| Lean prefers team leaders to process leaders                                                                                                                                                                                                                                                     | 230            |
| A constraint of projects is that estimates become commitments - this leads to overestimates and an inefficient use of time as people will use all the time they have estimated - better to not commit or overestimate and instead have buffer time for the whole project - critical chain theory | 232            |
| Focus our creative efforts on breaking dependencies                                                                                                                                                                                                                                              | 233            |
| Be alert to accommodations you have made for constraints which are no longer present - eg. having to define the cost, scope and schedule of a project upfront even when the funding does not have to be gained upfront                                                                           |                |
| Retrospectives can just produce the same long list of ideas which become someone else problem - try out techniques and implement those that work yourself                                                                                                                                        | 237            |
| Reduce the number of measurements and just measure cycle time, financial results and customer satisfaction                                                                                                                                                                                       | 238            |
| Measure not the fastest cycle time but a repeatable cycle time                                                                                                                                                                                                                                   |                |
| The development team should understand the profit and loss model for the product                                                                                                                                                                                                                 | 240            |
| Calculate the net promoter score for the product                                                                                                                                                                                                                                                 | 241            |
| Abolish the notion that is is good practice to start development with a complete specification - do concurrent development and specification                                                                                                                                                     |                |
| The last section of the book provide a how to guide for implementing "lean" including some of what's above                                                                                                                                                                                       | 242            |
