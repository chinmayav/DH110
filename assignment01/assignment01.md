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
1. Top Priority: Visibility of system status; Recognition and Recall; Aesthetic & Minimalist design
2. Important to Fix: User control and freedom; Error Prevention; Help users recognize, diagnose and recover from errors
3. Small Inconvenience: Flexibility & Efficiency of use; Help & Documentation; Consistency & Standards

### Website 2: [Go Higher - Massachusetts DHE](https://www.mass.edu/gohigher/home.asp)

#### About

The Go Higher site appears to be intended to describe, elaborate on and provide resources for the Go Higher program in the state of Massachusetts, a program that operates at the high-school level to promote college readiness and raise awareness about the programs, opportunities and resources available at schools across the higher education level. The user flow on this site is mainly exploratory, as a user can peruse this site to try to find relevant information to understand the program.

#### 1. Visibility of System Status

Good:
* The UI incorporates a breadcrumb trail to let the user know how the site has been accessed and where it links back to within the greater mass.edu domain.
* When exploring through sub-pages in tabs (e.g. About), each sub-page also has info on the tab it resides in and easy toggles to other sub-pages in that tab
* All interactions have immediate visual feedback (e.g. navigating to new page).

Bad:
* When using interactive map, upon clicking on a school you're taken to a new tab (which is about the interactive map, so not a big context shift, but still unexpected.)


> *Recommendation?* Yes: some form of visual indicator/button that you will then go to Campus directory when clicking on school on interactive map.

#### 2. Match Between System and the Real World

Good:
* Expandable and collapsible menus in tab bar operate as expected

Bad:
* Carousel of highlights keeps transitioning horizontally, but position indicator circles are arranged in a vertical line - mismatch can be confusing.

> *Recommendation?* Yes - make position indicator circles horizontally aligned.

#### 3. User Control and Freedom

Good:
* Breadcrumbs help establish a lifeline for users to feel more comfortable exploring without losing context.
* Users can navigate back and forward across linked pages freely using back and forward buttons in browser.

Bad:
* Interactive map takes user to another page, and exploring other schools on map is tedious as you need to scroll to top of 2nd page to find interactive map again and keep rescrolling every time you want to see another school.

> *Recommendation?* Yes: Redesign interactive map interaction - have it remain static on page, and each time you select a new school the info in a single section immediately below it changes to match the school you selected.

#### 4. Consistency and Standards

Good:
* Follows convention for tab structure, navigation structure (Home/About, etc.)
* Explains all names that it introduces to user for first time\

Bad:
* Carousel on home page does not match standard carousel for reason listed in heuristic #2


> *Recommendation?* Yes - fix carousel as highlighted in heuristic #2

#### 5. Error Prevention

Good:
* No place with high-priority user input to make specific mistakes or slips more frequently than average rate of error, that cannot easily be rectified by going back.

> *Recommendation?* No - not needed in this case, as major user input is not necessary.

#### 6. Recognition Rather Than Recall

Good:
* When selecting a page from tab item menu, the page has the tab item's menu visible with all the other options so one can easily recognize context/hierarchy it exists in.
* Certain sub-pages have buttons that toggle scrolling to sections - primes user for recognition of contents through recognizing section header.

> *Recommendation?* No - this interface primes users for recognition well.

#### 7. Flexibility and Efficiency of Use

Good:
* Visibility of tab menus with other options on each subpage helps user pivot between pages in a single tab easily.

Bad:
* In What's New, scroll feels endless and inefficient as it gets tediously long
* No dynamic, varied possible actions of interacting with interface - not very flexible, but quite simple to understand
* No customization or personalization available
* Opts to navigate user to many external links over providing resource inside the site

> *Recommendation?* News/Updates sub-page could benefit from some time/date-stamping and pagination to make scroll feel a bit more manageable and efficient.

#### 8. Aesthetic and Minimalist Design

Good:
* Consistent text/heading styles that denote some sense of written structure to each page

Bad:
* Image banner at top is distracting with low value, and reduces visibility of anything below it at first glance.
* Tabs are not horizontally aligned - it looks unprofessional and chaotic.
* Section divisions are not clear enough - not enough spacing or dividers, reduces visibility and scannability of each distinct piece of content
* Inconsistent button styles - red in homepage for More button, but going to other site like in Commonwealth Dual Enrollment Partnership has a blue button? And blue button is positioned like image with text wrapping it? Confusing messaging of sequence - where does user look first?

> *Recommendation?* Yes: fix all aforementioned issues!

#### 9. Help Users Recognize, Diagnose, and Recover From Errors

Good:
* Clear section headings and signposts let user know immediately if they misclicked or not

> *Recommendation?* No - as kinds of errors made are very low-stakes and simple, the measures already taken by the site will suffice.

#### 10. Help and Documentation

Good:
* Always hyperlinks to resources that are introduced in this site

Bad:
* No FAQs
* No clear point of contact about this program/initiative specifically

> *Recommendation?* Yes - add another tab with staff or contact information for administrators of this project specifically, and FAQs with common points of confusion/grievances.

#### Overall Assessment

This site has fairly good and clear information architecture - the way information is nested here is quite logical and easy to navigate, and the array of possible interactions that the user has available to them is narrow yet very simple & hard to majorly slip up with. However, it suffers largely in its visual execution which creates a lot of competing elements for attention that reduce the visibility of each distinct piece of information on the page. It also does not have clear points of contact for users that want to learn more personalized information about the initiative, and its interactive map navigation could use a lot of work.

Severity ratings:
1. Top Priority: Aesthetic & Minimalist design, Help & Documentation, 
2. Important to Fix: User Control & Freedom, Visibility of System Status, Flexibility & efficiency of use
3. Small Inconvenience: Match between System and Real World, Consistency & Standards
