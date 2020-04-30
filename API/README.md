# API
* I wanted to code using Lua but unfortunally:
  * I have no previous knowledge about the existing functions.
  * W3C Map editor gives me no option to convert triggers to Lua code.
  * Blizzard doesn't provide an API for the functions.

Thanks for the community there is forums and github with informations that can help to understand wc3 api.  
https://github.com/hackwaly/jass2/blob/master/blizzard.j  

# DisplayTextToForce

`DisplayTextToForce takes force toForce, string message returns nothing`

* **Description**
  * Display to `toForce` the text: `message`
  * The text is shown for an amount of time that automatically increases with the text length

## Examples
**Jass**  
```jass
call DisplayTextToForce( GetPlayersAll(), "Your message for the player" )
```

**Lua**
```lua
DisplayTextToForce(GetPlayersAll(), "Your message for the player")
```

**Lua alias**
```lua
print("Your message for the player")
```

# GetPlayersAll