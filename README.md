sublimetext-preferences
=======================

Developing a community based GUI for managing your SublimeText 2 preferences.

Concept
Create GUI for SublimeText preferences which are just JSON files.

How
Online hosted solution where ppl create an account and it stored their prefs. They can tweak etc then save as file. 

Basic Editing
Config file is created which outlines the available options. Options can be

  * Boolean
  * Number
  * String
  * Preset option (choose from list)
  * Command (unquoted string)
  * Array / object

For each option in a config would need to store

  * Data type (above list)
  * Default value
  * Required or not
  * Avail options (if list)

These would need to allow nesting as that may be possible. 

There'd be a standard config file and then a config file could be created for each plugin.

There'd be public presets which ppl could download. Or preload them into your profile then tweak. 

Data structure

  * Config
    * Option
      * Choices
      * Options (nesting)


  * User
    * Preferences
      * Configs


To Do

  * Look at Heroku/AWS for free hosting
  * Can all pref store in one user file?
  * Good download method. 
  * Plugin for launching / updating your preferences from app. 
