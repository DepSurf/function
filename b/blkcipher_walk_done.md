# Function: <code>blkcipher_walk_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff813a1150)
Location: crypto/blkcipher.c:104
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/crypto_null.c:skcipher_null_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_decrypt
```
**Symbols:**

```
ffffffff813a1150-ffffffff813a13c1: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff813dd990)
Location: crypto/blkcipher.c:103
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/crypto_null.c:skcipher_null_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff813dd990-ffffffff813ddc3d: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff813f5240)
Location: crypto/blkcipher.c:103
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/crypto_null.c:skcipher_null_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/xts.c:xts_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff813f5240-ffffffff813f54e7: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff81401570)
Location: crypto/blkcipher.c:104
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/crypto_null.c:skcipher_null_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/xts.c:xts_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81401570-ffffffff814017b1: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff81429b80)
Location: crypto/blkcipher.c:104
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/crypto_null.c:skcipher_null_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/xts.c:xts_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81429b80-ffffffff81429dc1: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff8145c4f0)
Location: crypto/blkcipher.c:100
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/crypto_null.c:skcipher_null_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff8145c4f0-ffffffff8145c704: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff8147a190)
Location: crypto/blkcipher.c:100
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/crypto_null.c:skcipher_null_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff8147a190-ffffffff8147a3a4: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/blkcipher.c (0)
Location: crypto/blkcipher.c:95
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
**Symbols:**

```
ffffffff814a8635-ffffffff814a864e: blkcipher_walk_done.cold (STB_LOCAL)
ffffffff814a80a0-ffffffff814a82bd: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff814c2d00)
Location: crypto/blkcipher.c:95
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
**Symbols:**

```
ffffffff814c2d00-ffffffff814c2f26: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffff8000105bd478)
Location: crypto/blkcipher.c:95
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
**Symbols:**

```
ffff8000105bd478-ffff8000105bd740: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (c076b23c)
Location: crypto/blkcipher.c:95
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
**Symbols:**

```
c076b23c-c076b4d0: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (c000000000744590)
Location: crypto/blkcipher.c:95
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
**Symbols:**

```
c000000000744590-c000000000744954: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffe000402b86)
Location: crypto/blkcipher.c:95
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
**Symbols:**

```
ffffffe000402b86-ffffffe000402d70: blkcipher_walk_done (STB_GLOBAL)
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
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff814bb2e0)
Location: crypto/blkcipher.c:95
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
**Symbols:**

```
ffffffff814bb2e0-ffffffff814bb506: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff814abd00)
Location: crypto/blkcipher.c:95
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
**Symbols:**

```
ffffffff814abd00-ffffffff814abf26: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff814b7370)
Location: crypto/blkcipher.c:95
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
**Symbols:**

```
ffffffff814b7370-ffffffff814b7596: blkcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkcipher_walk_done(struct blkcipher_desc *desc, struct blkcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff814cfe30)
Location: crypto/blkcipher.c:95
Inline: False
Direct callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
**Symbols:**

```
ffffffff814cfe30-ffffffff814d0075: blkcipher_walk_done (STB_GLOBAL)
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
