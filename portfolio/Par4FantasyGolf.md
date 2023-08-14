// [Home](../index.md) // [Portfolio](../portfolio.md) // Par 4 Fantasy Golf

# Par 4 Fantasy Golf
[GitHub Repo](https://github.com/brianeatsbeets/Par-4-Fantasy-Golf)

![Leagues](https://github.com/brianeatsbeets/brianeatsbeets.github.io/assets/94752449/6d68b774-126f-4c92-86f8-eed17e52279b) ![Tournaments](https://github.com/brianeatsbeets/brianeatsbeets.github.io/assets/94752449/0a40a5c5-cb05-442c-975e-48bb7724a742) ![TournamentDetail](https://github.com/brianeatsbeets/brianeatsbeets.github.io/assets/94752449/1fd23914-bdb4-40f0-8fa1-ebd43fb71385)

![CreateTournament](https://github.com/brianeatsbeets/brianeatsbeets.github.io/assets/94752449/b368d683-5447-43c5-b4b8-14086fcdf43a) ![MakePicks](https://github.com/brianeatsbeets/brianeatsbeets.github.io/assets/94752449/4acc5d6f-b161-4dda-b474-a3972023a357) ![AddEditAthlete](https://github.com/brianeatsbeets/brianeatsbeets.github.io/assets/94752449/3b0b3581-6711-492c-a003-02761210cc8b)

Par 4 Fantasy Golf is a fantasy betting app for professional golf where you bet against friends instead of against the house. It was proposed by a friend of mine as a replacement for a complicated Excel document he was keeping to track picks and tournament results. The basic components are leagues and tournaments; leagues contain tournaments and users, and tournaments contain athletes and user picks. When creating a tournament, you can import odds data from a Google Sheet, and you can set a budget for making selections. Before a tournament begins, league members can select the athletes who they think have the greatest chance of winning, and those selections are solidified once the tournament begins. As the tournament progresses, scoring data will periodically be imported from an ESPN API, and league member rankings will be updated based on how well their selected athletes are performing. After a tournament ends, the winner is decided and the league rankings (based on tournament wins) are updated.

This application and its infrastructure are built with a tiny userbase in mind - this is purely a project for friends, and it uses the free tier of Firebase for data storage, which has very restrictive usage limits. Data fetching efficiency and UI design are currently structured for an MVP and will be refined annd updated in future releases.

Features:
- Authentication and database via Firebase
- Custom collection/table view cells and layout
- Diffable data sources
- Real-time view controller data source updates via Combine subscription
- Data fetching from ESPN API using async/await and decoding into usable models
- Import and parse from Google Sheets (csv)
