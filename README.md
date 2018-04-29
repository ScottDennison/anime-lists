# anime-lists

Repository to store and provide the title and mapping lists of the website http://myanimelist.net.

### MyAnimelistTitleListMapping
Contains the Java programm to generate the lists. The programm relies on Maven as build process. When you build the program it will create a config.properties files with the necessary properties used.

Note: you need a key for the API of both https://themoviedb.org and https://www.thetvdb.com/

### anime-lists/anime-mapping/
contains the lists of mappings between Myanimelist, TheMovieDB and TheTVDB

Note: this list only contains available entries so for example the myanimelist with ID 2 is not available and therefore there is no mapping for it available.

### anime-lists/anime-titles/
contains the available titles (japanese, synonyms, english) all IDs on myanimelist.

Note: this list also contains unavailable entries!
