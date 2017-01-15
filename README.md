# CollaborTweet

This code is a framework for assessing text documents using a collaborative, online framework. It's written in Node.js and makes heavy use of third-party packages, like Express, Sqlite, etc.

This framework was initially developed to impose an ordering over a textual data set using pairwise comparisons (not unlike [SentimentIt](https://www.sentimentit.com)). The original task was to evaluate emotional intensity of Twitter data by providing users with a pair of tweets and asking them to assess which one exhibits a more negative feeling. This framework can support any such task using textual data and is not restricted to Twitter data, though I suggest short-form text rather than long documents.

The framework is also designed to support multiple users and multiple tasks, but these settings are only vaguely implemented. The system currently supports a single task, and users are specified by a file (users.js) in the users directory. One or both of these features should be implemented soon.

## Setup

You should be able to use `npm install` to set up the server and download any dependencies. Then, `npm start` will run the server, which you can access (currently) at [http://localhost:3000]. 