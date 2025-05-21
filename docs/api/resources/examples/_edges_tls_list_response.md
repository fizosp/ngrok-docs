<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-05-21T10:10:49Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2xOw6ACtEdsXrYMBAswVK8JVxCZ",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xOw6ACtEdsXrYMBAswVK8JVxCZ"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2xOw4soR7cx9s7JwGYld2EaOwAy",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2xOw4soR7cx9s7JwGYld2EaOwAy"
        },
        "enabled": true
      },
      "created_at": "2025-05-21T10:10:39Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2xOw4s9T3LUVY3JBrSfRr3tHURL",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xOw4s9T3LUVY3JBrSfRr3tHURL"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
