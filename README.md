
## Overview
This vault shows the issue using Kanban / MetaEdit and Dataview or Bases where the Vault cache is not being updated correctly, leading to incorrect display of the information.

To test.  
1. Open [[test Kanban Board]].
2. Move an item between *In Progress* and *Testing / 3rd Party*.
3. Open [[Homepage.canvas]].
4. Within 10 seconds, the cards should update and move between to the respective view.
5. This seems to work once for each card, then it does not update the view correctly when the card is then moved again, although if you look at the *Status* frontmatter on the file, it has updated correctly.
6. To resolve: **Settings > File and links > Rebuild Cache**.  The cards will appear in the correct location, until they have been moved once or twice.

Restarting Obsidian does not seem to resolve the issue.

This is happening on 1.11.4 and also on 1.10.6

Video of the issue: ![[issue.mkv]]