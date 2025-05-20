# Function: <code>x509_free_certificate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff813ac9d0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:48
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff813ac9d0-ffffffff813aca3f: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff813f0890)
Location: crypto/asymmetric_keys/x509_cert_parser.c:47
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff813f0890-ffffffff813f08e4: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8140a110)
Location: crypto/asymmetric_keys/x509_cert_parser.c:47
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff8140a110-ffffffff8140a164: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81418497)
Location: crypto/asymmetric_keys/x509_cert_parser.c:47
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81417f80-ffffffff81417fce: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff81417fd0-ffffffff81417fe7: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81442f87)
Location: crypto/asymmetric_keys/x509_cert_parser.c:47
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81442a70-ffffffff81442abe: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff81442ac0-ffffffff81442ad7: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81475e4a)
Location: crypto/asymmetric_keys/x509_cert_parser.c:47
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81475960-ffffffff814759ae: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff814759b0-ffffffff814759c6: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81493cea)
Location: crypto/asymmetric_keys/x509_cert_parser.c:47
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81493b20-ffffffff81493b6e: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff81493b70-ffffffff81493b86: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814c161a)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814c13d0-ffffffff814c1425: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff814c1430-ffffffff814c1446: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814da44a)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814da200-ffffffff814da255: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff814da260-ffffffff814da276: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8153a032)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81539ad0-ffffffff81539b27: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff81539b30-ffffffff81539b46: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81556e22)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff815568c0-ffffffff81556917: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff81556920-ffffffff81556936: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8155f5a2)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff8155f040-ffffffff8155f097: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff8155f0a0-ffffffff8155f0b6: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff815c0932)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff815c03d0-ffffffff815c0427: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff815c0430-ffffffff815c0446: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8166ab96)
Location: crypto/asymmetric_keys/x509_cert_parser.c:44
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff8166a600-ffffffff8166a657: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff8166a660-ffffffff8166a682: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81725616)
Location: crypto/asymmetric_keys/x509_cert_parser.c:44
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81725050-ffffffff817250a7: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff817250c0-ffffffff817250e2: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff817618e6)
Location: crypto/asymmetric_keys/x509_cert_parser.c:44
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81761300-ffffffff81761357: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff81761370-ffffffff81761392: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff817a3332)
Location: crypto/asymmetric_keys/x509_cert_parser.c:44
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff817a2c60-ffffffff817a2cb7: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff817a2cd0-ffffffff817a2cf2: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffff8000105d6700)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffff8000105d64d0-ffff8000105d652c: x509_free_certificate.part.0 (STB_LOCAL)
ffff8000105d6530-ffff8000105d6560: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (c0783d08)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
c0783af0-c0783b44: x509_free_certificate.part.0 (STB_LOCAL)
c0783b44-c0783b68: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (c0000000007652c8)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
c000000000765020-c0000000007650ac: x509_free_certificate.part.0 (STB_LOCAL)
c0000000007650b0-c0000000007650cc: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffe00041a61c)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffe00041a406-ffffffe00041a46c: x509_free_certificate.part.0 (STB_LOCAL)
ffffffe00041a46c-ffffffe00041a498: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814d2a2a)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814d27e0-ffffffff814d2835: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff814d2840-ffffffff814d2856: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814c344a)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814c3200-ffffffff814c3255: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff814c3260-ffffffff814c3276: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814ceaba)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814ce870-ffffffff814ce8c5: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff814ce8d0-ffffffff814ce8e6: x509_free_certificate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x509_free_certificate(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814e758a)
Location: crypto/asymmetric_keys/x509_cert_parser.c:46
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814e7340-ffffffff814e7395: x509_free_certificate.part.0 (STB_LOCAL)
ffffffff814e73a0-ffffffff814e73b6: x509_free_certificate (STB_GLOBAL)
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
