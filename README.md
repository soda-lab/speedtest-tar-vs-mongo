# speedtest-tar-vs-mongo
Testing read speed of JSON files from Mongo VS Tar file.
# Result:
## Test file size:
* Number of records: 19659
## Read from Mongo:
* Dump collection:1.5s
* Restore collection: 1.5s
* Read data -> csv: 5s
**Total: 8s**
## Read from Tar:
* Export collection to json (jsonArray): 4.5s
* Compress json file: 1.5s
* Read data -> csv: 22.6s
**Total: 28.6s**
