# Function: <code>tpm_seal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81337be9)
Location: security/keys/trusted.c:459
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8136d269)
Location: security/keys/trusted.c:459
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81383a89)
Location: security/keys/trusted.c:459
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81398120)
Location: security/keys/trusted.c:459
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813bd930)
Location: security/keys/trusted.c:459
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813ee754)
Location: security/keys/trusted.c:458
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81409983)
Location: security/keys/trusted.c:462
Inline: True
Inline callers:
  - security/keys/trusted.c:key_seal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:467
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff81436a00-ffffffff81436f90: tpm_seal (STB_LOCAL)
ffffffff8143770b-ffffffff81437726: tpm_seal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:467
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff814507a0-ffffffff81450d30: tpm_seal (STB_LOCAL)
ffffffff814514b9-ffffffff814514d4: tpm_seal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:461
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:key_seal
```
**Symbols:**

```
ffffffff814a2440-ffffffff814a2a20: tpm_seal (STB_LOCAL)
ffffffff814a3100-ffffffff814a311b: tpm_seal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:464
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:key_seal
```
**Symbols:**

```
ffffffff814bfe10-ffffffff814c03e2: tpm_seal (STB_LOCAL)
ffffffff81befd49-ffffffff81befd64: tpm_seal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:457
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
```
**Symbols:**

```
ffffffff814c6180-ffffffff814c6787: tpm_seal (STB_LOCAL)
ffffffff81be1e1e-ffffffff81be1e39: tpm_seal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:457
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
```
**Symbols:**

```
ffffffff8151ebc0-ffffffff8151f244: tpm_seal (STB_LOCAL)
ffffffff81cd308f-ffffffff81cd30aa: tpm_seal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:457
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
```
**Symbols:**

```
ffffffff815b21e0-ffffffff815b288a: tpm_seal (STB_LOCAL)
ffffffff81e86234-ffffffff81e8624f: tpm_seal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165cdc0)
Location: security/keys/trusted-keys/trusted_tpm1.c:457
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
```
**Symbols:**

```
ffffffff8165cdc0-ffffffff8165d491: tpm_seal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816956e0)
Location: security/keys/trusted-keys/trusted_tpm1.c:457
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
```
**Symbols:**

```
ffffffff816956e0-ffffffff81695db1: tpm_seal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d1d10)
Location: security/keys/trusted-keys/trusted_tpm1.c:457
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_seal
```
**Symbols:**

```
ffffffff816d1d10-ffffffff816d2410: tpm_seal (STB_LOCAL)
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
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffff80001053b9d0)
Location: security/keys/trusted.c:467
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffff80001053b9d0-ffff80001053bee8: tpm_seal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c06f1918)
Location: security/keys/trusted.c:467
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
c06f1918-c06f1ef0: tpm_seal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c00000000068ac30)
Location: security/keys/trusted.c:467
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
c00000000068ac30-c00000000068b2fc: tpm_seal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffe00039964a)
Location: security/keys/trusted.c:467
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffe00039964a-ffffffe000399bd8: tpm_seal (STB_LOCAL)
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
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:467
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff81448d80-ffffffff81449310: tpm_seal (STB_LOCAL)
ffffffff81449a99-ffffffff81449ab4: tpm_seal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:467
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff814397d0-ffffffff81439d60: tpm_seal (STB_LOCAL)
ffffffff8143a4e9-ffffffff8143a504: tpm_seal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:467
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff81444e20-ffffffff814453b0: tpm_seal (STB_LOCAL)
ffffffff81445b39-ffffffff81445b54: tpm_seal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm_seal(struct tpm_buf *tb, uint16_t keytype, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *data, uint32_t datalen, unsigned char *blob, uint32_t *bloblen, const unsigned char *blobauth, const unsigned char *pcrinfo, uint32_t pcrinfosize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:467
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
```
**Symbols:**

```
ffffffff8145c150-ffffffff8145c6e0: tpm_seal (STB_LOCAL)
ffffffff8145ce69-ffffffff8145ce84: tpm_seal.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
