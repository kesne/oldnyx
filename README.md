#Oldnyx

Oldnyx is a theme for Enyo 2's Onyx UI Library which aims to bring the visual appearance of Enyo 1 to Enyo 2 applications. Oldnyx is built right on top of Onyx, so any application can simply drop in the new stylesheet to use it.

I started this project because I thought the standard Onyx styles left something to be desired.

##Using

You should be able to simply drop the compiled Oldnyx css file into your Onyx CSS folder and have everything work without a problem. We also provide a few additional classes that you can use to customize your existing onyx components.

####onyx-dark
(TODO) Oldnyx uses a light theme for all components by default. Adding the "onyx-dark" class to nearly any component will use different styles which have been optimized for dark-themed applications.

####onyx-header
While Enyo 1 separated provided a Header kind for applications, Onyx has no such offering. To make a toolbar appear like an Enyo 1 Header, just add the "onyx-header" class.

####onyx-primary
(TODO) This recreates the primary button found on Enyo 1.


##Issues

- Incomplete style set. Not all of Onyx's components have been styled yet.
- The styles are not as flexible as they should be. Setting your own colors may not work as expected.
- Input background colors when focused are ignored unless marked as !important.
- GroupBoxes with headers rely on the first item having a background color.
- Dark styles are almost all missing or incomplete.

##Todo

- Try to rework the GroupBox implementation to something a little more flexible.
- Create dark themes.
- Fix toolbar backgrounds.
- Figure out tab button implementation.
- Finish styling all Onyx components.
- ToolInput