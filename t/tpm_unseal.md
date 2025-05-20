# Function: <code>tpm_unseal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813377a0)
Location: security/keys/trusted.c:574
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff813377a0-ffffffff81337b86: tpm_unseal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8136cdc0)
Location: security/keys/trusted.c:574
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff8136cdc0-ffffffff8136d1bc: tpm_unseal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813835e0)
Location: security/keys/trusted.c:574
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff813835e0-ffffffff813839dc: tpm_unseal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81397d00)
Location: security/keys/trusted.c:574
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81397d00-ffffffff813980bb: tpm_unseal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813bd510)
Location: security/keys/trusted.c:574
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff813bd510-ffffffff813bd8cb: tpm_unseal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:573
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff813ee3b0-ffffffff813ee6d7: tpm_unseal (STB_LOCAL)
ffffffff813ef1ee-ffffffff813ef28a: tpm_unseal.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:577
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff814095e0-ffffffff81409907: tpm_unseal (STB_LOCAL)
ffffffff8140a45f-ffffffff8140a4fb: tpm_unseal.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:582
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff814366a0-ffffffff814369f8: tpm_unseal (STB_LOCAL)
ffffffff81437699-ffffffff8143770b: tpm_unseal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:582
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81450440-ffffffff81450798: tpm_unseal (STB_LOCAL)
ffffffff81451447-ffffffff814514b9: tpm_unseal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:573
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:key_unseal
```
**Symbols:**

```
ffffffff814a1e80-ffffffff814a2358: tpm_unseal (STB_LOCAL)
ffffffff814a3077-ffffffff814a30ed: tpm_unseal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:580
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:key_unseal
```
**Symbols:**

```
ffffffff814bf840-ffffffff814bfd2e: tpm_unseal (STB_LOCAL)
ffffffff81befcc7-ffffffff81befd36: tpm_unseal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:575
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
```
**Symbols:**

```
ffffffff814c5aa0-ffffffff814c5f8e: tpm_unseal (STB_LOCAL)
ffffffff81be1d9c-ffffffff81be1e0b: tpm_unseal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:575
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
```
**Symbols:**

```
ffffffff8151e4c0-ffffffff8151e9ae: tpm_unseal (STB_LOCAL)
ffffffff81cd300d-ffffffff81cd307c: tpm_unseal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (0)
Location: security/keys/trusted-keys/trusted_tpm1.c:575
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
```
**Symbols:**

```
ffffffff815b1a30-ffffffff815b1fab: tpm_unseal (STB_LOCAL)
ffffffff81e861a7-ffffffff81e86216: tpm_unseal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165c580)
Location: security/keys/trusted-keys/trusted_tpm1.c:575
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
```
**Symbols:**

```
ffffffff8165c580-ffffffff8165cb4c: tpm_unseal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81694ea0)
Location: security/keys/trusted-keys/trusted_tpm1.c:575
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
```
**Symbols:**

```
ffffffff81694ea0-ffffffff8169546c: tpm_unseal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d14d0)
Location: security/keys/trusted-keys/trusted_tpm1.c:575
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_unseal
```
**Symbols:**

```
ffffffff816d14d0-ffffffff816d1a9c: tpm_unseal (STB_LOCAL)
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
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffff80001053b670)
Location: security/keys/trusted.c:582
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffff80001053b670-ffff80001053b9cc: tpm_unseal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c06f1544)
Location: security/keys/trusted.c:582
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
c06f1544-c06f1918: tpm_unseal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c00000000068a7d0)
Location: security/keys/trusted.c:582
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
c00000000068a7d0-c00000000068ac30: tpm_unseal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffe0003992e4)
Location: security/keys/trusted.c:582
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffe0003992e4-ffffffe00039964a: tpm_unseal (STB_LOCAL)
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
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:582
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81448a20-ffffffff81448d78: tpm_unseal (STB_LOCAL)
ffffffff81449a27-ffffffff81449a99: tpm_unseal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:582
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81439470-ffffffff814397c8: tpm_unseal (STB_LOCAL)
ffffffff8143a477-ffffffff8143a4e9: tpm_unseal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:582
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff81444ac0-ffffffff81444e18: tpm_unseal (STB_LOCAL)
ffffffff81445ac7-ffffffff81445b39: tpm_unseal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm_unseal(struct tpm_buf *tb, uint32_t keyhandle, const unsigned char *keyauth, const unsigned char *blob, int bloblen, const unsigned char *blobauth, unsigned char *data, unsigned int *datalen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/trusted.c (0)
Location: security/keys/trusted.c:582
Inline: False
Direct callers:
  - security/keys/trusted.c:trusted_instantiate
```
**Symbols:**

```
ffffffff8145bdf0-ffffffff8145c148: tpm_unseal (STB_LOCAL)
ffffffff8145cdf7-ffffffff8145ce69: tpm_unseal.cold (STB_LOCAL)
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
