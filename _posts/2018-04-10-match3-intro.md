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

At the Fishworld product design scrums, it was decided that it would be a good idea to integrate a Match 3 mini-game into our live Fishworld game.

Due to the timing of migration and the upcoming switch of core technology away from Flash, this presented us with a conundrom - the code base for this game feature is of a significant size. If we proceeded to implement it in Flash, we could get it out reasonably quickly but then it would need a full migration in the future, That would add to an already large migration backlog. If we waited for completion of Migration, it would delay the potential revenue generation we hoped to see by many months.

The solution agreed upon was to build a sort of hybrid solution. This would be comprised of creating an interface in the live Flash game to handle communication between Match 3 and the Fishworld base. We would then combine that with the Match 3 game elements (screens and logic) being written in C++ with our new engine. The two things are bridged through the magic of HTML5 and Javascript.

2 - What were we trying to accomplish

As discussed, out main issue was to get our old and new core technologies talking and working together to create a seamless experience for our users. There were several benefits of doing this:

  1. Solved the adding too much to the migration backlog issue

  2. Allowed us to start proving our new technology by providing a customer (Shaun Pauley), and a specific deiverable.

3 - What were the technical challenges

How did we solve the technical problems
Can we discuss them at a user decipherable level - I hope so...


4 - The Road to Match 3 Heaven

Wherein we chart the course and dicuss any trials and tribulations

The graphics engine and the editor were being devloped at the same time - discuss the problems that created



5 - Eh Voila - Success
Match 3 is in the final phases of development and things are moving along swimingly well :-). The outlook is quite positive for a June delivery of Match 3 to our Fishworld players. 










[^fn-sample_footnote]: Handy! Now click the return link to go back.
