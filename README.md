# Feedback_Forms
Feedback Forms
### In this script, we're using the getpass function from the getpass module to hide the user's input when they're typing their feedback. This is to avoid any potential issues with displaying potentially sensitive feedback on the screen. If this isn't a concern for you, you can replace getpass with the standard input function.

After each descriptive feedback answer, we're running sentiment analysis using Hugging Face's sentiment analysis pipeline, and then saving the sentiment alongside the feedback in the answers list. Then, when we write the feedback data to the CSV file, each row will consist of the rating, the descriptive feedback, and the sentiment of the feedback.
