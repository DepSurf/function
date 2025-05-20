# Function: <code>asn1_ber_decoder</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff81419f80)
Location: lib/asn1_decoder.c:168
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff81419f80-ffffffff8141acff: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff814621e0)
Location: lib/asn1_decoder.c:171
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff814621e0-ffffffff81462e6a: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff81480d10)
Location: lib/asn1_decoder.c:171
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff81480d10-ffffffff8148199a: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff81489f00)
Location: lib/asn1_decoder.c:171
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff81489f00-ffffffff8148abf3: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff814c6060)
Location: lib/asn1_decoder.c:171
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff814c6060-ffffffff814c6d01: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:171
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff814f7b42-ffffffff814f7b82: asn1_ber_decoder.cold.0 (STB_LOCAL)
ffffffff814f6f60-ffffffff814f7b42: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:171
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff8150c02d-ffffffff8150c051: asn1_ber_decoder.cold.0 (STB_LOCAL)
ffffffff8150b3a0-ffffffff8150c02d: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff8153a71d-ffffffff8153a760: asn1_ber_decoder.cold (STB_LOCAL)
ffffffff81539ab0-ffffffff8153a71d: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff8155b53d-ffffffff8155b580: asn1_ber_decoder.cold (STB_LOCAL)
ffffffff8155a8d0-ffffffff8155b53d: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff815e4fa8-ffffffff815e4fe8: asn1_ber_decoder.cold (STB_LOCAL)
ffffffff815e43c0-ffffffff815e4fa8: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff81bf48c7-ffffffff81bf4907: asn1_ber_decoder.cold (STB_LOCAL)
ffffffff816088f0-ffffffff816094dd: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_key_decode
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff81be67bf-ffffffff81be67ff: asn1_ber_decoder.cold (STB_LOCAL)
ffffffff815eb3c0-ffffffff815ec059: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_key_decode
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff81cde5ee-ffffffff81cde62e: asn1_ber_decoder.cold (STB_LOCAL)
ffffffff816578f0-ffffffff816589d6: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_key_decode
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff81ea4a1c-ffffffff81ea4a52: asn1_ber_decoder.cold (STB_LOCAL)
ffffffff8176fbf0-ffffffff81770d7d: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff8189f790)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_key_decode
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff8189f790-ffffffff818a0938: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff818e1d50)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_key_decode
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff818e1d50-ffffffff818e2eb6: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffff81928ce0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_key_decode
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff81928ce0-ffffffff81929e46: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffff800010667f68)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffff800010667f68-ffff8000106689c8: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (c08104f4)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
c08104f4-c081122c: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (c00000000081d3c0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
c00000000081d3c0-c00000000081e030: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/asn1_decoder.c (ffffffe000493254)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffe000493254-ffffffe000493d2a: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff81553b1d-ffffffff81553b60: asn1_ber_decoder.cold (STB_LOCAL)
ffffffff81552eb0-ffffffff81553b1d: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff81543d9d-ffffffff81543de0: asn1_ber_decoder.cold (STB_LOCAL)
ffffffff81543130-ffffffff81543d9d: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff8154f85d-ffffffff8154f8a0: asn1_ber_decoder.cold (STB_LOCAL)
ffffffff8154ebf0-ffffffff8154f85d: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int asn1_ber_decoder(const struct asn1_decoder *decoder, void *context, const unsigned char *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/asn1_decoder.c (0)
Location: lib/asn1_decoder.c:167
Inline: False
Direct callers:
  - crypto/rsa_helper.c:rsa_parse_priv_key
  - crypto/rsa_helper.c:rsa_parse_pub_key
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff815696ad-ffffffff815696f0: asn1_ber_decoder.cold (STB_LOCAL)
ffffffff81568a40-ffffffff815696ad: asn1_ber_decoder (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
