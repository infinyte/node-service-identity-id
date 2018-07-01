# @infinyte/node-service-identity-id [![travis][travis-image]][travis-url]

#### Create, parse and unparse service identity id's using RFC 4122 v4 UUIDs.

### Summary
A NodeJS helper which creates a UUID that is composed of a combination of details derived from a host's internal configuration details combined with a randomly generated value.  The resulting UUID can then be used as an identity token for service discovery and proxy/reverse-proxy traffic within a SOA or Microservice based system architecture.

##UUID Source Object Structure
- Hostname : string
- MAC Address : string
- IP Address : [] string (?? Perhaps only the most recent IP, or the last X most recent )
- RFC 4122 v4 UUID : string
