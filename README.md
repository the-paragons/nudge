# Problem
We all have behaviors we want to change. The problem is that it is difficult to focus on making more than one change at a time. It becomes difficult to track and provide feedback to yourself for things like:
* posture
* working hours
* taking breaks
* distributed movement
* etc.

To focus on these things in the moment is to break your flow in the moment. However, to wait and collect feedback yourself is onerous and the feedback is stale. What we want instead is a "coach" who can stand over us and whack us with a stick when we get off track. 

We need a nudge.

# Proposed Solution
VLMs and agentic workflows have gotten good enough that:
1. contextual understanding of a goal is possible
2. zero shot image analysis is possible

We propose a simple system that takes video as an input (can be on the order of every 1-10 seconds), takes a set of text based intentions -- the testset, and evaluates each assertion. Then, as output it can use a variety of channels but we can start with a notification.

That's it. Give it an intention, "I will take a break every 30 minutes", "I will sit upright with excellent posture" and you get back feedback in real time through a notification or, ideally, a voice prompt from a home hub.

Given the rising ubiquity of home camera systems and hubs -- and their cheapness the data should be available it's just a matter of getting access to it. We can select one ecosystem like Alexa, Google Home, or the Homepod since most camera systems integrate with one of these players.

We can build this toolchain completely open-source and (optionally) provide a paid hosted version.
