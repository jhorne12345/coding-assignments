
### Star Wars Coding Assignment

Create an API using Play Framework 2.5 in either Scala or Java 8.

Your API must do the following:
* Wrap the Star Wars API (http://swapi.co/) exposing a single endpoint: `/person/{id}`. Given that I call `/person/1`, for example, I expect to see the following information which you must obtain using various calls to the SWAPI api.

```
{
    "name": "Luke Skywalker",
    "homeworld": "Tatooine",
    "starshipsFlown": [
        {
            "name": "X-wing",
            "crew": "1",
            "passengers": "0"
        },
        {
            "name": "Imperial shuttle",
            "crew": "6",
            "passengers": "20"
        }
    ]
}
```
* Your API must be non-blocking.
* You must use only the tools provided by Play 2.5 - do not import any other libraries.

What we are looking for:
* We are interested in the readability, modularity, and testability of your implementation. Please imagine that this small example is going to turn into a larger application with 30+ endpoints and struture your code accordingly.

Do not commit your example onto a public repository. Please send us a zip file of your code. We will compile it locally and run it.
