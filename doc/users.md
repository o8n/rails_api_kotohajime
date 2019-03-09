## GET /users
Works! (now write some real specs).

### Example

#### Request
```
GET /users HTTP/1.1
Accept: text/xml,application/xml,application/xhtml+xml,text/html;q=0.9,text/plain;q=0.8,image/png,*/*;q=0.5
Content-Length: 0
Host: www.example.com
```

#### Response
```
HTTP/1.1 200
Cache-Control: max-age=0, private, must-revalidate
Content-Length: 2
Content-Type: application/json; charset=utf-8
ETag: W/"4f53cda18c2baa0c0354bb5f9a3ecbe5"
X-Request-Id: c735f789-3d83-4a44-925e-d5aaf9f13113
X-Runtime: 0.014854

[

]
```
