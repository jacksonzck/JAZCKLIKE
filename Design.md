# JAZCKLIKE design document

## Goal of the Project

 The goal of JAZCKLIKE is to provide a *generalized* *extensible* framework for user-created "Zachlike" puzzles, including many of the components from the games featured in the Zachtronics catalogue.

## User Stories

 - A player pulls in a puzzle they want and can play it and view the score. 
 - A puzzle maker can make the puzzle with the components they use, input and output criteria, and custom? scoring metrics. 

## General Design for Implementation

 - Do it in rust
 - Use sandboxed lua for all of the user generated code
 - + like "default" components and whatnot. 
 - Except outside of maybe XML for meta-information?
 - But they need to make an lua file anyway for the input and output generation
 - So ehh I dunno.
## Other Considerations

None for now!