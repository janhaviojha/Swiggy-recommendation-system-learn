What this script actually implements
1. Data generation
   
   Creates 500 artificial users and 100 artificial restaurants.
2. Interaction simulation
   
   Simulates 5,000 sessions with 20 restaurants per session.
3. Label generation
   
   Uses a predefined mathematical formula to simulate whether a user orders.
4. Data preparation
   
   Splits interactions chronologically into training, validation and test datasets.
5. Feature engineering
   
   Derives historical spending, cuisine preferences, price gaps and contextual features.
6. Model training
   
   Trains Logistic Regression and Gradient Boosting.
7. Model evaluation
   
   Compares both ML models against a simple rating-and-distance baseline using NDCG@10.
8. Recommendation
   
   Predicts order probabilities and ranks the candidate restaurants.
