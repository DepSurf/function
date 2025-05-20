# Function: <code>oiap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813369a0)
Location: security/keys/trusted.c:429
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff813369a0-ffffffff81336a2d: oiap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8136c460)
Location: security/keys/trusted.c:429
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff8136c460-ffffffff8136c4e3: oiap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81382c80)
Location: security/keys/trusted.c:429
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff81382c80-ffffffff81382d03: oiap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81397330)
Location: security/keys/trusted.c:429
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff81397330-ffffffff813973ae: oiap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813bcb10)
Location: security/keys/trusted.c:429
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff813bcb10-ffffffff813bcb8e: oiap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff813ed3c0)
Location: security/keys/trusted.c:428
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff813ed3c0-ffffffff813ed43a: oiap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81408bb0)
Location: security/keys/trusted.c:431
Inline: False
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff81408bb0-ffffffff81408c2a: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff814357f0)
Location: security/keys/trusted.c:433
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff814357f0-ffffffff8143587b: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8144f590)
Location: security/keys/trusted.c:433
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff8144f590-ffffffff8144f61b: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a1be0)
Location: security/keys/trusted-keys/trusted_tpm1.c:430
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
```
**Symbols:**

```
ffffffff814a1be0-ffffffff814a1c74: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814bf5a0)
Location: security/keys/trusted-keys/trusted_tpm1.c:433
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
```
**Symbols:**

```
ffffffff814bf5a0-ffffffff814bf634: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c5800)
Location: security/keys/trusted-keys/trusted_tpm1.c:426
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
```
**Symbols:**

```
ffffffff814c5800-ffffffff814c5894: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151e220)
Location: security/keys/trusted-keys/trusted_tpm1.c:426
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
```
**Symbols:**

```
ffffffff8151e220-ffffffff8151e2b4: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b1750)
Location: security/keys/trusted-keys/trusted_tpm1.c:426
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
```
**Symbols:**

```
ffffffff815b1750-ffffffff815b17f0: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165c280)
Location: security/keys/trusted-keys/trusted_tpm1.c:426
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
```
**Symbols:**

```
ffffffff8165c280-ffffffff8165c320: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81694ba0)
Location: security/keys/trusted-keys/trusted_tpm1.c:426
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
```
**Symbols:**

```
ffffffff81694ba0-ffffffff81694c40: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d11d0)
Location: security/keys/trusted-keys/trusted_tpm1.c:426
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_unseal
```
**Symbols:**

```
ffffffff816d11d0-ffffffff816d1270: oiap (STB_GLOBAL)
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
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffff80001053ab68)
Location: security/keys/trusted.c:433
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffff80001053ab68-ffff80001053ac08: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c06f0cbc)
Location: security/keys/trusted.c:433
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
c06f0cbc-c06f0d70: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (c0000000006890d0)
Location: security/keys/trusted.c:433
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
c0000000006890d0-c0000000006891b0: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffe000398abc)
Location: security/keys/trusted.c:433
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffe000398abc-ffffffe000398b6e: oiap (STB_GLOBAL)
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
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81447b70)
Location: security/keys/trusted.c:433
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff81447b70-ffffffff81447bfb: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff814385c0)
Location: security/keys/trusted.c:433
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff814385c0-ffffffff8143864b: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff81443c10)
Location: security/keys/trusted.c:433
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff81443c10-ffffffff81443c9b: oiap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int oiap(struct tpm_buf *tb, uint32_t *handle, unsigned char *nonce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/trusted.c (ffffffff8145af40)
Location: security/keys/trusted.c:433
Inline: True
Direct callers:
  - security/keys/trusted.c:tpm_unseal
  - security/keys/trusted.c:tpm_unseal
```
**Symbols:**

```
ffffffff8145af40-ffffffff8145afcb: oiap (STB_GLOBAL)
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
