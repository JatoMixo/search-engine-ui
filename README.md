# Search Engine UI
A small UI intended for a Search Engine, built with astro.

[The Search Engine](./SearchEngine.png)

## Documentation
The project contains the following components:
- `SearchBar` => The actual search bar for typing the query
- `Result` => A Web Result from a query, showing the title of the website, a small description and the score it received based on an algorithm for matching websites with the query.
- `ScoreDisplayer` => The circle displaying the score in the `Result` component, separated for easier reading and editing of the code.

It also contains the following pages:
- `/` => The Search Engine main page, with the search bar
- `/results` => A small example of how the `Result` component looks like