# serverless-example (Parsing POST request with AWS Lambda)


This code example accept Post request and parse the JSON contents with Lambda

- Sample request

```bash
curl --location --request POST 'https://h7swa55m2g.execute-api.us-east-1.amazonaws.com/production/setest' \
--header 'Content-Type: application/json' \
--data-raw '{
    "depatment": "HR",
    "id": "04",
    "name": "Pankaj"
}'
```
