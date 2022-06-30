Pull Request Description
Description:Currently, there seem to be two options for tagging: groups and keywords. Currently, groups seem to be the most usable option. However, I wonder, whether keywords are actually the better way to tag documents. However, their current usability is very bad (for example, showing all documents with a keyword requires some search skills)

Possible changes:
1. Show , (and potentially ) somewhere in the maintable. (something similar to groupskeywordslabels
1.1 Allow users to click on them.
 1.1.1 Upon clicking a group, the user will automatically open the group
 1.1.2 Upon clicking a keyword, all entries with that keyword will show in either main-table or in a separate window (e.g. in the window). Also, when within a group, only show entries from that group. edit > Manage keywords
1.1.2.1 Solution A: This approach would use the search feature of JabRef.
1.1.2.2 Solution B: Automatically create a when clicking on the keyword.group by keyword
  1.1.3 Upon clicking a label all entries with that label will show in either the main-table or in a separate window. Also, when within a group, only show entries from that group.
1.1.3.1 Solution A: use search feature
1.1.3.2 Solution B: create create group by label
2. Improve search for (potentially ) to something similar to what is shown in groupskeywordslabels

How to solve:
1.	You can use the search bar and search and search for specific keywords (e.g. "test") by writing
2.	You can also create automatic groups based on keywords, if that helps you
3.	What I was thinking of is something like labels here on GitHub (how you add them, how they display on issues and how you can click them or search for them). If needed, I can add more detailed explanation with screenshots.
4.	Make labels appear on multiple lines
5.	Divide tables into primary and secondary tables, use better search algorithms, and improve sensitivity to keywords



