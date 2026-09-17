## Customer meetings
### Sprint 0 (31.08)
#### Agenda
- Figuring out the most important features to focus on
- Questions regarding ownership of the GitHub repository
- Setting up a time for the next meet
#### Meeting notes
- Most important thing to focus on is bringing the application to production from staging
- Second most important focus is to get the search working with Helmet-API
- Everything else is a nice to have (such as the stories left by the preivous team)
- Continuing to use the same repository as the previous team, access will be provided to us
- Next meeting will be on Thursday 17.9. 16:00 


### Sprint 1 (17.09)

#### Agenda

- Demo
  - Application is now in production
  - Helmet search
  - User deletion

#### Questions for the customer / Development ideas

- **"Recent clubs" button in the sidebar:** A user may only belong to one book club, so the usefulness of this feature should be reconsidered.
- Language filtering for books retrieved from the Helmet API.
- Repositioning the registration button.
- Changing how the club invite code works.
- Showing password requirements during registration.
- Displaying Helmet search results in a scrollable container and showing more results.
- Users currently cannot leave clubs themselves.

#### Meeting notes

- The default languages for Helmet searches should be Finnish, Swedish, and English.
  - Users could potentially select additional languages, for example for a Russian-speaking book club.
- The language codes in the search results should be improved or converted into more readable language names.
- Book search results should include:
  - Cover image
  - Number of pages
- Edition year and ISBN may not be necessary information to display.
- Investigate whether the availability/reservation status of a book can be retrieved from Helmet.
- If the initial search results are not sufficient, there could be a button for loading the next set of results, for example the next 10 books.
- It is fine for part of the team to focus on refactoring while the rest works on new implementations.
- AI tools can be used as part of code reviews.
- Codes used for book clubs or login-related functionality should not be easily guessable or sequential.
- Password requirements do not need to be overly complicated.
- The team can freely work on and improve user management functionality.
- Check the cluster-related matter with Outi and Matti.
- The backlog is currently public.
- The application should support localization in both English and Finnish.

#### Customer development ideas

- **Manual cycle editing:** There may be a need to change the original duration of a book club cycle after it has been created.
- **Book club member view:** Add a view where users can see who belongs to the book club.
- **Meeting participation:** Allow members to indicate whether they will participate in a book club meeting.
  - The application could contain information about where the meeting will take place.
  - Users could see who has voted and/or who is attending the meeting.

#### Next meeting

- Confirm whether the next customer meeting will be on **Thursday, 1 October at 16:00**.
