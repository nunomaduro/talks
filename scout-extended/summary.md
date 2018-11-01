Laravel Scout provides a simple, driver based solution for adding full-text search to your Eloquent models.

But because [Laravel Scout](https://laravel.com/docs/scout) is search engine-agnostic, it keeps things basic. For indexing, this isn't an issue, as Scout will help keep everything in sync and format your data the way you want. But for search, it's limited.

In this talk, we will be using [Scout Extended](https://github.com/algolia/scout-extended), a library created by [Algolia](https://www.algolia.com) that extends Laravel Scout's Algolia driver adding Algolia-specific features.

You'll learn about the ideas behind this library. We'll also cover the most important features of Scout Extended, such as Aggregators, Zero Downtime Deployments, or the optimization of the search experience based on information from the model class.

This talk will include a 20 min live-coding session, where you will learn how to leverage Scout Extended to take the search experience of your website to the next level.
