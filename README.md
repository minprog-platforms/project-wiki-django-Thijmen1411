# Application Name

This application will be called **Encyclopedia**. This application will contain a home page with a list of all entries. Each entry will be a link to a page with a description of that entry. All pages will have a sidebar with a search field, which will let you search for specific entries, and a link to go back to the home page. They will also have links to create a new entry page or visit a random page.


## Getting Started

As of now, there's only the *index* view which will be the home page. In *views.py*, there should also be functions to view each entry page individually, which will be done using the *get_entry* function. These functions will be called upon when clicking a specific entry in the entries list on the home page, when searching for a specific entry in the sidebar or when a link to a different entry in an entry page is clicked. The *get_entry* function will also be used when the user is trying to visit a random page. Finally, there will also be a function to add a new entry page through the use of the *save_entry* function. There will have to be multiple paths in the *urlpatterns* list in *templates/encyclopedia/urls.py* for all these functions.

These HTML pages will be needed:
- layout.html
- index.html
- entry.html
- new.html
- edit.html
- search.html

![This is a sketch of the application](/sketches/Sketch.jpg)


