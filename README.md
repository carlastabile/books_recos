# 📚 Book Recommendations from tweets 📚

A tiny script to fetch tweets about reading books and recommending them from people I follow and admire. Because of reasons I'm not sharing the list of users I use, so just use your own users. 🤓 

The original script is from the [Twitter docs](https://developer.twitter.com/en/docs/twitter-api/tweets/search/introduction).

## Set up 
1. Get your own Twitter developer account and get a Bearer Token 
2. Create a .env file in the root of the project with the `BEARER_TOKEN` variable and set your token there.
3. Create a users.txt file in the root folder and define the Twitter usernames you want to "scrape" from without the @. Example: 

  `users.txt`:
  ```
  CarlaStabile
  SomeOtherCoolUsername
  ButNotCoolerThanMine
  ```

4. Run the script `ruby tweets.rb`

As for now I'm only printing the text of the tweets, the goal would be to apply so more analysis on them but that is not going to happen today. 


## Contributing 
If you happen to run into this repo and feel generous feel free to submit a PR. I always appreaciate some collab. 🤩
