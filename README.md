# SimpleToDo-App
My First Repository Simple Todo APP
# Pre-work - SimpleTodo App

SimpleTodo App is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: Vijayalakshmi Mohankumar

Time spent: 30 hours spent in total

## User Stories

The following **required** functionality is completed:

* [COMPLETE] User can **successfully add and remove items** from the todo list
* [COMPLETE] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [COMPLETE] User can **persist todo items** and retrieve them properly on app restart

The following **optional** features are implemented:

* [NO] Persist the todo items [into SQLite](http://guides.codepath.com/android/Persisting-Data-to-the-Device#sqlite) instead of a text file
* [NO] Improve style of the todo items in the list [using a custom adapter](http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView)
* [NO] Add support for completion due dates for todo items (and display within listview item)
* [NO] Use a [DialogFragment](http://guides.codepath.com/android/Using-DialogFragment) instead of new Activity for editing items
* [NO] Add support for selecting the priority of each todo item (and display in listview item)
* [NO] Tweak the style improving the UI / UX, play with colors, images or backgrounds

The following **additional** features are implemented:

* [NO] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:** Pretty simple process to create new application with minimal programming language. Application creation environment is very interesting and made me to interest on Andriod application development.
Interested to explore more on this platform.

**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`."

**Answer:** ArrayAdapater: It holds the data and send the data to adapter view then view can takes the data from the adapter view and shows the data on different views like listview, gridview, spinner etc. ArrayAdapter is more simple and commonly used Adapter in android.
Android's ListView uses an Adapter to fill itself with Views. When the ListView is shown, it starts calling getView() to populate itself. When the user scrolls a new view should be created, so for performance the ListView sends the Adapter an old view that it's not used any more in the convertView param.


## Notes

Describe any challenges encountered while building the app.

## License

    Copyright [2017] [Vijayalakshmi mohankumar]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
