
NowNews is a scraper app that uses Mongoose and Cheerio to scrape news from the NPR website. Each scraped article will be saved to MongoDB.

Users are able to leave comments on the articles displayed and revisit them later accessing the "Saved Articles" link. The comments will be saved to the database as well and associated with their articles. Users are able to delete comments left on articles. All stored comments are visible to every user.

NPM Packages that I used: express, express-handlebars, mongoose, body-parser, cheerio and request.