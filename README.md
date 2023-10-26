# Twimber App

The Twimber App is a simple web application that allows users to create, view, and interact with tweet-like posts. It's built using HTML, CSS, and JavaScript, and it includes features such as posting new tweets, liking tweets, retweeting, replying to tweets, and deleting tweets.

## Features

- **Posting Tweets:** Users can enter text in the input field and click the "Tweet" button to create a new tweet.

- **Liking Tweets:** Each tweet can be liked by clicking the heart icon. Clicking it again unlikes the tweet.

- **Retweeting:** Users can retweet tweets, and the retweet count is displayed on each tweet.

- **Replying to Tweets:** Replies can be viewed by clicking the comment icon on a tweet, revealing a list of replies.

- **Deleting Tweets:** Users can delete their own tweets by clicking the trash can icon.

- **Local Storage:** The app uses local storage to store the tweets' data, allowing the user to refresh the page without losing their data.

## Usage

To use the Tweet Feed App, follow these steps:

1. Clone or download the project to your local machine.

2. Open the `index.html` file in a web browser to run the application.

3. You can interact with the app by posting tweets, liking tweets, retweeting, replying to tweets, and deleting tweets.

4. The app will automatically save your data using local storage, so you can return to your tweets even after closing the browser.

## Built With

- HTML, CSS, and JavaScript
- [UUID](https://github.com/uuidjs/uuid) library for generating unique tweet IDs

## To Do

There are some issues surrounding the delete button, where all tweets can be deleted instead of just the users. I am working on fixing this bug.

## Author

Benjamin Seed
