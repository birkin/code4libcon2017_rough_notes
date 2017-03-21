### lightning talks...

#### MQTT -- lightweight tcp/ip protocol for publish-subscribe
- ian
- mosquitto
- just publish to a topic; hierarchical
- QoS levels, from 0 to 2 (2 being once, with 4-step handshake)
- reason: bandwidth and battery-life
    - http polling is expensive
- lots of libraries to work with this


#### ArcLight
- mark
- blacklight-based discovery system for discovery & delivery of archival materials
- community-based design team


#### Patron data

what are we keeping?

PII-1 - data about person

PII-2 - data about a person's activities

how to balance patron privacy with operational needs?

case 1, data warehouse
- all data going into warehouse is de-identified, and an id is sha-256 with salt

case 2, city open data initiative
- they should be good to go, but still concerns about fuzzy-matching
- 3 data points -- know how other data-sets can affect your data

Vendors have lots of data

See read, plan, act slide


#### finding aid...

"automation and the dignity of the archivist" -- http://archivaria.ca/index.php/ca/article/view/13030

1990 -- RAD - canadian archival description standard

AtoM in Canada


#### Building Bibliographic rdf applications and microservices

[pre-conf link](http://2017.code4lib.org/workshops/Building-Bibliographic-RDF-Applications-and-Microservices)


#### linked data + archives + special collections

zepheira - bibframe - libhub initiative (2014-2015) - library-link network (2015-present)


mark -> bibframe -> to others -> publish in schema.org & others -> can be consumed

human friendly & machine-optimized side

working now with special collections -- tx state, 35,000 records, & VIVA (multi virginia institutions, 100,000 + records)

separate domains, allows ownership of (open) data

consuming & using
organic/direct

really worth seeing these slides again

---

---


### solrmarc upgrade

[link](http://2017.code4lib.org/talks/SolrMarc-the-Next-Generation)

easier to upgrade, faster, more features, easier to add more features -- 17.5 hours to 1 hour

credit to dev from finland

---


### Coordinated Discovery: UW-Madison's approach to building its library discovery platform

[link](http://2017.code4lib.org/talks/Coordinated-Discovery-UWMadisons-approach-to-building-its-library-discovery-platform)

- bruce barton

- uncoordinated discovery -- lots of buckets
    - all have their own search interfaces & look different

coordinated...

- wayfinding

- carry search string foward

- check other buckets in background and advertise close matches
    - close matches for known items
    - "we also suggest"

- generating search suggestions -- passing search to suggestion service -- cool
    - knows kind of search, and bucket from which it came from
    - longer than four words: try articles too
    - cat author, try dig-creator
    - etc

- evaluate when they come back
    - 'closeness of fit'
        - levenshtein distance of string matching on titles
        - break nmaes 'Jaccard index'

- advertise result
    - either link to item, or link to search in other bucket

- suggestion service allows curated search terms

---


### How the distributed web could bring a new Golden Age for Libraries

[link](http://2017.code4lib.org/talks/How-the-distributed-web-could-bring-a-new-Golden-Age-for-Libraries)

slightly new topic...

has been helping save fed govt data

- matt zumwalt

- centralized, decentalized, distributed (latter two are under decentralized term)

- data rescue

- "storing data together"

- data rescue -- lots of orgs -- datarefuge, IA, EDGI, climate mirror, code for science, protocol labs

- so now, lots of data has been downloaded, now what...

- grassroots effort to decentralize government data, would be foolish to re-centralize

- web itself precarious
    - location-addressed farce
    - no way to reconcile the single url identifier with copies

- peers coordinating
    - please hold copy at lib; i have copy, let others know; i have free storage, you can store a piece of something there

- content addressing

- cryptographic hashes yield unique identifier

- accession without upload

- share hash with folk who might want to pull copy of data
    - me: what would be an approach to link the evolution of data

- accession feeds of data
    - aaron schwartz's idea of rss feeds

- metadata catalogs are data-sets

- distributed network of people and devices
    - instead of worrying about folk not going to library,

- decentralization: literal sense, and socio-economic sense of who gets to be a peer
    - patrons are clients / consumers, not 'peers' -- interesting to think of patrons of peers
    - when libs interact with peers, that's when rich goodness happens

- ipfs.io, datatogether.x

- protocol labs working on ip address clustering / lockss architecture has already addressed redundancy concerns  -- avatars will be released

---


### Automating Audio & Moving Image Access Copy Creation with Elastic Transcoder, in Seussian Rhyme

[link](http://2017.code4lib.org/talks/Automating-Audio-Moving-Image-Access-Copy-Creation-with-Elastic-Transcoder-in-Seussian-Rhyme)

- stephen schor; omg, in suessian rhmye

- elastic transcoder

- pipelines...
    - offer notifications

- process and events scriptable, notifiable i think

---


### Moving Beyond the Lone Digital Archivist Model Through Collaboration and Living Documentation

[link](http://2017.code4lib.org/talks/Moving-Beyond-the-Lone-Digital-Archivist-Model-Through-Collaboration-and-Living-Documentation)

- princeton archivists
    - manuscripts division, u-archives & public policy

- set up bit-curator box, with other hardware -- processing archivists to digital archivists

- born digital archive working group -- reading group and workshop model

- living documentation
    - comments for links
    - reflection document

---

[END]

