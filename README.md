# ge-wiki-parser

Parses game data and spits out wiki formatting. Deals with localised strings by providing an interface to all sheets at the same time. MULTI LANGUAGE DRIFTING

Partially based upon an older project to port all the data to a SQL db

todo: fix this readme lol


## Usage

    ge-wiki-parser <data path> <parser name> [module] [args] [here...]
    
## Notes

* Parsers are located in the Parsers namespace and only parsers inside that namespace can be used.