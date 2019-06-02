# bpmn-anti-patterns-process-models

This repository holds process models of BPMN *Anti-patterns* based on Rozman et al. (2008).

These are the *anti-patterns* we were able to model through one of the selected BPMN-based process modeling tools (Bizagi, Bonita, Camunda and Signavio). The only *anti-pattern* we could not model was anti-pattern 5. Although, some tools emitted warning or error in the modeling phase. The table below presents the *anti-pattern* id and its respective description.

Id  |  *Anti-pattern*
--- | -------------
01|    Activities in one pool are not connected
02|     The event does not contain an end event
03|     Sequence flow crosses sub-process boundary
04|     Sequence flow crosses pool boundary
05|     Gateway receives, evaluates and sends a message
06|     Intermediate events are placed on the edge of the pool
07|     Hanging intermediate events or activities in the process model
08|     Each swimlane in the pool contains start event
09|     Exception flow is not connected to the exception
10|    Message flow misuse across swimlanes
