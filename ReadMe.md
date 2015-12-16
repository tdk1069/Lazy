# Lazy

Simple helper for farming XP/CP/Trash items. So far includes:

  - Always Turn to face Target, even if Trust Tank pulls away from you
  - Keep within 3Yalms of Target at all times
  - Weaponskill when TP available
  - Ability to cast a spell whenever Recast/MP allows

### Installation

* Inside your Windower\Addons folder create a new folder called Lazy
* Copy these files into the folder created above.

### Commands
* //lazy start
* //lazy stop
* //lazy reload

#### //lazy start
Starts the actual helper

#### //lazy stop
Stops the helper

#### //lazy reload
Reloads the options from the settings.xml

### settings.xml
<spell></spell> - Spell to cast, will cast whenever MP and recast time allows
<spell_active></spell_active> - true/false enables/disables enables casting of the spell
<weaponskill></weaponskill> - weaponskill to use when over 1000TP
<weaponskill_active></weaponskill_active> - true/false enables/disables use of weaponskills
