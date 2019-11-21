# ipfsmap
Tile server based on IPFS

It is a small project that unifies openstreetmap.org along with ipfs

The aim is to create a free tile server system for developers who are creating map featured apps.

Resources for this pourpose are heavy in data storage and transmission. Now they can be soften.

This project is a hybrid between classic and distributed web … it will be modified to be as distributed as it can, the good news is that it could run on a personal computer, meaning that the system could be, not too hard to spread over different developers who need a free tile server, and, replication of this system would help it self … the main feature is that the map is dynamic (meaning that the map changes over time) tiles would update every 14 days, depending on the number of times a tile is requested (and configuration) …

Source code is for illustration pourposes, by the moment, downloads will be soon fully functional.

It should run in a http server environment, along with a ipfs node … every request, it would add files (if needed) to ipfs and responds with a http redirection to a randomly chosen gateway … (the list is short and static, by the moment) and i think it would be nice to, also, communicate with the ipfs network through js-ipfs by creating an instance in the browser …

Try a live demo here: http://pulsartronic.duckdns.org/

to be continued :) ... (i have 20 minutes a day (or less) to work on this :()
