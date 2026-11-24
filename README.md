# json

https://roadmap.sh/projects/js-json-response-normalizer

An API response often contains more data than your program needs. Normalize the response into a smaller list of published article summaries.

Write these functions:

getPublishedArticles(response) should return only articles where status is "published".

toArticleSummary(article) should return an object with id, title, authorName, and views.

normalizeArticles(response) should return summaries for published articles only.
