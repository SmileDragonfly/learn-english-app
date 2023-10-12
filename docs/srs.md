# SRS for Learn English App
<!-- TOC -->
* [SRS for Learn English App](#srs-for-learn-english-app)
  * [History](#history)
  * [Application requirements](#application-requirements)
  * [Backend requirements](#backend-requirements)
  * [FrontEnd requiremnts](#frontend-requiremnts)
  * [UI/UX requirements](#uiux-requirements)
<!-- TOC -->
## History
|Date|Version|Author|Change Description|
|----|-------|------|------------------|
|10/10/2023|1.0|DatDT|Initial version of SRS|

## Application requirements
### 1. User
- Signup
  - Enter: username(unique) + password(strength enough) => server ok
  - Optional: Use OAuth2
    - TODO
- Login
  - Use phone or email and password to login
    - Enter email(phone) + password => backend verify => success/fail
- Logout
  - User click on button logout => logout and back to log in screen
- Profile
  - Add name, phone, email, nation
  - Verify email, phone (to reset password if forget)
- Reset password
- User level
  - User will have english level evaluated by their learning process
    - Vocabulary level
    - Grammar level
    - Pronunciation level
- History
  - Vocabulary history
  - Grammar history
  - Pronunciation history
  - Learning history by datetime (in a day => show what user have learned)
### 2. Features
- Learn Vocabulary, Grammar and Pronunciation
  - Random mode: easy to hard words
  - Level mode: depend on user level, the words will have same difficult level
- Translate Vietnamese to English
  - Word
  - Phrase
  - Sentence
  - Paragraph
## Backend requirements
### 1. Technology stack
### 2. Business logic
## FrontEnd requiremnts
### 1. Technology stack
### 2. Business logic
#### 2.1. Register screen
- Enter username, password to signup
#### 2.2. Main screen (after user login)
- Header: 
  - Name(Email)
  - Level
  - Learned time
  - Current point
  - Point need to reach next level
- Study list
  - Vocabulary
  - Grammar
  - Phrase
  - Sentence
  - Paragraph
  - Pronunciation
- Footer: Home - History - User setting 
#### 2.3. After user choose one in study list => Learning screen config
- Let user choose learn mode:
  - Random => take random data include easy, immediate and advance
  - Base on level => (A1, B1, B2, C1, C2)
  - Exam base on level and will have timing
    - Affect to current level (up/down/stay)
- Choose number of questions: 5, 10, 15, 20... => Begin learning
#### 2.4. Question screen
- Have header and footer and stop button => user can stop anytime
- In exam mode: will have clock
- Main frame for question
  - Question
  - Audio button to listen the question
  - Answer: Choose ABCD
#### 2.5. Result screen
- Total number of questions
- Number of correct and incorrect question
- Answer for each question
- Total score
- Confirm button to back to main screen
- Replay button to do again
#### 2.6. History screen
- Choose category: Vocabulary - Grammar...
- Below the above options: display all history list 
- After choose one of category above => History list
  - History list
    - Each item: Day - Mode - Number of question - Completion time - Score
      - (Score in mode are not exam mode will have gray color)
  - History detail screen (after click on an item in list)
    - Result after complete the lession => [Result screen](#result-screen)
## UI/UX requirements





