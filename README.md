# Interlok Solace WMQ

This demo's integration between solace and webphsereMQ with the following channels.

![Sequence](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/quotidian-ennui/interlok-solace-wmq/main/docs/sequence-diagram.puml)

## Quickstart

- Create a file "src/main/interlok/config/license.properties" that contains your license key
   - `adp.license.key=XXXXX` -> if you're using 4.2+ then a license key is no longer required
- `./gradlew -PbuildEnv=dev build`
- `docker-compose up -d` (to start up your local docker solace/websphereMQ images)
- `(cd build/distribution && java -jar lib/interlok-boot.jar)`

## Further Reading

- https://interlok.adaptris.net/interlok-docs
- https://github.com/adaptris/interlok
- https://twitter.com/InterlokDev

## Learning about the parent gradle

- https://github.com/adaptris/interlok-build-parent
- https://github.com/adaptris-labs/build-parent-json-csv
- https://github.com/adaptris-labs/interlok-install-builder (this is a basic example of using the parent-gradle)
