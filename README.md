# Knowledge-Graphs

docker run --rm --link janusgraph-default:janusgraph -e GREMLIN_REMOTE_HOSTS=janusgraph     -it docker.io/janusgraph/janusgraph:latest ./bin/gremlin.sh

g = TinkerGraph.open().traversal()

g.addV('person').property('name','chris')
