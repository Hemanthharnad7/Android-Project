# MyTodoList
Simple todo Android Application to learn Android Design Principles 

**To Do** is an android app that allows building a todo list and basic todo items management functionality including adding new items and editing items.

Submitted by: **Hemanth Kumar Harnad**

Time spent: **20** hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can **successfully add items** from the todo list
* [x] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [x] User can **persist todo items** and retrieve them properly on app restart

## Video Walkthrough 

Here's a walkthrough of implemented user stories:


https://github.com/Hemanthharnad7/MyTodoList/blob/master/MyTodoList.gif

##Project Analysis

Q1) What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used.

The user interface of the Android application is defined by one or multiple forms/windows/displays. Each window is controlled by an Activity object that has a complex lifecycle. The visual elements of the Activity instance are constructed  using ViewGroup and View objects.The View class is the parent for a large hierarchy of visual controls, widgets, like textboxes, checkboxes, buttons etc. The ViewGroup class is the base for a hierarchy of layouts, used to manage collections of widgets and to define the layout architecture (linear, relative, tabular) of the window.

Q2) Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`.

Adapter is a bridge between UI component and data source that helps us to fill data in UI component. It holds the data and send the data to an Adapter view then view can takes the data from the adapter view and shows the data on different views like as ListView, GridView, Spinner etc. For more customization in Views we uses the base adapter or custom adapters. To fill data in a list or a grid we need to implement Adapter. Adapters acts like a bridge between UI component and data source.
