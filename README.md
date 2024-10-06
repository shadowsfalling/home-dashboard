## Shopping List
Tables: shopping_lists, shopping_items

A shopping list contains multiple items, with each item belonging to a specific list.

Lists can be marked as "archived" when completed.
Each item in the list can be marked as "purchased."
A list should have a "completed" flag indicating if all items have been purchased.
Items can be grouped into categories (e.g., "Meal: Spaghetti Bolognese" as a category, with all necessary ingredients listed underneath as shopping_items).
Items can also exist without a category.
There should be a text field under each category for dynamically adding new items to the list.

# Timetracker
Table: time_entries

Each time entry is linked to a specific task or project.

Projects should be viewable individually, and the remaining working hours for the day should be displayed.
Time entries should be editable, allowing the user to adjust the start and end times as needed.

# Diary
Table: diary_entries

Each diary entry is recorded with a specific date and time.

# Calendar and Events
Table: calendar_events

This table stores event details, including start and end times.

There is a flag to indicate whether the event should be shown as a countdown on the dashboard.

# To-Dos
Table: todos

To-dos represent repeatable tasks, such as household chores.

The system allows setting repeat intervals (e.g., daily, weekly, monthly, yearly).
A flag indicates whether a task has been completed.

# Countdowns
Countdown information for upcoming events is displayed when an event is flagged for countdown.

# Quotes for Inactivity
Table: quotes

Stores random quotes or sayings that are displayed when the user has been inactive for a period of time.
