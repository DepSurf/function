# Function: <code>skcipher_walk_done</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813f6110)
Location: crypto/skcipher.c:108
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
**Symbols:**

```
ffffffff813f6110-ffffffff813f6334: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81402540)
Location: crypto/skcipher.c:109
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
**Symbols:**

```
ffffffff81402540-ffffffff81402753: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8142abb0)
Location: crypto/skcipher.c:109
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
**Symbols:**

```
ffffffff8142abb0-ffffffff8142adc3: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8145d900)
Location: crypto/skcipher.c:108
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
**Symbols:**

```
ffffffff8145d900-ffffffff8145dafd: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8147b1a0)
Location: crypto/skcipher.c:108
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
```
**Symbols:**

```
ffffffff8147b1a0-ffffffff8147b39d: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a93f0)
Location: crypto/skcipher.c:103
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814a93f0-ffffffff814a9605: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c4060)
Location: crypto/skcipher.c:104
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814c4060-ffffffff814c42f3: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81523540)
Location: crypto/skcipher.c:104
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81523540-ffffffff815237d7: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81540490)
Location: crypto/skcipher.c:104
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81540490-ffffffff81540723: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81548b00)
Location: crypto/skcipher.c:105
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81548b00-ffffffff81548d90: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a92e0)
Location: crypto/skcipher.c:105
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff815a92e0-ffffffff815a9570: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81650750)
Location: crypto/skcipher.c:105
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81650750-ffffffff816509a3: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81709f00)
Location: crypto/skcipher.c:105
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81709f00-ffffffff8170a153: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81743460)
Location: crypto/skcipher.c:123
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81743460-ffffffff817436b6: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81785790)
Location: crypto/skcipher.c:122
Inline: False
Direct callers:
  - crypto/lskcipher.c:crypto_lskcipher_crypt_sg
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81785790-ffffffff817859e6: skcipher_walk_done (STB_GLOBAL)
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
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105becc8)
Location: crypto/skcipher.c:104
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffff8000105becc8-ffff8000105bef98: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076cca8)
Location: crypto/skcipher.c:104
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
c076cca8-c076d024: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c0000000007462d0)
Location: crypto/skcipher.c:104
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
c0000000007462d0-c000000000746744: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe000403fa4)
Location: crypto/skcipher.c:104
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffe000403fa4-ffffffe0004041c8: skcipher_walk_done (STB_GLOBAL)
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
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bc640)
Location: crypto/skcipher.c:104
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814bc640-ffffffff814bc8d3: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814ad060)
Location: crypto/skcipher.c:104
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814ad060-ffffffff814ad2f3: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b86d0)
Location: crypto/skcipher.c:104
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814b86d0-ffffffff814b8963: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skcipher_walk_done(struct skcipher_walk *walk, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d11b0)
Location: crypto/skcipher.c:104
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814d11b0-ffffffff814d1426: skcipher_walk_done (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
