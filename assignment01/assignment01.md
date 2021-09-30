# Higher Education for Underrepresented Groups - Supported by the Government of Massachusetts?

## Heuristic Evaluation - Chinmaya Vempati, DH110-F21

### Overview

Higher education has undergone a shift in its cultural & societal role in the last decade. As the younger generations of today contend with issues such as ever-increasing costs of living and a heavy & borderline predatory student debt system, there has been an increasing drive to stop treating higher education—a well-reported pathway for upward mobility in the socioeconomic ladder—as a privilege only available to the few, and rather think of higher education as a right accessible to all those who want it, especially underrepresented and marginalised groups who have historically faced exclusion from these spaces of learning. Meaningfully effecting this change necessitates, in large part, being codified in social support systems that the government is responsible for. 

In this vein, the government of Massachusetts has established a number of online resources to help guide prospective users through the landscape of resources and systems that may help make higher education more accessible for them. This is precisely the space I intend to delve into to explore how effectively these have actually been implemented, and not only evaluate how good they are at meeting the needs of the underrepresented, but also ideate and explore how much better they could be. How meaningful are the resources & solutions they spotlight to the users they’re intended for? Does the user experience of the resources clearly guide them through this unfamiliar domain, or unintentionally obfuscate it further? And most importantly, how do we evaluate where we are so we can push the envelope towards where we could be? 

### [Nielsen's Usability Heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/)

| No. | Heuristic | Description |
|---|---|---|
| 1 | Visibility of System Status | Users should always be informed about what is going on and should be given appropriate feedback to their actions |
| 2 | Match Between System and the Real World | Use concepts and language that are familiar and logical to the user |
| 3 | User Control and Freedom | Allow users to make mistakes; give them options to undo and redo tasks |
| 4 | Consistency and Standards | Follow conventions and make sure design is consistent across the platform |
| 5 | Error Prevention | Get rid of error-prone conditions and provide users with safety nets for high-cost errors |
| 6 | Recognition Rather Than Recall | Minimize user's memory load by giving them suggestions and help in context |
| 7 | Flexibility and Efficiency of Use | Provide multiple ways to perform a task to make the platform accessible to all users |
| 8 | Aesthetic and Minimalist Design | Provide only relevant content and features |
| 9 | Help Users Recognize, Diagnose, and Recover From Errors | Tell users what the problem is and provide suggestions to fix it |
| 10 | Help and Documentation | Supply users with extra help to complete their tasks |


### [Severity Ratings for Usability Problems](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/)

The following rating scale can be used to evaluate the severity of usability issues:
| Rating | Description |
|---|---|
| 1 | Cosmetic problem only: need not be fixed unless extra time is available on project |
| 2 | Minor usability problem: fixing this should be given low priority |
| 3 | Major usability problem: important to fix, so should be given high priority |

Ratings are displayed in parentheses after each usability issue.

### Website 1: [Strategic Initiatives - Massachusetts Department of Higher Education (DHE)](https://www.mass.edu/strategic/home.asp)

#### About

The Strategic Initiatives site appears to be intended to function as an area to search for relevant educational programs deployed in or by the state of Massachusetts. The primary flow a user follows is to filter by keyword, category or stakeholder to narrow the search set across programs, and then explore the available programs to decide which would apply to them or which warrants further exploration.

#### 1. Visibility of System Status

Good:
* The UI incorporates a breadcrumb trail to let the user know how the site has been accessed and where it links back to within the greater mass.edu domain.
* Relatively immediate feedback of each action (e.g. filter selection) a user takes as number of search results is visible and updates

