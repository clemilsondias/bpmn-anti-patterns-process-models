# bpmn-anti-patterns-process-models

This repository holds process models of BPMN Anti-patterns based on Rozman et al. (2008).

These are the anti-patterns we were able to model through one of the selected BPMN-based process modeling tools (Bizagi, Bonita, Camunda and Signavio). The only anti-pattern we could not model were anti-pattern 5. The table below presents the anti-pattern id and its respective description.

Id    Anti-pattern
==========================================================
1     Activities in one pool are not connected

2     The event does not contain an end event
3     Sequence flow crosses sub-process boundary
4     Sequence flow crosses pool boundary
5     Gateway receives, evaluates and sends a message
6     Intermediate events are placed on the edge of the pool
7     Hanging intermediate events or activities in the process model
8     Each swimlane in the pool contains start event
9     Exception flow is not connected to the exception
10    Message flow misuse across swimlanes
