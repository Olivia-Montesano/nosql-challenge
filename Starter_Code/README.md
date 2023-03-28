Initially I set up the database and update it. I imported a JSON file using mongoimport, then added "Penang Flavours" to the data. I then updated the collected with the required values and deleted all those that are unnecessary. Then I converted latitude and longitude to floats.

Then for the analysis:
1. 41 establishments have a hygiene score of 20, including The Chase Rest Home and Brenalwood.
2. 34 establishments in London have a RatingValue greater than or equal to 4, including Charlie's and Mv City Cruises Erasmus.
3. The top 5 establisments with a RatingValue of 5, nearest to 'Penang Flavours' are: 1.) TIWA N TIWA African Restaurant Ltd, 2.) Fineway Cash & Carry, 3.) Lucky Food & Wine, 4.) Premier Express, and 5.) Everest Stores Ltd
4. 55 Local Authorities have establishments with a hgiene score of 0. The Local Authorities with the most establishments with a hygiene score of 0 are: 1.) Thanet, with 1130 , 2.) Greenwich, with 882, and 3.) Maidstone, with 713.