Bad:
* Low visibility of how many/which filters are selected at any point in time, especially if selected filters need to be scrolled down in their menu to see.
* As you scroll down, easy to lose context of what filters are selected (i.e. how you're narrowing your search) as there's no visible reference without needing to scroll all the way back up.

> *Recommendation?* Yes - include some form of visual reference or direction to let them access info on filters even when their viewport is lower in the scroll - e.g. a hovering button that allows them to navigate back to top, or a hovering bar of selected filters as tags that are always visible as they scroll down, and reorder selected filters so they appear at top of list when you select them (making all selected filters the first ones you see).

#### 2. Match Between System and the Real World

Good:
* All terms used in this site are easily understandable, and do not require any additional specific context for a general user to be able to decipher (e.g. focus areas, student identities, initiatives, etc.)
* Filters are also correctly referred to (as users are familiar with the concept) and implemented through a search bar and checkboxes
* Search Results is organized like a scrollable bulletin board with distinct items.


> *Recommendation?* No - this seems to match real-world structures adequately, with no real need for fixes or radical improvements that would create tangible added value.

#### 3. User Control and Freedom

Good:
* Checkboxes for filters are easy to uncheck, and there is even a button for resetting filters
* Breadcrumbs are clickable, so if they ended up on this page by accident the user can navigate back.

Bad:
* If one hits Reset Filters accidentally, they have to manually reselect all filters they deselected from memory.
* Not immediately obvious that breadcrumbs are hyperlinked.

> *Recommendation?* Yes - add button to enable previously selected filters that appears when Reset Filters is clicked, + add underline/bolded styles to breadcrumbs to make them more obviously clickable.

#### 4. Consistency and Standards

Good:
* Terms used here are familiar to users in other contexts (e.g. initiatives)

Bad:
* Certain items have identical cover photos, forcing users to look at names to distinguish them where they would use the cover photos as visual cues when scanning page.

> *Recommendation?* Yes - make each cover photo unique.

#### 5. Error Prevention

Good:
* Clear indications of sections that set precedent for how you interact with them (e.g. you don't use filters and expect a sorting mechanism).

Bad:
* Checkboxes are too small, so easy for user to make a slip and misclick.

> *Recommendation?* Yes - larger checkboxes with more space in between each item.

#### 6. Recognition Rather Than Recall

Good:
* In each item being searched for, there are category keywords that users can recognize from the filters they selected

Bad:
* As you scroll down, easy to lose context of what filters are selected (i.e. how you're narrowing your search) as there's no visible reference without needing to scroll all the way back up.
* Connection between selected filters and category keywords is non-obvious - must be inferred.

> *Recommendation?* Yes - a hovering bar of selected filters as tags that are always visible as they scroll down past filter editing section, or other form of visual indication of filters being selected (perhaps collapsible, or bolded category keywords in each item corresponding to appropriate filter).

#### 7. Flexibility and Efficiency of Use

Good:
* Search and Filters provide flexibility of action to user, allowing them to define their own search set by what is relevant to them.

Bad:
* Cannot define any other ways of sorting search results apart from alphabetical order (e.g. most recent).
* No clear keyboard shortcuts for undoing or redoing filter selections.

> *Recommendation?* Yes - institute Cmd-Z for undoing selecting/deselecting a filter, etc. and include other togglable options for sorting search results.

#### 8. Aesthetic and Minimalist Design

Bad:
* can't see all filters within certain filter list, and not obvious that each list is scrollable
* spacing and section separation is inconsistent, makes irrelevant elements to each other feel grouped together while relevant elements are separated
* three items per row may lead to visual/cognitive overload and reduce visibility for each item
* skip to content header is entirely unnecessary.

> *Recommendation?* Yes - consistent section dividers, increase spacing between site description and search bar, reduce to two items per row and remove skip to content header.

#### 9. Help Users Recognize, Diagnose, and Recover From Errors

Good:
* Easy to deselect a filter or delete a keyword

Bad:
* Low visibility of selected filters means that hard for user to see/recognize if wrong filter is selected

> *Recommendation?* Yes - better visibility for selected filters! Make them bigger and more prominent when selected.

#### 10. Help and Documentation

Bad:
* No links for keywords in Mass DHE context that may need more description (e.g. a Task Force)
* No clear link or signpost to FAQ page anywhere 


> *Recommendation?* Signpost to FAQ page at some point in the site - either below site description or at the bottom (either above footer or within footer). Add links for keywords, or at least tooltips that describe them.

#### Overall Assessment

This site could certainly do with visual tweaks that would not only clean up the aesthetic but also help make relevant pieces of information seem more visible and make the site more scannable. One could even add bonus bits of functionality that would make it feel more tailored to the user's context, stage of use and tastes. However, apart from that, the site is actually quite functional for its intended purpose, with relatively immediate feedback for every distinct user action taken.

Severity ratings:
Top Priority: Visibility of system status; Recognition and Recall; Aesthetic & Minimalist design
Important to Fix: User control and freedom; Error Prevention; Help users recognize, diagnose and recover from errors
Small Inconvenience: Flexibility & Efficiency of use; Help & Documentation; Consistency & Standards

### Website 2: [Go Higher - Massachusetts DHE](https://www.mass.edu/gohigher/home.asp)

#### About

#### 1. Visibility of System Status
* point here

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

> *Recommendation?*

#### 2. Match Between System and the Real World
* point here

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

> *Recommendation?*

#### 3. User Control and Freedom
* point here

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

> *Recommendation?*
#### 4. Consistency and Standards
* point here

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

> *Recommendation?*

#### 5. Error Prevention
* point here

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

> *Recommendation?*

#### 6. Recognition Rather Than Recall
* point here

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

> *Recommendation?*
#### 7. Flexibility and Efficiency of Use
* point here

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

> *Recommendation?*

#### 8. Aesthetic and Minimalist Design
* point here

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

> *Recommendation?*

#### 10. Help and Documentation
* point here

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

> *Recommendation?*

#### Overall Assessment


