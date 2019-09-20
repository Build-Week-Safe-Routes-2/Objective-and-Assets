[Notion](https://www.notion.so/Full-Time-Build-Sprint-Culture-Document-19e679fc1a284b668d8132dd8d7228cd)

Clone this document and answer the prompts to the best of your team's ability

# Proposal

---

- What problem does your app solve?

  - Users have the ability to avoid the most dangerous intersections in a given area.

- Be as specific as possible; how does your app solve the problem?

  - The area can include a city, state, or a country by displaying information to users to avoid congested or dangerous areas.

- What is the mission statement?
  - Make driving safer one interesection at a time with cloud-based and continuous integration machine learning to provide a user experience that is unparalleled. AWS.

# Features

---

## Web?

- What features are required for your minimum viable product?

  - Address / Intersection input field
  - Interactive Map showing crash statistic for a given intersection
  - Show historical crashes on the map for given time period
  - Visualization should indicate the likelihood of crashes at different locations
  - MVP should have a limited geographic scope

- What features may you wish to put in a future release?
  - Starting + ending destination and map the safest route

* What do the top 3 similar apps do for their users?
  - Google Maps
  - Waze
  - CrimeWatch

## Data Science

- What features are required for your minimum viable product?

  - Create a model that predicts the odds of an accident occuring at a given interesction.

- What features may you wish to put in a future release?

  - Predict the odds for the any given state in the country

- What do the top 3 similar apps do for their users?
  - Google Maps
  - Waze
  - CrimeWatch

# Design - Planning

---

_Optional but highly recommended_
_Please refer to this document:_

[Build Weeks: Planning & Design Worksheet (How to build a beautiful application)](https://www.notion.so/aabd4ef25a184a2085e511ce93480c0f)

- What design system will you use?

  - Figma

- What will your user flow be?
  - Landing page -> Application

* What is the URL to your wireframes?
  - [NA](#)

# Frameworks - Libraries

---

- What 3rd party frameworks/libraries are you considering using?

  - Plotly, Google Maps/Wayze API, Axios, Formik, UI libs, Yup,
  - Anaconda
  - Express
  - JWT
  - Flask

- Do APIs require you to contact its maintainer to gain access?
  N/A

- Are you required to pay to use the API?
  N/A

- Have you considered using Apple Frameworks? (MapKit, Healthkit, ARKit?)
  Never

# For Data Scientists

---

- Describe the Established data source with at least rough data able to be provided on day 1.

  - NHTSA data set provided with airtable

- You can gather information about the data set you’ll be working with from the project description. Be sure to collaborate with your PM, and your Backend Architect to chat about the resources you have.

  - Ok

- Write a description for what the DS problem is (what uncertainty/prediction are we trying to do here? Sentiment analysis? Why is this a useful solution to a problem?)
  - Predicting the rate of accidents at a given intersection and translating that into a danger rating
  - Having a really high validity score so that we are confidently asserting that the rate of accidents will be accurate

* A target (e.g. JSON format or such) for output that DS students can deliver to web/other students for them to ingest and use in the app
  - JSON

# Target Audience

---

- Who is your target audience? Be specific.

  - The general public looking for disruptive, cloud-based applications to assist their day to day life.

- What feedback have you gotten from potential users?

  - This application sounds wonderful

- Have you validated the problem and your solution with your target audience? How?

## Research

---

- Research thoroughly before writing a single line of code. Solidify the features of your app conceptually before implementation. Spend the weekend researching so you can hit the ground running on Monday.

# Prototype Key Feature(s)

---

- This is the “bread and butter” of the app, this is what makes your app yours. Calculate how long it takes to implement these features and triple the time estimated. That way you’ll have plenty of time to finish. It is preferred to drop features and spend more time working on your MVP features if needed.
