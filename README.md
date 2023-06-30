# Feedback_Forms
Feedback Forms
### In this script, we're using the getpass function from the getpass module to hide the user's input when they're typing their feedback. This is to avoid any potential issues with displaying potentially sensitive feedback on the screen. 
If this isn't a concern for you, you can replace getpass with the standard input function.

After each descriptive feedback answer, we're running sentiment analysis using Hugging Face's sentiment analysis pipeline, and then saving the sentiment alongside the feedback in the answers list. Then, when we write the feedback data to the CSV file, each row will consist of the rating, the descriptive feedback, and the sentiment of the feedback.
 ### UPDATES
Instead of just asking users to rate an instructor's performance on a scale of 1-5, we can also ask them to provide a few sentences explaining their rating. The sentiment of these sentences can then be analyzed using a sentiment analysis library or service. We can then correlate these sentiments with the numerical ratings.
# # feedback_form_tutorials
