# Serverless API contract

Implement these endpoints on a serverless provider.

## POST /api/products
`{"keyword":"wireless earbuds","page":1}` -> `{"products":[]}`

## POST /api/generate-article
`{"keyword":"wireless earbuds","productIds":[1,2],"language":"id"}` -> `{"title":"","slug":"","content":"","seoDescription":"","imagePrompt":"","ctaUrl":""}`

## POST /api/affiliate-link
`{"productUrl":"https://www.aliexpress.com/item/..."}` -> `{"affiliateUrl":"..."}`

Secrets must remain server-side.
