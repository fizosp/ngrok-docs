<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-21T10:10:44Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2xOw4v037QyVmwKvpOwW4bFjcDp",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xOw4v037QyVmwKvpOwW4bFjcDp"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xOw5Z001DvduBGCc85Fpy7RLJk",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-21T10:10:44Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2xOw5Z001DvduBGCc85Fpy7RLJk",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-21T10:10:42Z",
      "hostport": "2cd3f15abcd9.ngrok.paid:443",
      "id": "ep_2xOw5HEGbjd35oCD3hZhfI1XcpY",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2xOw2pASVo2GNgAZTgwK6Ao5Xdc",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://2cd3f15abcd9.ngrok.paid",
      "tunnel": {
        "id": "tn_2xOw5HEGbjd35oCD3hZhfI1XcpY",
        "uri": "https://api.ngrok.com/tunnels/tn_2xOw5HEGbjd35oCD3hZhfI1XcpY"
      },
      "tunnel_session": {
        "id": "ts_2xOw5GS1P5R7vUznSEszLbvxBTh",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2xOw5GS1P5R7vUznSEszLbvxBTh"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-21T10:10:42Z",
      "upstream_url": "http://localhost:80",
      "url": "https://2cd3f15abcd9.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-21T10:10:39Z",
      "domain": {
        "id": "rd_2xOw4v037QyVmwKvpOwW4bFjcDp",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xOw4v037QyVmwKvpOwW4bFjcDp"
      },
      "edge": {
        "id": "edgtls_2xOw4s9T3LUVY3JBrSfRr3tHURL",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2xOw4s9T3LUVY3JBrSfRr3tHURL"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xOw4sJdCfE2X1R1QaYemrPjrKY",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-21T10:10:39Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
