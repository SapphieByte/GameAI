# GameAI
***A file for creating AI in games.***

---

## Syntax
`--` Creates a comment.  
`[(name)]` Defines a normal header.  
`<platform:(name)>` Defines a platform-specific header.  
`[/]` Ends a normal header.  
`</>` Ends a platform-specific header.  
`?(name):(value)` Sets a variable inside a header.  

## Styling recomendations
- Comments should be at least two spaces away from a line of code.

  ```
  ?somekey:"somedata"  -- Two spaces
  ```
- Two newlines should be put after a header end.  
  ```
  ...
  [/]
  
  
  [header]
  ```
  
  ## Quick notes
  Interpreters/converters are created by other gamedevs. If you make a program taking an `.aif` file to code, please use the python file provided in this repo (`./PythonAIFUtils.py`). If you desperately need the `.aif` to dictionary function in a different language, please message me on discord at `ack#0002`.
  
  If you have any questions or concerns, please message me on discord as stated above (`ack#0002`).
