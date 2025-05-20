# Function: <code>crypto_stats_skcipher_encrypt</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1285
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/seqiv.c:seqiv_aead_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:crypto_cts_encrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/ctr.c:crypto_rfc3686_crypt
  - crypto/gcm.c:crypto_rfc4543_copy_src_to_dst
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
ffffffff81477f80-ffffffff81477f90: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a5f90)
Location: crypto/algapi.c:1254
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff814a5f90-ffffffff814a5fe5: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814c0c40)
Location: crypto/algapi.c:1264
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff814c0c40-ffffffff814c0c95: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815214d0)
Location: crypto/algapi.c:1236
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff815214d0-ffffffff81521540: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153e0c0)
Location: crypto/algapi.c:1255
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff8153e0c0-ffffffff8153e130: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1255
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff81546730-ffffffff815467a0: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1237
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff815a7220-ffffffff815a7290: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1279
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff8164e360-ffffffff8164e3f4: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1227
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff817074b0-ffffffff81707544: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1264
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffff8000105ba3f0-ffff8000105ba430: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1264
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
c0768c5c-c0768c7c: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c00000000073e450)
Location: crypto/algapi.c:1264
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
c00000000073e450-c00000000073e54c: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1264
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffe00040097e-ffffffe0004009b6: crypto_stats_skcipher_encrypt (STB_GLOBAL)
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
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b9220)
Location: crypto/algapi.c:1264
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff814b9220-ffffffff814b9275: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a9c40)
Location: crypto/algapi.c:1264
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff814a9c40-ffffffff814a9c95: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b52b0)
Location: crypto/algapi.c:1264
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff814b52b0-ffffffff814b5305: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crypto_stats_skcipher_encrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cdd30)
Location: crypto/algapi.c:1264
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_encrypt
```
**Symbols:**

```
ffffffff814cdd30-ffffffff814cdd85: crypto_stats_skcipher_encrypt (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
