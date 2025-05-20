# Function: <code>pkcs7_get_content_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, bool want_wrapper);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff813adf20)
Location: crypto/asymmetric_keys/pkcs7_parser.c:174
Inline: False
Direct callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/mscode_parser.c:mscode_parse
```
**Symbols:**

```
ffffffff813adf20-ffffffff813adf5e: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff813f1b90)
Location: crypto/asymmetric_keys/pkcs7_parser.c:179
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff813f1b90-ffffffff813f1bc7: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8140b400)
Location: crypto/asymmetric_keys/pkcs7_parser.c:179
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff8140b400-ffffffff8140b437: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81418ff0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:179
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff81418ff0-ffffffff81419023: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81443b20)
Location: crypto/asymmetric_keys/pkcs7_parser.c:189
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff81443b20-ffffffff81443b53: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81476a50)
Location: crypto/asymmetric_keys/pkcs7_parser.c:189
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff81476a50-ffffffff81476a83: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81494bf0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:189
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff81494bf0-ffffffff81494c23: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814c25e0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff814c25e0-ffffffff814c2613: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814db410)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814db410-ffffffff814db443: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8153ad00)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff8153ad00-ffffffff8153ad33: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81557b10)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff81557b10-ffffffff81557b43: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81560460)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff81560460-ffffffff81560493: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff815c1810)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff815c1810-ffffffff815c1843: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff8166bc20)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff8166bc20-ffffffff8166bc6b: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81726880)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff81726880-ffffffff817268cb: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff81762c80)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff81762c80-ffffffff81762ccb: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff817a4770)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff817a4770-ffffffff817a47bb: pkcs7_get_content_data (STB_GLOBAL)
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
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffff8000105d76f8)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffff8000105d76f8-ffff8000105d775c: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (c0784d58)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
c0784d58-c0784dac: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (c000000000766a90)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
c000000000766a90-c000000000766ad4: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffe00041b550)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffe00041b550-ffffffe00041b5a2: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814d39f0)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814d39f0-ffffffff814d3a23: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814c4410)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814c4410-ffffffff814c4443: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814cfa80)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814cfa80-ffffffff814cfab3: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pkcs7_get_content_data(const struct pkcs7_message *pkcs7, const void **_data, size_t *_data_len, size_t *_headerlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff814e8550)
Location: crypto/asymmetric_keys/pkcs7_parser.c:185
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814e8550-ffffffff814e8583: pkcs7_get_content_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t *_headerlen</code>
</li>
<li>
<b>Param removed. </b>
<code>bool want_wrapper</code>
</li>
</ul>
</details>
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
