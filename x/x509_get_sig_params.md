# Function: <code>x509_get_sig_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff813adab0)
Location: crypto/asymmetric_keys/x509_public_key.c:158
Inline: True
Direct callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
**Symbols:**

```
ffffffff813adab0-ffffffff813adbe7: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff813f1960)
Location: crypto/asymmetric_keys/x509_public_key.c:27
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff813f1960-ffffffff813f1acf: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8140b1b0)
Location: crypto/asymmetric_keys/x509_public_key.c:27
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff8140b1b0-ffffffff8140b31f: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81418d50)
Location: crypto/asymmetric_keys/x509_public_key.c:27
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff81418d50-ffffffff81418f16: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81443880)
Location: crypto/asymmetric_keys/x509_public_key.c:27
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff81443880-ffffffff81443a29: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:27
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff81476a22-ffffffff81476a48: x509_get_sig_params.cold.1 (STB_LOCAL)
ffffffff814767a0-ffffffff8147692a: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:27
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff81494bc2-ffffffff81494be8: x509_get_sig_params.cold.1 (STB_LOCAL)
ffffffff81494940-ffffffff81494aca: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff814c25b2-ffffffff814c25d8: x509_get_sig_params.cold (STB_LOCAL)
ffffffff814c2340-ffffffff814c24bb: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff814db3e2-ffffffff814db408: x509_get_sig_params.cold (STB_LOCAL)
ffffffff814db170-ffffffff814db2eb: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff8153acd2-ffffffff8153acf8: x509_get_sig_params.cold (STB_LOCAL)
ffffffff8153aa60-ffffffff8153abdb: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff81bf2297-ffffffff81bf22bd: x509_get_sig_params.cold (STB_LOCAL)
ffffffff81557880-ffffffff81557a0c: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff81be424f-ffffffff81be4275: x509_get_sig_params.cold (STB_LOCAL)
ffffffff81560180-ffffffff8156030c: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff81cd7a93-ffffffff81cd7ab8: x509_get_sig_params.cold (STB_LOCAL)
ffffffff815c1530-ffffffff815c16b7: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff81e8ad2d-ffffffff81e8ad52: x509_get_sig_params.cold (STB_LOCAL)
ffffffff8166b9d0-ffffffff8166bb11: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff817265f0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff817265f0-ffffffff81726753: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81762980)
Location: crypto/asymmetric_keys/x509_public_key.c:25
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff81762980-ffffffff81762b52: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff817a4470)
Location: crypto/asymmetric_keys/x509_public_key.c:25
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff817a4470-ffffffff817a4642: x509_get_sig_params (STB_GLOBAL)
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
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (ffff8000105d7430)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffff8000105d7430-ffff8000105d75d0: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (c0784ac8)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
c0784ac8-c0784c3c: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (c000000000766540)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
c000000000766540-c000000000766788: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (ffffffe00041b316)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffe00041b316-ffffffe00041b472: x509_get_sig_params (STB_GLOBAL)
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
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff814d39c2-ffffffff814d39e8: x509_get_sig_params.cold (STB_LOCAL)
ffffffff814d3750-ffffffff814d38cb: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff814c43e2-ffffffff814c4408: x509_get_sig_params.cold (STB_LOCAL)
ffffffff814c4170-ffffffff814c42eb: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff814cfa52-ffffffff814cfa78: x509_get_sig_params.cold (STB_LOCAL)
ffffffff814cf7e0-ffffffff814cf95b: x509_get_sig_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int x509_get_sig_params(struct x509_certificate *cert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: crypto/asymmetric_keys/x509_public_key.c:23
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
**Symbols:**

```
ffffffff814e8522-ffffffff814e8548: x509_get_sig_params.cold (STB_LOCAL)
ffffffff814e82b0-ffffffff814e842b: x509_get_sig_params (STB_GLOBAL)
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
