# Reborn-E (Engine) Apollyon Architecture

## Architectural Designs
- Base Reborn Engine
  - Throttle 
- Reborn-E
  - Synchronous
  - Apollyon

### Base Reborn Engine
Base Reborn Engine has two distinctive features (compared to Reborn-E): 1) Several (**ROAMING**) Executive Components; and 2) Highly Event-Driven. 

Although roaming executive components were highly performant, they were too tedious and actually counterintuitive, especially using Reborn Engine. Base Reborn Engine is, by far, one of the most performant engines, but it comes at the cost of absolutely disgusting error handling. Additionally, handling conditional events across several branches and client-server can become even more tiring than it already is. 

Throttle Architecture was, thus, introduced with the idea that it integrates plug-ins that run quick design time tasks, including a centralised location for most, if not all, of the branches and their functions exported in one composed module. Throttle was the first architectural design to introduce more than one branch. Although Throttle Architecture failed, it proved that design-time task executions were possible with Reborn Engine; in fact, it proved to be ridiculously easy. This was thanks to the additional branch that was introduced. (I couldn't keep coping with the Base Reborn Engine and abandoned it entirely, Throttle Architecture included). Throttle Architecture had some other successes, especially in introducing Service-Orientated Programming. 

### Reborn-E
Reborn-E has two distinctive features (compared to Base Reborn Engine): 1) Single-Script Architecture; 2) Microservices Architecture (Supersedes Applicative Architecture).

Single-Script Architecture allowed me to introduce a number of features, including better security for conditional scripts using CollectionService. This was huge, as the game could be stolen, but the majority of the in-game codebase wouldn't be. Additionally, Single-Script Architecture improved performance, organisation, and pacing (which is huge for us quota-based developers...). Microservices, on the other hand, were also perfect, as the more divided a codebase is, the better it is (that's without using artificial helpers like events). However, the number of branches available was no improvement from the failed Throttle Architecture and still continued, in many aspects, the same logic. Although it was a huge improvement, it was still downplayed by the fact that Object Orientated Programming had to be introduced, and as great as it is, it's not perfect. 

Synchronus Architecture was the breakthrough. Synchronus Architecture has several distinctive features:1) Layered Architecture; 2) Pipe-Filter Architecture; and 3) Space-Based Architecture. Synchronous, in its name, decreased the amount of stored data over logic and then also introduced a stream for that data in its own unique branch, the Pipe-Filter branch. This same branch also handles run-time optimisations, preventing an overload on the server. Despite this being a huge improvement in performance from 5 branches (Reborn-E) to 8 branches (Synchronous), this became tedious once again as it encouraged bad-habit coding. Not only this, but I still relied on run-time and gameplay data, meaning the iteration count was still quite high. We weren't eliminating the problem; we were rather avoiding it. 

### Reborn-E (Apollyon)
The Apollyon Architecture is the biggest breakthrough yet. It has several distinctive features:1) Partial Removal of Layered Architecture; 2) Reintroduction of Data-Orientated Programming; 3) Broker Architecture; 4) Introduction of Entity-Based Programming via Entity Component Systems; 5) Generalised Data Managers; and 6) Forces Good-Habit Coding. 

The Throttle Architecture, despite its failure, was actually quite successful on the development side of things. It proved that design-time executions were possible, and they were all-important in cutting down on development time and increasing pace. The Apollyon Architecture takes inspiration from this and introduces a dedicated branch for design time executions.

Speaking of branches, Synchronous had 8 branches. Apollyon has **DOUBLED** this amount to 16 branches, which is a gigantic improvement. Apollyon not only improved from Synchronous Architecture but also overhauled Reborn-E entirely and introduced applicative coding and caching over reiteration, recalculation, and instancing. Each component, item, and entity has its own unique serial identification, humongously decreasing memory leaks. This leaves the server with more than enough to carry out its heavily isolated tasks like communication, final calculations, and rendering. 

Apollyon Architecture isn't just an improvement in development but rather an improvement in experience, as new technology has been integrated, including post-processing effects like Dwayne (heavily overused in battleground games), rain, and snow viewport illusions. You could say this example is the Developer's Choice: we've also introduced a new technology that uses queuing in streaming and rendering, which is absolutely perfect if you want to introduce similar technology to other engines. 
