# DataLeads URL to Markdown (GitHub Action)

Convert any webpage to clean LLM-ready markdown via the DataLeads extraction API.

Calls the DataLeads API endpoint `POST /v1/markdown` and writes the JSON response to `dataleads-result.json` plus the `result` output.

## Usage

```yaml
steps:
  - uses: DataLeadsPRO/url-to-markdown-action@v1
    with:
      url: https://example.com
      api_key: ${{ secrets.DATALEADS_API_KEY }}
```

Get a client key at [data.dataleads.pro](https://data.dataleads.pro).

## License

MIT
