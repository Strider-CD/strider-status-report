[![NPM](https://nodei.co/npm/strider-status-report.png)](https://nodei.co/npm/strider-status-report/)

strider-status-report
=====================

Creates a status report for strider

### Example

```
keyvan@luchia.local:~/P/S/strider-status-report git:fix ❯❯❯ http get localhost:3000/ext/status-report/jobs                             ⏎ ✱ ◼
HTTP/1.1 200 OK
Connection: keep-alive
Content-Length: 594
Content-Type: application/json; charset=utf-8
Date: Mon, 11 Aug 2014 15:21:49 GMT
ETag: "338269429"
Set-Cookie: connect.sid=s%3A5bZiMQfZ5fTUgBrO54nBR2oA.TCV6%2FEYBPkro8f0MIu0ag8Xv5E2HJtxr%2BXprDrlBi%2Fg; Path=/; Expires=Thu, 11 Sep 2014 01:50:52 GMT; HttpOnly
Vary: Accept-Encoding
X-Powered-By: Express

[
    {
        "project": "some-project",
        "branches": [
            {
                "name": "master",
                "finished": "2014-10-14T10:11:00.231Z",
                "data": {
                    "deploy_exitcode": -1,
                    "test_exitcode": 0,
                    "plugin_data": {
                        "node": {
                            "testCmd": "passed",
                            "doTest": true
                        }
                    }
                }
            },
            {
                "name": "some-feature-branch",
                "finished": "2014-10-14T10:11:00.231Z",
                "data": {
                    "deploy_exitcode": -1,
                    "test_exitcode": 0,
                    "plugin_data": {
                        "node": {
                            "testCmd": "passed",
                            "doTest": true
                        }
                    }
                }
            }
        ]
    },
    {
        "some-other-project",
        "branches": [
            {
                "name": "master",
                "finished": "2014-10-14T10:11:00.231Z",
                "data": {
                    "deploy_exitcode": -1,
                    "test_exitcode": 0,
                    "plugin_data": {
                        "node": {
                            "testCmd": "passed",
                            "doTest": true
                        }
                    }
                }
            },
            {
                "name": "some-feature-branch",
                "finished": "2014-10-14T10:11:00.231Z",
                "data": {
                    "deploy_exitcode": -1,
                    "test_exitcode": 0,
                    "plugin_data": {
                        "node": {
                            "testCmd": "passed",
                            "doTest": true
                        }
                    }
                }
            }
        ]
    }
]
```
