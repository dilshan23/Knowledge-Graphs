# Knowledge-Graphs

docker run --rm --link janusgraph-default:janusgraph -e GREMLIN_REMOTE_HOSTS=janusgraph     -it docker.io/janusgraph/janusgraph:latest ./bin/gremlin.sh

docker run -it -p 8182:8182 janusgraph/janusgraph

g = TinkerGraph.open().traversal()

g.addV('person').property('name','chris')
