ToDoShorthandsKM
================

Keyboard Maestro Library for quickly adding Contexts and due dates to the current task in the quick add window.

This does have to be looked at to match your context names, and the localization of days names as Appigo ToDo's intelligent task parsing reacts to the right names of days in your current locale. So in my german version, I use like 'Sonntag' instead of 'sunday' when I type #sun .

Usage
=====

Import the library into Keyboard Maestro. When you're in the quick add window of Appigo ToDo (that you can set a shortcut for), and want to set a due date, type the following shortcuts:

  * #to for tomorrow
  * #mon, #tue, #wed, #thu, #fri, #sat and #sun for adding the next weekday, 9am as the due date, which gets put the beginning of the text.
  * @w for adding the @work context, @h for adding the @home and @g for adding the @GET context at the end of the text and jumping back right before it.
  
Of course all of this can be adapted to your needs in Keyboard Maestro easily. I'd love to do something more advanced, but sadly ToDo has no apple script API and not even menu items for your specific contexts, so not much more can be done AFAIK.