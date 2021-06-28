# FiniteStateMachineAPI
University of Washington Bothell Capstone, Spring 2021

Abstract:
This project was created using and functioning on Unity 2020.2.1f1.

This project was created using and functioning on Unity 2020.2.1f1.

The purpose of the Finite State Machine (FSM) API is meant to regulate events and user inputs to trigger the appropriate gameobject behaviors. For gameobjects with multiple behaviors with complex logic to transition between behaviors, this API cleanly organizes the behaviors into states and reduces logic complexity when switching between states.

This API is meant for game engineers to write scripts that inherit from the API. The game engineer needs to understand how to code in C# and add components to gameobjects in the Unity engine. You can follow this simple API tutorial documented here as an introduction to using the API: https://docs.google.com/document/d/1vvVsV0kVZuumiyAUdiKPjekmthv68DkWFOU4v_ok6C4/edit.

This API can be used for any gameobject including player characters. Player FSMs are scalable, but it is not recommended for PFSMs to go beyond state complexities that are observable in common first-person video games.

The result of this project is a FSM API that game developers can use for their projects to organize the behaviors and logic transitions.
