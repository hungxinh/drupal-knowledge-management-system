#Overview

DKMS is envisioned as a knowledge management system built with Drupal primarily for sharing/storing/searching case-related documents. Core functionality includes the ability to upload tagged and categorized documents using a single form; an intuitive search and filter system that allows advocates to quickly and easily locate the documents they need; mechanisms to identify the newest, most popular, or most helpful documents; and permissions controls so that limited access can be granted as necessary to outside individuals or organizations. It is designed to be responsive and mobile-friendly.


<p align = center><img src=/DKMS-Home.png></p>

If not logged in, visitors will arrive at a home page, prompting them to sign in or sign up.


<p align = center><img src=/DKMS-Dashboard.png></p>

The "Dashboard" operates as the primary landing page for signed in users.

The top of the Dashboard includes a link to the user's account page, a link to the upload file form, a search box, and a mega menu that includes common filters (legal issue, document type, advocate author). These filters will operate using a Select2, allowing users to type or select their filter of choice (e.g. "eviction"). The search box returns results based on tags provided by users at the time the document was uploaded, as well as on the text of the document itself when possible.

Below this toolbar, the Dashboard will feature blocks highlighting (1) the current user's favorite cases, clicking which takes them to a Search Results page for that case; (2) documents recently accessed by the current user; (3) popular documents (e.g. 5-10 documents weighted by most unique user accesses then most overall accesses in the past 60 days); and (4) recently uploaded documents. Blocks 3 and 4 will be filtered to match a user's "Favorites" (see below).


<p align = center><img src=/DKMS-Search.png></p>

The top of the Search Results page contains a search bar, populated by the search term used if a user arrived at this page by using the search bar function on the Dashboard. The search bar will search within filtered results if any filters have been applied (i.e. entering a new search term will not reset the filters a user has applied).

Below the search bar are filter options which appear as links, selecting which opens a Select2 allowing users to select from commonly used filters or begin typing. These options include, for instance, Case, Legal Issue, and Advocate Author. There will also be a date range selector. All applied filters (including search terms) will appear in the appropriate place (i.e. inside the search bar or under their respective filter option link) and will feature an "x" for simple one-click removal.

The results themselves will be displayed below the filter options. Each result will feature a thumbnail preview of the document generated automatically at the time it was uploaded and a small icon indicating what filetype the document is. Aside the thumbnail, details about the file will be listed (e.g. title, date filed, etc.). Together they form a single clickable field that will take a user to that file's page. A smaller button will allow a user to directly download the document from the Search Results page.

Interactive arrow icons will appear next to attributes by which the results can be sorted (e.g. date filed).


<p align = center><img src=/DKMS-FileProfile.png></p>

When a user selects a file from the Search Results page, they will arrive at a profile page for that file. At the top of the page is the File Title, followed by small icons for New or Popular files, and the option to mark the file as a Favorite.

Below, on the left, a larger version of the thumbnail preview appears, below which are clickable file tags (e.g. "Appellate Brief"). On the right are various file properties: Date Filed, Case Title, Advocate, Legal Issue. The Case Title field also includes a count of how many files are associated with that case, and case tags (e.g. water rights).

Below this data is a field for users to add comments on the file, as well as flag the file as helpful/not helpful. The former allows advocates to discuss the usefulness of the document and provide feedback, while the latter can be used for later analysis--in particular, identifying which documents are most helpful practice-wide.


#My Account Dashboard

Following the link from the Dashboard will lead users to their account page. The account page is tabbed with Recently Accessed, History, Favorites, and Account Management.

The Recently Accessed tab is linked to a Search Results page displaying documents the current user has viewed, sorted by most recent date of access.

The History tab is linked to a Search Results page filtered to display documents uploaded by the current user, sorted by most recently uploaded.

The Favorites tab will allow users to select filters to apply to their Dashboard display (Popular and Newest Docs). It will also allow them to designate favorite cases, which will appear on the Dashboard as well.
