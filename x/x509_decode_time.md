# Function: <code>x509_decode_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff813acd70)
Location: crypto/asymmetric_keys/x509_cert_parser.c:493
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff813acd70-ffffffff813ad082: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff813f08f0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:480
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff813f08f0-ffffffff813f0c0d: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8140a170)
Location: crypto/asymmetric_keys/x509_cert_parser.c:479
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff8140a170-ffffffff8140a48d: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81417c70)
Location: crypto/asymmetric_keys/x509_cert_parser.c:480
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff81417c70-ffffffff81417f78: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81442760)
Location: crypto/asymmetric_keys/x509_cert_parser.c:482
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff81442760-ffffffff81442a68: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81475630)
Location: crypto/asymmetric_keys/x509_cert_parser.c:491
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff81475630-ffffffff81475959: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814937f0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:488
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff814937f0-ffffffff81493b19: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814c1090)
Location: crypto/asymmetric_keys/x509_cert_parser.c:533
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff814c1090-ffffffff814c13c8: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814d9ec0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:533
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff814d9ec0-ffffffff814da1f8: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81539790)
Location: crypto/asymmetric_keys/x509_cert_parser.c:533
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff81539790-ffffffff81539ac9: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81556580)
Location: crypto/asymmetric_keys/x509_cert_parser.c:550
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff81556580-ffffffff815568b9: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8155ed00)
Location: crypto/asymmetric_keys/x509_cert_parser.c:595
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff8155ed00-ffffffff8155f034: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff815c0060)
Location: crypto/asymmetric_keys/x509_cert_parser.c:595
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff815c0060-ffffffff815c03d0: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff8166a290)
Location: crypto/asymmetric_keys/x509_cert_parser.c:607
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff8166a290-ffffffff8166a5f5: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81724cd0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:610
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff81724cd0-ffffffff81725035: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff81760f80)
Location: crypto/asymmetric_keys/x509_cert_parser.c:660
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff81760f80-ffffffff817612e5: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff817a28e0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:670
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff817a28e0-ffffffff817a2c45: x509_decode_time (STB_GLOBAL)
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
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffff8000105d5fc8)
Location: crypto/asymmetric_keys/x509_cert_parser.c:533
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffff8000105d5fc8-ffff8000105d62dc: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (c078377c)
Location: crypto/asymmetric_keys/x509_cert_parser.c:533
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
c078377c-c0783af0: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (c000000000764930)
Location: crypto/asymmetric_keys/x509_cert_parser.c:533
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
c000000000764930-c000000000764d38: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffe00041a142)
Location: crypto/asymmetric_keys/x509_cert_parser.c:533
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffe00041a142-ffffffe00041a406: x509_decode_time (STB_GLOBAL)
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
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814d24a0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:533
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff814d24a0-ffffffff814d27d8: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814c2ec0)
Location: crypto/asymmetric_keys/x509_cert_parser.c:533
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff814c2ec0-ffffffff814c31f8: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814ce530)
Location: crypto/asymmetric_keys/x509_cert_parser.c:533
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff814ce530-ffffffff814ce868: x509_decode_time (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int x509_decode_time(time64_t *_t, size_t hdrlen, unsigned char tag, const unsigned char *value, size_t vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff814e7000)
Location: crypto/asymmetric_keys/x509_cert_parser.c:533
Inline: False
Direct callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_after
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_note_not_before
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_sig_note_authenticated_attr
```
**Symbols:**

```
ffffffff814e7000-ffffffff814e7338: x509_decode_time (STB_GLOBAL)
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
