# Function: <code>x509_cert_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff813ad090)
Location: crypto/asymmetric_keys/x509_cert_parser.c:68
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff813ad090-ffffffff813ad200: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff813f0f30)
Location: crypto/asymmetric_keys/x509_cert_parser.c:64
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff813f0f30-ffffffff813f1102: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8140a7b0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:64
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff8140a7b0-ffffffff8140a960: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81418300)
Location: crypto/asymmetric_keys/x509_cert_parser.c:64
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff81418300-ffffffff814184b9: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81442df0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:64
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff81442df0-ffffffff81442fa9: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:64
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff81476590-ffffffff814765a1: x509_cert_parse.cold.3 (STB_LOCAL)
ffffffff81475cf0-ffffffff81475ea7: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:64
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff81494730-ffffffff81494741: x509_cert_parse.cold.2 (STB_LOCAL)
ffffffff81493b90-ffffffff81493d47: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff814c2120-ffffffff814c2131: x509_cert_parse.cold (STB_LOCAL)
ffffffff814c1450-ffffffff814c1641: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff814daf50-ffffffff814daf61: x509_cert_parse.cold (STB_LOCAL)
ffffffff814da280-ffffffff814da471: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff8153a820-ffffffff8153a831: x509_cert_parse.cold (STB_LOCAL)
ffffffff81539e60-ffffffff8153a059: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff81bf2270-ffffffff81bf2281: x509_cert_parse.cold (STB_LOCAL)
ffffffff81556c50-ffffffff81556e49: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff81be4228-ffffffff81be4239: x509_cert_parse.cold (STB_LOCAL)
ffffffff8155f3d0-ffffffff8155f5c9: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff81cd7a2d-ffffffff81cd7a3e: x509_cert_parse.cold (STB_LOCAL)
ffffffff815c0760-ffffffff815c0959: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:61
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff81e8ac79-ffffffff81e8ac8a: x509_cert_parse.cold (STB_LOCAL)
ffffffff8166a9c0-ffffffff8166abc8: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81725440)
Location: crypto/asymmetric_keys/x509_cert_parser.c:61
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff81725440-ffffffff81725656: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81761710)
Location: crypto/asymmetric_keys/x509_cert_parser.c:61
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff81761710-ffffffff81761926: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff817a30a0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:61
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff817a30a0-ffffffff817a3372: x509_cert_parse (STB_GLOBAL)
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
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffff8000105d6560)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffff8000105d6560-ffff8000105d6734: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (c0783b68)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
c0783b68-c0783d40: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (c0000000007650d0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
c0000000007650d0-c000000000765368: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffe00041a498)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffe00041a498-ffffffe00041a658: x509_cert_parse (STB_GLOBAL)
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
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff814d3530-ffffffff814d3541: x509_cert_parse.cold (STB_LOCAL)
ffffffff814d2860-ffffffff814d2a51: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff814c3f50-ffffffff814c3f61: x509_cert_parse.cold (STB_LOCAL)
ffffffff814c3280-ffffffff814c3471: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff814cf5c0-ffffffff814cf5d1: x509_cert_parse.cold (STB_LOCAL)
ffffffff814ce8f0-ffffffff814ceae1: x509_cert_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct x509_certificate *x509_cert_parse(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:63
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_extract_cert
```
**Symbols:**

```
ffffffff814e8090-ffffffff814e80a1: x509_cert_parse.cold (STB_LOCAL)
ffffffff814e73c0-ffffffff814e75b1: x509_cert_parse (STB_GLOBAL)
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
