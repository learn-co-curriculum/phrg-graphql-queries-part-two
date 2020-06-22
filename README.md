# Overfetching Queries

Chances are that in the last lesson you overfetched from the pokemon database. If not, good for you! Nevertheless, its good to recognize that GraphQL queries should only request what is needed and nothing more. When more than is needed is queried, it is called overfetching, and it is taxing on your database and response time.

For this lesson, we need to build GraphQL queries that **only** request what is asked for and nothing more.

## Pokemon

Use [Pokemon-GraphQL](https://graphql-pokemon.now.sh/) to form queries that only return the requested data.

1. Pokemon names and their respective fast attack names for the first 10 pokemon.
1. The amount required for Squirtle to evolve, the name of Squirtle's evolutions, the amount required for those evolutions to evolve again, and the names of the Squirtle's evolved evolutions.
1. The minimum wieght and height of the first 5 pokemon, along with their number.
1. Sandshrew's classification, weaknesses, types, and image url.

## Geography

Besides Pokemon, we also want to drill into some info geography. And GraphiQL is not the only GraphQL Interactive Development Environment (IDE) out there. Use [this countries](https://countries.trevorblades.com/) GraphQL IDE to form queries that only return the requested data. Be sure to explore "docs" tab on the right of the page.

1. All the continent names.
1. All countries names and their capitols.
1. All countries names, codes, and all the languages spoken in each country.
1. The code for Brazil is "BR". Query for its name, native name, phone code, flag (emoji), and all of its states.
1. The code for Dutch is "nl". Query the language's name, whether it reads right-to-left, and what it is referred to natively.
1. The code for Europe is "EU". Query the continent's name, and its countries names and currencies.
