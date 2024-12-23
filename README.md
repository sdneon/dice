# dice
_Animated_ **dice** for HTML.
Adapted/patched/enhanced from [rems' Double Dice Roller @ sourcescodester](https://www.sourcecodester.com/javascript/17350/double-dice-roller-using-html-css-and-javascript-source-code.html).

## Dev Notes
* Fixed dice value and shown dice face mismatch. show-# css styles were mixed up.

### Enhancements/mods:
  * Refactored into class, with new features. E.g.:
    * HTML code generation for a dice.
  * Optionals:
    * Click on dice to roll.
        * Link 2 dice to roll together. 
    * On click handler.
    * Cheat modes to favour `even`s, `odd`s, `6`s or `1`s.
    ```js
    //To enable cheat:
    Dice.getDice('dice1').cheat = 'even'; //or '6', etc. Specify as string.
    //Roll it:
    Dice.getDice('dice1').roll(); //with animation
    Dice.getDice('dice1').random(); //without animation; just get a test value
    
    //To disable cheat:
    Dice.getDice('dice1').cheat = false;
    ```
  *  

# Credits
Thanks for the sample codes, rems!