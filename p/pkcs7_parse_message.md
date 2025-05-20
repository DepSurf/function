# Function: <code>pkcs7_parse_message</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff813ae030)
Location: crypto/asymmetric_keys/pkcs7_parser.c:113
Inline: False
Direct callers:
  - certs/system_keyring.c:system_verify_data
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff813ae030-ffffffff813ae177: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff813f1c80)
Location: crypto/asymmetric_keys/pkcs7_parser.c:111
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff813f1c80-ffffffff813f1e2e: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8140b4f0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:111
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff8140b4f0-ffffffff8140b69e: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814190e0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:111
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff814190e0-ffffffff81419286: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81443c10)
Location: crypto/asymmetric_keys/pkcs7_parser.c:119
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff81443c10-ffffffff81443dbc: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:119
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff814773b7-ffffffff814773cf: pkcs7_parse_message.cold.4 (STB_LOCAL)
ffffffff81476b20-ffffffff81476cc0: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:119
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff814955a7-ffffffff814955bf: pkcs7_parse_message.cold.3 (STB_LOCAL)
ffffffff81494cc0-ffffffff81494e60: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff814c2fa7-ffffffff814c2fbf: pkcs7_parse_message.cold (STB_LOCAL)
ffffffff814c26d0-ffffffff814c2887: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff814dbdd7-ffffffff814dbdef: pkcs7_parse_message.cold (STB_LOCAL)
ffffffff814db500-ffffffff814db6b7: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff8153b6a7-ffffffff8153b6bf: pkcs7_parse_message.cold (STB_LOCAL)
ffffffff8153adf0-ffffffff8153af8c: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81bf22bd-ffffffff81bf22d5: pkcs7_parse_message.cold (STB_LOCAL)
ffffffff81557c00-ffffffff81557d9c: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81be4275-ffffffff81be428d: pkcs7_parse_message.cold (STB_LOCAL)
ffffffff81560550-ffffffff815606ec: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81cd7ab8-ffffffff81cd7ad0: pkcs7_parse_message.cold (STB_LOCAL)
ffffffff815c1900-ffffffff815c1a9c: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81e8ad52-ffffffff81e8ad6a: pkcs7_parse_message.cold (STB_LOCAL)
ffffffff8166bd30-ffffffff8166bee4: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff817269c0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff817269c0-ffffffff81726b7f: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81762dc0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff81762dc0-ffffffff81762f7f: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff817a48b0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff817a48b0-ffffffff817a4b2b: pkcs7_parse_message (STB_GLOBAL)
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
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffff8000105d7828)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffff8000105d7828-ffff8000105d79d4: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (c0784e6c)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
c0784e6c-c0785020: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (c000000000766bf0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
c000000000766bf0-c000000000766e30: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffe00041b650)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffe00041b650-ffffffe00041b7c2: pkcs7_parse_message (STB_GLOBAL)
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
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff814d43b7-ffffffff814d43cf: pkcs7_parse_message.cold (STB_LOCAL)
ffffffff814d3ae0-ffffffff814d3c97: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff814c4dd7-ffffffff814c4def: pkcs7_parse_message.cold (STB_LOCAL)
ffffffff814c4500-ffffffff814c46b7: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff814d0447-ffffffff814d045f: pkcs7_parse_message.cold (STB_LOCAL)
ffffffff814cfb70-ffffffff814cfd27: pkcs7_parse_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct pkcs7_message *pkcs7_parse_message(const void *data, size_t datalen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:115
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_read_modsig
```
**Symbols:**

```
ffffffff814e8f17-ffffffff814e8f2f: pkcs7_parse_message.cold (STB_LOCAL)
ffffffff814e8640-ffffffff814e87f7: pkcs7_parse_message (STB_GLOBAL)
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
