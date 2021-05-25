# Medscribe - Hack The North 2019 (Winner of the Manulife Challenge)
https://devpost.com/software/medscribe

# Inspiration
Poor doctor's notes commonly lead to inaccurate diagnosis. We wish to provide a secondary transcript of all the information during the patient's visit so that they can understand their situation, and physician assistants can cross-check their notes.

# What it does
Medscribe allows doctors to speak into Google Assistant and produce a SOAP note (Subjective, Objective, Assessment, Plan) which is known as an effective note taking method that most doctors use. The platform takes these notes and summarizes it into a few sentences with all the crucial information. Once summarized, the notes are transferred to the Medscribe website where a profile is created/updated for the patient.

# How we built it
Medscribe was built using various languages and APIs. The Voiceflow API is used to get speech to text from Google Assistant. From there, we used the Google Spreadsheets API to transfer the notes to a machine learning model where they are summarized. Then, the summarized notes are sent via a Flask API to a Web App made with React.

# Built With
css

express.js

flask

google-drive-api

google-spreadsheets

html

javascript

python

react

voiceflow
