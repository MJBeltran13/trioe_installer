# trioe_esp32_s3 Arduino package index

Hosted package index:

`https://raw.githubusercontent.com/MJBeltran13/trioe_installer/main/package_esp32_s3_index.json`

Add this repository's `package_esp32_s3_index.json` URL to Arduino IDE's
Additional Boards Manager URLs, then install **Trioe Boards** and select
**TRIOE Dev Module**.

The index exposes only the S3 board entry. Espressif publishes one shared
`esp32-core` archive, so the downloaded archive is not physically reduced to
S3-only files; this package prevents the other board choices from appearing.

For a local checkout, the URL is:

```text
file:///absolute/path/to/trioe_installer/package_esp32_s3_index.json
```
