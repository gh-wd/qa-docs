# Desktop app requirements

- **App name:** QA-Desktop 
- **Product Vision:** Application allows users to create collections of question/answer items to test their knowledge for a particular subject or topic to enhance their learning

## Functional Requirements
|Priority|User facing features| Id # |
| :---| :---| ---:|
| Must Have | Flashcard management  | 1 |
| Must Have | Account management | 2 |
| Must Have | Flashcard persistence | 3 |
| Must Have | Flashcard sessions | 4 |
  
### Use cases
- Flashcard Creation
  - User can create a new collection with a name and tags
  - User can create new flashcards with question and answer
- Flashcards management
  - Application displays flashcard collections that can be sorted or filtered
  - Flashcards can be selected for the following actions:
    - Deletion
      - Application asks for confirmation before deleting entire collection or indiviual card
    - Editing
      - Collection name and tags can be updated
      - Flashcard question and answer can be updated
      - New cards can be added
- Using flashcards
  - User can select a flashcard collection to start using it
  - User can select option to randomize cards or display in created order
  - Application displays each flashcard one by one, allowing user to go to the next card or back to the previous one
  - Once user reaches end of the flashcards, application presents option for starting over or returning back to home screen
- User auth
  - User can login to access their own flashcards
  - Password is encrypted
