---
"@effect/tsgo": patch
---

Extend `preferSchemaTypeProperty` to also report `Schema.Codec.Encoded<typeof X>`, `Schema.Codec.DecodingServices<typeof X>`, and `Schema.Codec.EncodingServices<typeof X>` in favor of `typeof X.Encoded`, `typeof X.DecodingServices`, and `typeof X.EncodingServices`.
