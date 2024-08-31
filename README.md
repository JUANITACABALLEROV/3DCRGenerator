# 3DCRGenerator

This repository contains the accompanying materials for the paper "3DCR: A Tool for Immersive Process Mining".
The game artifact "3DCR Beta Generator" described in the paper can be sampled by visiting the URL https://play.unity.com/en/games/036f5d66-b931-4892-91c8-320df2be6dcc/3dcr-generator-beta

 The tool contributes to two use cases in process mining: Elicitation and discovery of process variants using unrestricted process models and simulations of process models.

## Tool Demonstration  

https://bit.ly/3DCRvideos

1. We built a process model for the sickness registration process using DCR Simulator and exported it in XML File format.
2. We built the Unity world based on the logic (events, rules, and so on) of Dynamic Condition Response graphs, providing specific domain representations and visual and sound cues to understand better what is going on.
3. While the user interacts with the tool in its online or local version, it collects two types of logs. The first corresponds to the "activity_state_change" event that contains the activity ID, the name of the activity, and the status (Executed / Refused), in other words, whether the trace is valid or not. The second corresponds to the specific interaction log with each executed activity.
4. These logs can be analyzed in Unity Analytics Cloud. If you use the local tool, this step requires configuring the service at https://docs.unity.com/ugs/manual/analytics/manual/get-started. You can make diagrams and SQL queries there and create new events and parameters according to the granularity you want to consult.
5. For the tutorial's example, we take the valid traces of a couple of interactions and export them in CSV format to be analyzed with DISCO.


##To play the 3DCR Beta, please note the following:

If pressing the keys does not work, try clicking the mouse button within the game view.
Choose full screen before selecting a domain.
Switch views by using the 1,2,3 keys.
1. In View 1, the WASD keys move the character back/forward/left/right. To execute an activity, place the targeting reticule over it and press the left mouse button.
2. In View 2, the WASD keys move the character back and forth, and AD rotates the character on its axis. To execute an activity, place the mouse pointer over it and press the left mouse button.
3. In View 3, the WASD keys move the camera back/forward/left/right. Place the mouse pointer over an activity to preview its execution.

##Notes:

The folder" artifact" contains the artifact's source code.
The folder" doc" contains the appendices for the paper" 3DCR: A Tool for Immersive Process Mining."
