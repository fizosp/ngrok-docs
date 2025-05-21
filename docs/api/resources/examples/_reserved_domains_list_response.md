<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2xOw2vOgB160Nbqm6048nm4Tb4Z",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2xOw2vOgB160Nbqm6048nm4Tb4Z"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.hyv1gmuujx8kj4hd.local-ngrok-cname.com",
      "created_at": "2025-05-21T10:10:23Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2xOw2wAHiM0XaXXInxeThT6Crgz",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2xOw2wAHiM0XaXXInxeThT6Crgz"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-05-21T10:10:23Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.hyv1gmuujx8kj4hd.local-ngrok-cname.com",
      "created_at": "2025-05-21T10:10:23Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2xOw2r1LgTOu7OC9oVxwLgLEEag",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2xOw2r1LgTOu7OC9oVxwLgLEEag"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
