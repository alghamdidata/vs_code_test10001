TITLE: From a Bad Prompt to an Excellent Prompt
TOPIC: Using AI to prepare lecture slides on supply and demand
=============================================================


-------------------------------------------------------------
1. BAD PROMPT
-------------------------------------------------------------
Problem: too short and vague. No role, no student level,
no slide count, no context, no expected format.
-------------------------------------------------------------

"Make me slides about economics."

-------------------------------------------------------------
2. EXCELLENT PROMPT
-------------------------------------------------------------
Fixes every gap from the bad prompt using four parts (RACE):
  Role        -> who the AI should act as
  Action      -> the exact task to do
  Context     -> background info and known student struggles
  Expectation -> required structure and output format
-------------------------------------------------------------

"Act as a teaching assistant helping prepare undergraduate course
material. Create a 6-slide outline and 5 quiz questions on the topic
of supply and demand basics, for an intro-level undergraduate
economics class. The lecture is 45 minutes long. Context: last week
covered basic definitions of supply and demand separately; this week
builds toward how they interact to set market price. Some students
struggled last week with distinguishing a shift in demand from a
movement along the demand curve. Expectation: the slide outline
should build logically from review, to new material, to a
real-world example. The quiz should include 3 multiple-choice and 2
short-answer questions that test application of the concept, not
just recall of definitions. Provide an answer key."


-------------------------------------------------------------
3. FOLLOW-UP PROMPT (refinement step)
-------------------------------------------------------------
Problem found in the first draft: questions 2 and 4 only tested
recall of definitions instead of applying the concept.
This prompt names the exact issue and asks for a fix.
-------------------------------------------------------------

"Questions 2 and 4 only test recall of definitions. Rewrite both so
students must apply the concept to a new scenario, for example a
change in a related good's price, rather than just define a term."
