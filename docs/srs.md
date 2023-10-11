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
1. User
- Signup
  - Use phone number
    - Send OTP => verify OTP => create password => update password
  - Use email
    - Send OTP to email => verify OTP => create password => update password
  - Optional: Use OAuth2
    - TODO
- Login
  - Use phone or email and password to login
    - Enter email(phone) + password => backend verify => success/fail
- Logout
  - User click on button logout => logout and back to log in screen
- Profile
  - Name, phone, email, nation
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
2. Features
- Learn Vocalbulary, Grammar and Pronunciation
  - Random mode: easy to hard words
  - Level mode: depend on user level, the words will have same difficult level
- Translate Vietnamese to English
  - Word
  - Phrase
  - Sentence
  - Paragraph
## Backend requirements
1. Technology stack
2. Business logic
## FrontEnd requiremnts
1. Technology stack
2. Business logic
## UI/UX requirements





