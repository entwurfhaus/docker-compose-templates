# apache-solr

This `README.md` covers some technical notes.

### Upload sample data

```bash
curl -X POST -H "Content-Type: application/json" \
    "http://apache-solr:8983/solr/alpha/update?commit=true" \
    --data-binary @/scripts/sample_data.json
```
