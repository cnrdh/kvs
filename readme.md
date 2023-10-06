# kvs

Deno [KV](https://deno.com/kv) streaming storage service

REST-style API: manipulate stored values via HTTP GET,PUT, and DELETE

List streaming: All KV lists are streamed via
[SSE](https://developer.mozilla.org/en-US/docs/Web/API/EventSource) or NDJSON
(newline delimited JSON).
