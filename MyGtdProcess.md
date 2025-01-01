# Keeping Track of Things

This method is based on the ideas expressed in [_Getting Things Done_](https://en.wikipedia.org/wiki/Getting_Things_Done) by David Allen, and is used to keep track of tasks that are not routine and frequent e.g., an email sent every Monday. The intention of the steps below is to keep track of (1) what needs to be done and when, and (2) what has been completed.

Two spreadsheet (Numbers or Excel) documents are used to keep everything in order. In practice, these will probably be tabs in a single spreadsheet. These should be kept as simple as possible so they can be exported as .csv files for portability.

- __TODO-List__, which includes all unfinished, known tasks.  
- __DONE-List__, which includes all completed tasks.

Two paper documents are used each day:

- The current week's TODO list.
- The current day's notes, which includes the day's TODO items at the top.

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

These are any work or goal that will take more than one action. The simplest will require only an entry in the __TODO-List__.  

Try to identify all of the needed TODO items & any dependencies and put them in chronological order.  

Consider timing for each when logging in __TODO-List__, but only make _Reminders_ / _Tasks_ for the next item needing to be completed.  

Despite weekly updates to all projects being part of the process, things like goals related to a 5-year plan can fall behind if they are not intentionally focused on. In these cases, setting aside some time each month or week by including a __TODO-List__ item for updating a status report would help.  

## TODO-List

This is the central document used to make this process work. Items included in it _must be_ written as a required step, granularly enough that no single task will take more than a week to complete. An item could be to determine what steps are needed to accomplish some goal.

Items are ordered by priority. This can be a text document or a .csv file opened in a spreadsheet program (preferred). TODO items on the __TODO-List__ should be moved to a list of completed items (__DONE-List__) periodically.

_Routine items_ like annual health checkups should be included in the __TODO-List__ with a note stating that once complete, another item should be added to the list for the next period.  

The format used to assemble the __TODO-List__ is based on [todo.txt](https://github.com/todotxt/todo.txt), but instead is a comma-separated list where all the following fields are required:

- __Current__:  
	- _Yes_= this week.  
	- _No_= not this week.  
- __Next step__: 
	- _Yes_= this is the next step in this context.  
	- _No_= some other step needs to happen before this one.  
- __Priority__:  
	- _High_  
	- _Medium_  
	- _Low_  
	- _Don't know_  
- __Status__:  
	- _Not started_  
	- _In process_ (__this week__)  
	- _Complete_  
- __Scheduled__:  
	- _Yes_= reminder/task initiated.  
	- _No_= not initiated.  
- __Start date__: Estimated start date for the task in YYYY-MM-DD format.  
- __Due date__: Required finish date for the task in YYYY-MM-DD format.  
- __Id date__: Date the item was added to the TODO List in YYYY-MM-DD format.  
- __Context__: Describes the project or category.  
- __TODO item__: Short text defining the item which is the same as what is used in Reminders, Folders, etc.  
- __Completed date__: Date the item was completed in YYYY-MM-DD format or 'Not done'. 

__Examples__:

|Current|Next step|Priority|Status|Scheduled|Start date|Due date|Id date|Context|TODO item|Completed date|
|:------|:--------|:-------|:-----|:--------|:---------|:-------|:------|:------|:--------|:-------------|
|Yes|No|Medium|Not started|Yes|2024-01-01|2024-01-15|2023-09-23|taxes|Send quarterly tax.|Not done|
|Yes|Yes|High|Complete|Yes|2024-09-26|2024-09-27|2024-09-26|email|Send mom an email.|2024-09-26|
|No|Yes|Low|Not started|No|2024-09-26|2024-09-27|2024-09-26|Save a pelican.|Call Steve to understand when they need the boat.|Not done|

## Weekly

### Weekly - Beginning

- Organize goals for the week by day.  

### Weekly - End

- Review all items in each inbox and handle them as described under __New item / idea__.  
- Write TODO items for the following _week_, in order, on _paper_, with relative priority and which day they _need_ to be accomplished. This must include routine tasks as well as those in the __TODO-List__.  
- Update any items on TODO-List.  
- Move completed items from __TODO-List__ to __DONE-list__.  
- Update Project documents (including after-action reviews and longer-term goals).  
- Review irregular period items expected to happen or due in the next four weeks.  

## Daily

### Daily - Beginning

- Review items noted the day or week before and ensure the week's (paper) TODO list includes all of them ordered according to priority. It should be clear what today's top thee items are.  

### Daily - End

- Review new items and existing weekly items, make updates where needed.  
- Start the next day's notes, including the items needing to be done that day.  
- Track any wins (e.g., goals achieved, things learned) as well a any things that can be done better (potential projects).  
