# LDA for board game recommendations
A scratch patch for playing with latent Dirichlet allocation for board game recommendation.

Unfortunately it's too large to attach here, but the data was (painstakingly) scraped from [Board Game Geek](www.boardgamegeek.com). I will provide a template script as soon as it's cleaned up, but [this](https://github.com/ThaWeatherman/scrapers/tree/master/boardgamegeek)is probably a good starting point.

The dataset I ended up with consists of 10,000 games (which were all rated by at least 100 unique users), 238,483 unique user accounts and more than 18 million individual game ratings.

I used [Elasticsearch](www.elastic.co) in stead of a "real" database, because I wanted to learn how to use it so this provided enough of an excuse. I'm just noting that here, because I would probably have used SQLite or even MongoDB if that wasn't the case.

[pyLDAvis](https://github.com/bmabey/pyLDAvis) is an amazing library for visualising topic models, but unfortunately it does not display on GitHub. I'm busy organising my local files in a way that is more distributable and will add them here as soon as I can.
