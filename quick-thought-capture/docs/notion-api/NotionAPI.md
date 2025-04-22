

- Sample Idea Page
```sh
# Page 
curl https://api.notion.com/v1/pages/1dd7b826f8e880cd8267ec9faef2a075 \
    -H "Authorization: Bearer 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" \
    -H "Content-Type: application/json" \
    -H "Notion-Version: 2022-06-28"

# Block
curl https://api.notion.com/v1/blocks/1dd7b826f8e880cd8267ec9faef2a075/children \
    -H "Authorization: Bearer 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" \
    -H "Content-Type: application/json" \
    -H "Notion-Version: 2022-06-28"

```