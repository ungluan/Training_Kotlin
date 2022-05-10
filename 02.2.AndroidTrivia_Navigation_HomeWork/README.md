1. How do you enable your project to use navigation components?
==> Answer: Add dependencies for navigation-fragment-ktx and navigation-ui-ktx
in the build.gradle (module) file.

2. Where are the possible routes through your app defined?
==> Answer: In a file (often called navigation.xml) in the res > navigation folder.

3. Which of the following statements about the NavHostFragment are true? Select all that apply.

a. As the user moves between destinations defined in the navigation graph, the NavHostFragment swaps
the fragments in and out as necessary.
b. You can click the NavHostFragment in the Project view to open the navigation graph.
c. You add the NavHostFragment to the main layout by adding a <fragment> whose name is 
androidx.navigation.fragment.NavHostFragment.
d. You must create a single NavHostFragment subclass and implement the onNavigate() method to 
handle different kinds of navigation (such as button clicks).

==> Answer: a,d

4. Which of the following statements about the navigation graph are true? Select all that apply.

a. You create a potential path through the app from one Fragment to another 
by connecting the fragments in the navigation graph.
b. The type of a connection between fragments is Action.
c. You must add the type="navigation" attribute to every <fragment> that is included in the 
navigation graph.
d. To open the navigation graph, you double-click the navigation file (navigation.xml) in the 
Android Studio Project pane, then click the Design tab.



