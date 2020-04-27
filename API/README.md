# API
* I wanted to code using Lua but unfortunally:
  * I have no previous knowledge about the existing functions.
  * W3C Map editor gives me no option to convert triggers to Lua code.
  * Blizzard doesn't provide an API for the functions.

The solution is to searchs old forums and convert triggers to jass code.  

## DisplayTextToForce

### Examples
```jass
call DisplayTextToForce( GetPlayersAll(), "Your message for the player" )
```