# ZURB Ink Sublime Snippets

###### ZURB Ink version: v1.0.5

## Installation

ZURB Ink Sublime Snippets work with the latest development builds of Sublime Text, including [Sublime Text 2](http://www.sublimetext.com/dev) and [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install ZURB Ink Sublime Snippets via the `Package Control: Install Package` menu item. The ZURB Ink Sublime Snippets package is listed as `ZURB Ink Snippets` in the packages list.

### Using Git

Alternatively, if you are a git user, you can install the snippets and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

###### Mac/Linux Instructions

1. CD into Sublime Text packages folder
`cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages`

2. Clone repository into packages folder
`git clone https://github.com/christianrojas/zurb-ink-sublime-snippets.git`

###### Windows Instructions

1. CD into Sublime Text packages folder
`cd "%AppData%\Sublime Text 3\Packages\User"`
2. Clone repository into packages folder
`git clone https://github.com/christianrojas/zurb-ink-sublime-snippets.git`


### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files.
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory


## Snippets

+ Each snippet is prefixed with zi- (ZURB Ink).
+ Each snippet is singular, unless the name of the component ends in an s (columns)
+ Available classes are included as comments in the snippets


### Grid Structure

Component    | Usage
:----------- | :-----------: 
Boilerplate  | zi-boilerplate + tab
Container    | zi-container + tab
Row          | zi-row + tab
Wrapper      | zi-wrapper + tab
Columns      | zi-columns + tab
Sub Columns  | zi-sub-columns + tab
Buttons      | zi-button + tab
Images       | zi-image + tab
Block Grid   | zi-block + tab


## Contributing

1. Fork it.
2. Create your feature branch (`git checkout -b my-new-feature`).
3. Test your changes to the best of your ability.
4. Update the documentation to reflect your changes if they add or changes current functionality.
5. Commit your changes (`git commit -am 'Added some feature'`).
6. Push to the branch (`git push origin my-new-feature`).
7. Create a new pull request.



