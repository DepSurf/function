# Function: <code>public_key_signature_free</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff813f04f0)
Location: crypto/asymmetric_keys/signature.c:25
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_free_certificate
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff813f04f0-ffffffff813f0531: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81409d70)
Location: crypto/asymmetric_keys/signature.c:25
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_free_certificate
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81409d70-ffffffff81409db1: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814178a0)
Location: crypto/asymmetric_keys/signature.c:25
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814178a0-ffffffff814178e2: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81442300)
Location: crypto/asymmetric_keys/signature.c:25
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81442300-ffffffff81442342: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814751e0)
Location: crypto/asymmetric_keys/signature.c:25
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814751e0-ffffffff81475221: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81492ed0)
Location: crypto/asymmetric_keys/signature.c:27
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81492ed0-ffffffff81492f11: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814c05d0)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814c05d0-ffffffff814c0616: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814d9420)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814d9420-ffffffff814d9466: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81538cf0)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81538cf0-ffffffff81538d38: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81555af0)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81555af0-ffffffff81555b38: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff8155e260)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff8155e260-ffffffff8155e2a8: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff815bf590)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff815bf590-ffffffff815bf5d8: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81669440)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81669440-ffffffff81669499: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81723d20)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff81723d20-ffffffff81723d79: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff817600a0)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff817600a0-ffffffff817600f9: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff817a19d0)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff817a19d0-ffffffff817a1a29: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffff8000105d55d0)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffff8000105d55d0-ffff8000105d5620: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (c0782e30)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
c0782e30-c0782e78: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (c0000000007639a0)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
c0000000007639a0-c000000000763a18: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffe0004197c2)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffe0004197c2-ffffffe000419816: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814d1a00)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814d1a00-ffffffff814d1a46: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814c2420)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814c2420-ffffffff814c2466: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814cda90)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814cda90-ffffffff814cdad6: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void public_key_signature_free(struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814e6560)
Location: crypto/asymmetric_keys/signature.c:23
Inline: True
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
**Symbols:**

```
ffffffff814e6560-ffffffff814e65a6: public_key_signature_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
