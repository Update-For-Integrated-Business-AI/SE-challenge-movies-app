# Movies App Challenge

## Challenge
### Background

It’s COVID all over again and our customers are staying home. Our data showed that they love to watch movies but they are having a hard time picking what to watch (who doesn’t?). So we decided to create an app to help them do just this. You are the hero, our mobile team is dependent on you to provide them with APIs for the app.

### Task

We want to create an backend app using any programming language, library or framework to **collect, store and display movie information to our users.** To be able to provide our users with the best experience we will collect data from both local and international sources. Sadly, all the sources are not consistent with each other so we have to support input from different data-sources:

- Local list movies (Excel sheet)
- Gov. agency (CSV)
- IMDB API (API 🤷)
- Netflix Top 10 (API)

> A local TV producer has a great list of movies but they are in HTML so we have plans to support HTML but this will be in a later stage.

To display the data correctly to the user we should make sure that we store the data such that:

- There are no duplicated movies in the database.
- We can retrieve which data-sources we collected movies from.

Provide an API so that the **mobile app allows users to:**

- List movies sorted by rating and popularity.
- Show movie details.
- Show movie data-sources.
- Add movies to watch list.

**Bonus:**

- We want to store versions of movies from datasources to be able to provide historical data in the future (like rating/popularity) change overtime.
- System should provide a heartbeat endpoint for the uptime and health monitor.
- Mobile team prefers to use graphql instead of REST.

## Instructions
How to attempt this challenge:

1. Create a new repo in your account and note the git url
2. Clone this repo
3. Solve the challenge
4. Set your new repo as the origin: git remote set-url origin ${your repo url}
5. Push your solution to your repo
You must follow these steps for your solution to be accepted -- forks or other methods will not be considered.
