#John Klein
CMU SEI  
jklein@sei.cmu.edu

## Who am I?

- 10 years at SEI
	- Consulting - government and industry clients, defense, healthcare, finance, exascale science, ...
	- Research - Systems of systems, enterprise IT, big data
- Came to SEI from industry - telecom, enterprise applications, personal productivity, video networking, defense
- Perspective - engineering mindset, multi-disciplinary, generalist, try to be a systems thinker

## Position
### Starting point
I'm pessimistic. I think that our problems are more fundamental than "what is the best way to combine ML and programmed components".

- Society tolerates our inability to deliver and operate dependable* software
- Democratization of software development - low barriers to entry (both intellectual and capital).
- All software matters - today everything is connected to the internet and can directly or indirectly impact the dependability of other systems
	- There are no dog houses anymore (apologies to Grady Booch)
- We will hit a tipping point - societal tolerance will end, resulting in
	- Government (over) regulation, creating a black and a gray market for software
	- Software engineers becoming ostracized by society
	- Other bad stuff - I'm not a very good futurist

Evidence:

* __Square Kilometre Array (SKA) radio telescope project__ - Total construction cost ~ €800M (doesn't include 10+ years of design), software development estimated at ~ €90M
	* Most of the software was architected and will be developed by astronomers having no softare engineering training
	* But it's just scientific software - NOT!
		* SCADA control system - 131,000 antennas in the Low Frequency array
		* Exascale computing and storage
		* Fault-resilient processing pipeline
		* And it will cost at least €90M, and could brick €800M of hardware

* ["Write Code Like a Pro: Create Working Applications" (O'Reilly Media)](http://shop.oreilly.com/product/9781119404170.do)
	* "CODERS ARE ROCK STARS...Coders are the people who are building the future. You can stake your own claim on the future by learning pro coding techniques. Take a look inside to figure out how and why coders think a bit differently, the basics of building a working application with a professional coding language, and how to test your app to make sure it works. Get a jump on your future as a rock-star coder today!"
* [The Daily WTF: Curious Perversions in Information Technology]
(https://thedailywtf.com/) - the CodeSOD column never ceases to amaze me

### So what about the future of software design?
1. We need to take a system of systems perspective
	* (Almost) everything is networked
	* System of systems = Distributed, independent purpose, independent evolution
	* Systems need to monitor thier environment and behave appropriately when things change - usable autonomic frameworks?
1. We're not all Google or Netflix - we need usable architecture frameworks that allow "average" developers to produce dependable software
	* Combination of default behavior and explicit configuration?
	* Maybe model-based?
1. Reduce accidental complexity from multi-language, multi-tool development environments (see [https://stackshare.io]() for examples)
1. Deal with "legacy" software
	* Need efficient ways to recreate software for useful systems running on obsolete platforms
	* Hard socio-technical problem, e.g., yesterday's bugs are today's must-have features, because they are embedded in organizational processes or user's muscle memory.





-----
*Dependability = reliability + availability + safety + confidentiality + integrity + maintainability