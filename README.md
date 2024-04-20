## TO-DO LIST

I am creating this to do list as a part of the intermediate javascript section of
the Odin Project.  I am jumping back into coding after not doing much for the last
month while moving my first few commits may be a bit rusty.  

The goal for this project is to develop skills with classes/constructors/factories
and to reinforce webpack/JSON learning, and finally to put the SOLID principles
into practice.  While this project is part of the Odin Project, I would also like 
to expand upon it for myself to use as a personal to do list.  Possible even
creating a desktop shortcut for ease of access as I expand on it.

My to do list will consit of a sidebar, where you can see the different to-do list
categories that I will be working on.  The categories will be stored in a dynamically 
filled and emptied array, filled from form answers.  Each to-do object will also 
be created in a dynamically filled array (within the categories array) with each 
object containing a title, priority, due date, completed boolean check, and a
description.

When the categories/to do lists are created, a DOM manipulator function will add 
them to the HTML tree along with a completed checkmark (greys out object), and a
delete button attached at the time of creation.

On the sidebar there will be a create new item button, where you will be able to 
choose whether you want to create a category or an item.  It will also display
the Home button and all categories and the titles of their items.  

In the home tab you will be able to see all of your categories, and their item
titles, aswell as your most urgent and due tasks.