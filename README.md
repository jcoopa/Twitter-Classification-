# Twitter-Classification-
This data contains tweets associated with terrorism, and random tweets not associated with terrorism. The goal is to reengineer this data so it is able to be ran through some type of intelligent algorithm, then run that reengineered data through your machine learning algorithm of choice, thus attempting to predict terroristic related tweets.   


Summary:
I have extensive training in several aspects of NLP including prediction which really came in handy with this.
I was suspicious of over-fitting but after comparing results from training & testing, then shuffling the data
and re-sampling, I’m still getting pretty much the same results. It was confirmed that the model performed "Very Well" on the none labeled data

• Both Test and Training data results show a 99% accuracy, consistent outcomes are a good sign.
• Time to complete is under 60 seconds. (Installing packages may extend this time)
• Advanced pre processing (key to great outcome)
• LSA
• K-Fold Cross Validation
• Tokenize
• Clean and Truncate text
• TFIDF
• svmLinear (othere tested, this was the best)
• Large (30%) sample data used to validate results
