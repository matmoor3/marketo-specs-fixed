Copies of Adobe's official Marketo OpenAPI (Swagger 2.0) specs from AdobeDocs/marketo-apis.
Only change: in swagger-mapi.json, the `status` query parameter on the four "Get Export ... Jobs" calls had `enum` on an `array` type, which Gemini function calling rejects. The enum was moved into `items`.
swagger-asset.json is unchanged.
