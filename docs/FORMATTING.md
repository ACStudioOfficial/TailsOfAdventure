## Script Formatting Standard (Tails Script Format)

To ensure that "Tails of Adventure" scripts are consistent, easy to read, and automation-friendly, we follow a strict markup format.

## 1. File Structure
The beginning of a script, a specific story arc, or important metadata must be marked with a second-level header:  
`## Arc: "The Golden Age", Part 1: The First Boot`

## 2. Dialogues and Speech
Every line of dialogue is constructed using the following formula:  
`__Name__ (Modifier): Speech text[Space][Space]`

### Formatting Rules:
1. **Name:** Must be bolded using double underscores on both sides: `__Tails__`.
2. **Modifier (Optional):** If the character’s speech is altered (screaming, whispering, crying), add it in parentheses after the name: `__Lenka__ (screaming):`. It can be also placed mid-sentence or other parts to mark that text after it is affected by that modifier
3. **Punctuation:** A colon followed by a space MUST come after the name/modifier.
4. **Line Termination:** Each dialogue line __MUST__ end with a double space instead of a period. This ensures a "soft wrap" in Markdown.  
Examples:

__Tails__: I like you cut G   
[Tails slaps Anton]  
__Anton__: (screaming painfully)

## 3. Actions and Stage Directions
To mark a physical action, use an open square bracket followed by the character's name (without a colon) and the action:
`[Name Action]`

**Examples:**  
[Tails slaps Anton]  
__Lenka__ (screaming): SIX SEVEEEENNNNNNN   
[__Lenka__ commits arson and other warcrimes against humanity in the name of 67]  

## 4. Technical Details (SFX and Screen Text)
Audio cues (SFX), on-screen text, or subtitles are formatted using a double indentation (two tabs or 8 spaces) to visually separate them from the dialogue. It can be used several times in in any part of the script, but you have to double-Enter to separate it from the script. Also, if the text does not become grey in GitHub editor, make sure that you have a clean line before your details. It is a good idea to always have details and the rest of the script separated by 2 new lines  
Example:


                SFX: Loud explosion in the background
                TEXT: "67 hours later..."
                

__Tails__: I think we have arrived.  

## 5. Pronunciation
Some words can be hard to understand, hence after some questional words, there might be doube brackets to mark how you should pronounce that word.
Example:

__Tails__: I'm sick and tired. Let me rm -rf ((R M dash R F)) this mf

## 6. Script Template Example:
## Episode: The Bread Riot 


                SFX: Glass shattering


__Tails__: I like you cut G  
[Tails slaps Anton]  
__Anton__: (screaming painfully)  
__Lenka__ (screaming): SIX SEVEEEENNNNNNN  
[Lenka commits arson and other warcrimes against humanity in the name of 67]
__Tails__: I'm sick and tired. Let me rm -rf ((R M dash R F)) this mf
                
                
                TEXT: END OF CHAPTER
