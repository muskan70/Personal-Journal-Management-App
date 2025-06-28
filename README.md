## Personal Journel Management App
It is a terminal app used to store personal journel of users.

Features present:
- login or signup details: 
  > - All the usernames and their passwords are stored in .npy file 
  > - check at login if that username and password exists then only user is allowed to enter
  > - At signup,first check if no.of users do not exceed a limit then check if that particular user is already present or not,then add that user to our login list
- After login user is asked if he want to enter a new entry or view all previous entries.
- During listing of all previous entries, we load the npy file of that user and display all the entries along with their date and time of entry.
- while adding a new entry it is checked if no.of entries are not greater than limit.
- If yes then the first entry is removed and new entry is added like a queue.
