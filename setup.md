# Setup
python -m nordlys.wikipedia.pageid_extractor -in /data/wikipedia/preprocessed-YYYYMMDD/ -o path/to/output/folder
```
python -m nordlys.wikipedia.merge_sf -redirects path/to/redirects.txt -anchors path/to/anchors_count.txt -titles path/to/page-id-titles.txt -o path/to/output/folder
```
mongoimport --db nordlys --collection surfaceforms_wiki_YYYYMMDD --file /path/to/sf_dict_mongo.json --jsonArray
```