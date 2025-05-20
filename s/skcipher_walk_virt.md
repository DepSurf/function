# Function: <code>skcipher_walk_virt</code>

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
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813f6ad0)
Location: crypto/skcipher.c:473
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
**Symbols:**

```
ffffffff813f6ad0-ffffffff813f6b06: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81402ea0)
Location: crypto/skcipher.c:474
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
**Symbols:**

```
ffffffff81402ea0-ffffffff81402eda: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8142b520)
Location: crypto/skcipher.c:473
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
**Symbols:**

```
ffffffff8142b520-ffffffff8142b55a: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8145e230)
Location: crypto/skcipher.c:474
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
```
**Symbols:**

```
ffffffff8145e230-ffffffff8145e26a: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8147bad0)
Location: crypto/skcipher.c:472
Inline: False
Direct callers:
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
```
**Symbols:**

```
ffffffff8147bad0-ffffffff8147bb2a: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a9e70)
Location: crypto/skcipher.c:472
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814a9e70-ffffffff814a9eca: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c4b60)
Location: crypto/skcipher.c:476
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814c4b60-ffffffff814c4bba: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81523980)
Location: crypto/skcipher.c:476
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81523980-ffffffff81523a7e: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815408d0)
Location: crypto/skcipher.c:476
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff815408d0-ffffffff815409ce: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81548f30)
Location: crypto/skcipher.c:477
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81548f30-ffffffff8154902e: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a9710)
Location: crypto/skcipher.c:477
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff815a9710-ffffffff815a980e: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81650b60)
Location: crypto/skcipher.c:477
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81650b60-ffffffff81650c6a: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8170a340)
Location: crypto/skcipher.c:477
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff8170a340-ffffffff8170a44a: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81743b90)
Location: crypto/skcipher.c:495
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81743b90-ffffffff81743c9a: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81785fd0)
Location: crypto/skcipher.c:499
Inline: False
Direct callers:
  - crypto/lskcipher.c:crypto_lskcipher_crypt_sg
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/xts.c:xts_xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff81785fd0-ffffffff81786036: skcipher_walk_virt (STB_GLOBAL)
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
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105bf5d8)
Location: crypto/skcipher.c:476
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffff8000105bf5d8-ffff8000105bf648: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076d318)
Location: crypto/skcipher.c:476
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/cbc.c:crypto_cbc_encrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
c076d318-c076d378: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c000000000747330)
Location: crypto/skcipher.c:476
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
c000000000747330-c0000000007473c4: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe000404776)
Location: crypto/skcipher.c:476
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffe000404776-ffffffe0004047da: skcipher_walk_virt (STB_GLOBAL)
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
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bd140)
Location: crypto/skcipher.c:476
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814bd140-ffffffff814bd19a: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814adb60)
Location: crypto/skcipher.c:476
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814adb60-ffffffff814adbba: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b91d0)
Location: crypto/skcipher.c:476
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814b91d0-ffffffff814b922a: skcipher_walk_virt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skcipher_walk_virt(struct skcipher_walk *walk, struct skcipher_request *req, bool atomic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d1c90)
Location: crypto/skcipher.c:476
Inline: False
Direct callers:
  - crypto/crypto_null.c:null_skcipher_crypt
  - crypto/ecb.c:crypto_ecb_crypt
  - crypto/cbc.c:crypto_cbc_decrypt
  - crypto/xts.c:xor_tweak
  - crypto/ctr.c:crypto_ctr_crypt
```
**Symbols:**

```
ffffffff814d1c90-ffffffff814d1cca: skcipher_walk_virt (STB_GLOBAL)
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
