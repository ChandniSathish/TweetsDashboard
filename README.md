Created a user friendly dashboard for popular tweets with given keywords.<br><br>
Details:
- <b>get_data.py</b> will search tweets for given keywords, do sentiment analysis and write into PostgreSQL database.
- Before executing <b>get_data.py</b>, You have to fill <b>credentials.py</b> for Twitter API, PostgreSQL database and keywords for twitter search.
- Tweepy is used for searching tweets and TextBlob is used for sentiment analysis.
- Tableau public doesnt support to connect PostgreSQL server. So I imported data from PostgreSQL database and convert it to excel file to upload Tabluea. <b>tweets.xlsx</b> is a sample of uploaded data.


Tableau Dashboard
<img src="https://user-images.githubusercontent.com/67562422/211403092-81ef63c6-b98d-4bba-828a-821095a9ba4b.png" width="1000" height="500" >



