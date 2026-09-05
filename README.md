# swift-rfc-1123-coder

Wire coders for [swift-rfc-1123](https://github.com/swift-ietf/swift-rfc-1123): `RFC_1123.Domain.Coder` and `RFC_1123.Domain.Label.Coder` parse a host name or label from a byte cursor and serialize it back, the `ASCII.Parseable`, `ASCII.Serializable` and `Binary.Serializable` conformances, and `Coder.Codable` on both types so `RFC_1123.Domain(decoding:)` / `encoded()` work out of the box. The domain package stays a pure model; import `RFC_1123_Coder` wherever bytes enter or leave.
