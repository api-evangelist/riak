# Riak KV (riak)

Riak KV is a distributed NoSQL key-value database originally developed by Basho Technologies, designed for high availability, fault tolerance, and horizontal scalability across commodity hardware. Riak exposes two client-facing APIs: a RESTful HTTP API for basic GET, PUT, POST, and DELETE operations, and a higher-performance Protocol Buffers (PBC) API spoken over TCP. Both APIs support buckets, objects, secondary indexes, search, MapReduce, and CRDT data types.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/riak/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/riak/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Database
- NoSQL
- Key-Value Store
- Distributed Systems
- Open Source
- Basho
- CRDT

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Riak KV HTTP API

RESTful HTTP API for Riak KV providing GET, PUT, POST, and DELETE access to buckets, objects, secondary indexes, search, MapReduce, and CRDT data types. Default port is 8098. Authentication and authorization are configured via Riak security on the server.

- **Human URL:** [https://docs.riak.com/riak/kv/latest/developing/api/http](https://docs.riak.com/riak/kv/latest/developing/api/http)
- **Base URL:** `http://<your-riak-host>:8098`

#### Tags

- HTTP API
- Key-Value
- Buckets
- MapReduce
- Secondary Indexes

#### Properties

- [Documentation](https://docs.riak.com/riak/kv/latest/developing/api/http)
- [H T T P  Bucket  Operations](https://docs.riak.com/riak/kv/latest/developing/api/http/list-buckets.1.html)
- [H T T P  Object  Operations](https://docs.riak.com/riak/kv/latest/developing/api/http/fetch-object.1.html)
- [Postman Collection](collections/riak.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/riak.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Riak Protocol Buffers Client API

Higher-performance binary client API for Riak KV using Protocol Buffers messages encoded over a long-lived TCP connection. Default port is 8087. Each request message produces one or more response messages on the same connection. Message definitions are published in the open source basho/riak_pb repository.

- **Human URL:** [https://docs.riak.com/riak/kv/latest/developing/api/protocol-buffers](https://docs.riak.com/riak/kv/latest/developing/api/protocol-buffers)
- **Base URL:** `pb://<your-riak-host>:8087`

#### Tags

- Protocol Buffers
- PBC
- Binary Protocol
- Key-Value
- High Performance

#### Properties

- [Documentation](https://docs.riak.com/riak/kv/latest/developing/api/protocol-buffers)
- [Message  Definitions](https://github.com/basho/riak_pb)
- [Encoding  Reference](https://docs.riak.com/riak/kv/latest/developing/api/protocol-buffers/index.html)
- [Postman Collection](collections/riak.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/riak.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://riak.com)
- [Documentation](https://docs.riak.com/riak/kv/latest/)
- [A P I  Documentation](https://docs.riak.com/riak/kv/latest/developing/api/)
- [GitHub Organization](https://github.com/basho)
- [Source  Code](https://github.com/basho/riak)
- [Protocol  Buffers  Repo](https://github.com/basho/riak_pb)
- [Client  Libraries](https://docs.riak.com/riak/kv/latest/developing/client-libraries/)
- [Download](https://docs.riak.com/riak/kv/latest/setup/installing/)
- [License](https://github.com/basho/riak/blob/develop/LICENSE)
- [L L Ms Txt](https://docs.riak.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
