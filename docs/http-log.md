# HTTP Request Log
## Request 1: Fetching a Post (Valid Request)
**Command:**
curl -i https://jsonplaceholder.typicode.com/posts/1

**Response:**
HTTP/1.1 200 OK
Date: Sun, 16 Aug 2026 13:12:16 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 292
Connection: keep-alive
access-control-allow-credentials: true
Cache-Control: max-age=43200
etag: W/"124-yiKdLzqO5gfBrJFrcdJ8Yq0LGnU"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=PD3aZ5JXmnXLLbuM9yuy2jwg6ke8U5C2Yq%2BT0erzkj0%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1775729378"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=PD3aZ5JXmnXLLbuM9yuy2jwg6ke8U5C2Yq%2BT0erzkj0%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1775729378"
Server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 730
x-ratelimit-reset: 1775729393
Age: 17217
Accept-Ranges: bytes
cf-cache-status: HIT
CF-RAY: a2c0b0902eeffe1e-SIN
alt-svc: h3=":443"; ma=86400

{
  "userId": 1,
  "id": 1,
  "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
  "body": "quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas totam\nnostrum rerum est autem sunt rem eveniet architecto"
}



## Request 2: Fetching a User (Valid Request)
**Command:**
curl -i https://jsonplaceholder.typicode.com/users/1

**Response:**
HTTP/1.1 200 OK
Date: Sun, 16 Aug 2026 13:13:43 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 509
Connection: keep-alive
access-control-allow-credentials: true
Cache-Control: max-age=43200
etag: W/"1fd-+2Y3G3w049iSZtw5t1mzSnunngE"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=lsI%2BTfv1uK9A%2Fjv%2BW39yM97aGEcVYb%2BtylNf0aAFsdQ%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786877577"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=lsI%2BTfv1uK9A%2Fjv%2BW39yM97aGEcVYb%2BtylNf0aAFsdQ%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786877577"
Server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 937
x-ratelimit-reset: 1786877625
Age: 8445
Accept-Ranges: bytes
cf-cache-status: HIT
CF-RAY: a2c0b2b13846ed99-SIN
alt-svc: h3=":443"; ma=86400

{
  "id": 1,
  "name": "Leanne Graham",
  "username": "Bret",
  "email": "Sincere@april.biz",
  "address": {
    "street": "Kulas Light",
    "suite": "Apt. 556",
    "city": "Gwenborough",
    "zipcode": "92998-3874",
    "geo": {
      "lat": "-37.3159",
      "lng": "81.1496"
    }
  },
  "phone": "1-770-736-8031 x56442",
  "website": "hildegard.org",
  "company": {
    "name": "Romaguera-Crona",
    "catchPhrase": "Multi-layered client-server neural-net",
    "bs": "harness real-time e-markets"
  }
}





## Request 3: Fetching a Comment (Valid Request)
**Command:**
curl -i https://jsonplaceholder.typicode.com/comments/1

**Response:**
HTTP/1.1 200 OK
Date: Sun, 16 Aug 2026 13:14:11 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 268
Connection: keep-alive
access-control-allow-credentials: true
Cache-Control: max-age=43200
etag: W/"10c-KJ4I9RM/+33TKdV8CFsIvqsDSP0"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=juUFUla4sclQXiOziFb%2B7LWRR7Hh%2BVY8G8E%2Bpbnmoo8%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786868245"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=juUFUla4sclQXiOziFb%2B7LWRR7Hh%2BVY8G8E%2Bpbnmoo8%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786868245"
Server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 996
x-ratelimit-reset: 1786868262
Age: 17806
Accept-Ranges: bytes
cf-cache-status: HIT
CF-RAY: a2c0b360adf3f881-SIN
alt-svc: h3=":443"; ma=86400

{
  "postId": 1,
  "id": 1,
  "name": "id labore ex et quam laborum",
  "email": "Eliseo@gardner.biz",
  "body": "laudantium enim quasi est quidem magnam voluptate ipsam eos\ntempora quo necessitatibus\ndolor quam autem quasi\nreiciendis et nam sapiente accusantium"
}




## Request 4: Fetching a Todo Item (Valid Request)
**Command:**
curl -i https://jsonplaceholder.typicode.com/todos/1

**Response:**
HTTP/1.1 200 OK
Date: Sun, 16 Aug 2026 13:14:57 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 83
Connection: keep-alive
access-control-allow-credentials: true
cache-control: max-age=43200
etag: W/"53-hfEnumeNh6YirfjyjaujcOPPT+s"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=o3LnB4y9klD2bC%2B9j%2F4juYbUmCEOESrp8RutkrsBB%2BY%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1776956825"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=o3LnB4y9klD2bC%2B9j%2F4juYbUmCEOESrp8RutkrsBB%2BY%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1776956825"
Server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1776956878
Age: 3
Accept-Ranges: bytes
cf-cache-status: HIT
CF-RAY: a2c0b47fbb91a085-SIN
alt-svc: h3=":443"; ma=86400

{
  "userId": 1,
  "id": 1,
  "title": "delectus aut autem",
  "completed": false
}





## Request 5: Deliberate Failure (Not Found)
**Command:**
curl -i https://jsonplaceholder.typicode.com/posts/99999

**Response:**
HTTP/1.1 404 Not Found
Date: Sun, 16 Aug 2026 13:15:46 GMT
Content-Type: application/json; charset=utf-8
Content-Length: 2
Connection: keep-alive
access-control-allow-credentials: true
Cache-Control: max-age=43200
etag: W/"2-vyGp6PvFo4RvsFtPoIWeCReyIC8"
expires: -1
nel: {"report_to":"heroku-nel","response_headers":["Via"],"max_age":3600,"success_fraction":0.01,"failure_fraction":0.1}
pragma: no-cache
report-to: {"group":"heroku-nel","endpoints":[{"url":"https://nel.heroku.com/reports?s=J4Z76OisLXhMrx7C6hPF7L50sF4Cjb3TNY2TniMt6pc%3D\u0026sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d\u0026ts=1786883327"}],"max_age":3600}
reporting-endpoints: heroku-nel="https://nel.heroku.com/reports?s=J4Z76OisLXhMrx7C6hPF7L50sF4Cjb3TNY2TniMt6pc%3D&sid=e11707d5-02a7-43ef-b45e-2cf4d2036f7d&ts=1786883327"
Server: cloudflare
vary: Origin, Accept-Encoding
via: 2.0 heroku-router
x-content-type-options: nosniff
x-powered-by: Express
x-ratelimit-limit: 1000
x-ratelimit-remaining: 999
x-ratelimit-reset: 1786883385
Age: 2819
cf-cache-status: HIT
CF-RAY: a2c0b5b018ca1d3a-SIN
alt-svc: h3=":443"; ma=86400

{}