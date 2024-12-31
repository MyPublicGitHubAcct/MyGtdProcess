# GTD Process

This method is used to keep track of tasks that are not routine and frequent e.g., an email sent every Monday. The goal of this method is to keep track of (1) what needs to be done and when, and (2) what has been completed.

Two .csv documents are used to keep everything in order:

- __TODO-List__, which includes all unfinished, known tasks.  
- __DONE-List__, which includes all completed tasks.

## New item / idea

This process is started each time a new request, idea, or need is identified and understood at least enough to make note of it.  Do one of:  

- Take action now (5 minutes or less). 
	- If assigning to someone else, file this in __DONE-List__.  
- Log temporarily, items that can't be added to a list due to physical context (i.e., location) e.g., personal items don't go on the work lists and vice versa. [Notes or paper]  
- Don't take action now items - do one of:  
	- Delete the item.  
	- File for future _reference_, if needed. No entry will be made in __TODO-List__.  
		- M: Folders + Text Documents (Sublime Text)  
		- W: Folders + OneNote  
	- File for _consideration_ at some timed interval. An entry will be made in __TODO-List__ with a _Due date_ representing when this should be reassessed.  
		- M: Folders + Reminders + Text Documents (Sublime Text)  
		- W: Folders + Tasks + OneNote  
	- File as a new _project_.  
		- M: TODO List (Sublime Text) + Folders + Reminders  
		- W: TODO List (OneNote) + Folders + Tasks  

## Projects

These are any work that will take more than one action. The simplest will require only an entry in the __TODO-List__.  

Try to identify all of the needed TODO items & any dependencies and put them in chronological order.  

Consider timing for each when logging in __TODO-List__, but only make _Reminders_ / _Tasks_ for the next item needing to be completed.  

## TODO-List

This is the central document used to make this process work. Items included in it _must be_ written as a required step, granularly enough that no single task will take more than a week to complete.

Items are ordered by priority. This can be a text document or a .csv file opened in a spreadsheet program (preferred). TODO items on the __TODO-List__ should be moved to a list of completed items (__DONE-List__) periodically.

The format used to assemble the __TODO-List__ is based on [todo.txt](https://github.com/todotxt/todo.txt), but instead is a comma-separated list where all the following fields are required:

- __Current__:  
	- _Y_= this week.  
	- _N_= not this week.  
- __Next step__: 
	- _Y_= this is the next step in this context.  
	- _N_= some other step needs to happen before this one.  
- __Priority__:  
	- _H_= high.  
	- _M_= medium.  
	- _L_= low.  
	- _D_= don't know.  
- __Status__:  
	- _N_= not started.  
	- _C_= complete.  
- __Scheduled__:  
	- _Y_= reminder/task initiated.  
	- _N_= not initiated.  
- __Due date__: Required finish date for the task in YYYY-MM-DD format.  
- __Identified date__: Date the item was added to the TODO List in YYYY-MM-DD format.  
- __Context__: Describes the project or category.  
- __TODO item__: Short text defining the item which is the same as what is used in Reminders, Folders, etc.  
- __Completed date__: Date the item was completed in YYYY-MM-DD format or 'Not done'. 

__Examples__:

Y, N, M, N, Y, 2024-01-15, 2023-09-23, taxes, Send quarterly tax., Not done  
Y, Y, H, C, Y, 2024-09-27, 2024-09-26, email, Send mom an email., 2024-09-26  
N, Y, L, N, N, 2024-09-27, 2024-09-26, Save a pelican., Call Steve to understand when they need the boat., Not done  

## Weekly

### Weekly - Beginning

- Organize goals for the week.  

### Weekly - End

- Review all items in each inbox and handle them as described under __New item / idea__.  
- Write TODO items for the following _week_, in order, on _paper_, with relative priority and which day they _need_ to be accomplished. This must include routine tasks as well as those in the __TODO-List__.  
- Update any items on TODO-List.  
- Move completed items from __TODO-List__ to __DONE-list__.  
- Update Project documents (including after-action reviews and longer-term goals).  
- Review irregular period items expected to happen or due in the next four weeks.  

## Daily

### Daily - Beginning

- Review items noted the day or week before and ensure the week's (paper) TODO list includes all of them ordered according to priority.  

### Daily - End

- Review new items and existing weekly items, make updates where needed.  
- Update any status items.  




