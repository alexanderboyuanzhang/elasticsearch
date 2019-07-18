# elasticsearch

### Prerequsities

`$ java -version`

### Install Elasticsearch on Ubuntu

1.  Run `bin/elasticsearch` (or `bin\elasticsearch.bat` on Windows)

### Configure Elasticsearch

`sudo nano config/elasticsearch.yml`

change the following values:

`network.host: 0.0.0.0`
`cluster.name: myCluster1`
`node.name: "myNode1"`

### Launch Elasticsearch

Run `curl http://localhost:9200/` or `Invoke-RestMethod http://localhost:9200` with PowerShell

### References

<https://www.elastic.co/downloads/elasticsearch>
