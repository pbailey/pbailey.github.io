---
layout: post
title: Match 3, ThorCC Style
---

Match 3 Article Outline

  Let's put the Outline for this article here:
  1. Overview
  2. What were we trying to accomplish
  3. What were the technical challenges
  4. The Road to Match 3 Heaven
  5. Eh Voila - Success


1 - Overview

As all Vikings know, supporting and growing a live game requires constanly tending to the software and adding new features to maximize the ongoing happiness of our players! The Fishworld product design team determined that adding Match 3 to Fishworld would add a desireable new feature for our users. Hopefully it would also be good from a revenue generating perspective.

Due to the timing of migration and the upcoming switch of core technology away from Flash, this presented us with a some hard decisions. The code required to build Match 3 would be of a significant size. If we proceeded to implement it in Flash, we could get it out reasonably quickly but then it would need a full migration in the future. That would add to an already large migration backlog. Waiting for migration completion on the other hand would delay the potential revenue generation we hoped to see by many months.

The solution agreed upon was to build a sort of hybrid solution. This would be comprised of creating an interface in the live Flash game to handle communication between Match 3 and the Fishworld base. We would then combine that with the Match 3 game elements (screens and logic) being written in C++ with our new engine. The two things are bridged through the magic of HTML5 and Javascript.

2 - What were we trying to accomplish

From a gamers perspective, add a cool new feature to Fishworld to increase user interest, and grow our revenue base.

From the technical perspective, combine our old and new core technologies and create a seamless and entertaining experience for our users.
 
The benefits of the approach were:

  1. We minimized the effect on the migtration backlog

  2. The plan provided PTR with its first production ready customer (Shaun Pauley), and a specific deiverable for insertion into the live Fishworld game environment.

3 - What were the technical challenges

1. The Thor enginge supports several types of Animation, one needed to be decided upon for Match 3 - the winner in this case was .... Spine Animation

2. Adding the new game functionality while ensuring the separation of the technologies used - this was accomplised by creating a bridge - calling out from Fishworld to HTML5 and bridging that to Emscripten (the technology that lets us complile Thor down to WebAssembly)


How did we solve the technical problems
Can we discuss them at a user decipherable level - I hope so...
The Thor engine supports multiple types of animation - which one - Decided to go with Spine Animation - seemed like the best choice



4 - The Road to Match 3 Heaven

Wherein we chart the course and dicuss any trials and tribulations

The graphics engine and the editor were being devloped at the same time - discuss the problems that created
- This was the biggest challenge for all developers on both sides to the engine.




5 - Eh Voila - Success
Match 3 is in the final phases of development and things are moving along swimingly well :-). The outlook is quite positive for a June delivery of Match 3 to our Fishworld players. 










[^fn-sample_footnote]: Handy! Now click the return link to go back.
