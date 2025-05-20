# Function: <code>crypto_stats_skcipher_decrypt</code>

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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1298
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - crypto/gcm.c:gcm_dec_hash_continue
```
**Symbols:**

```
ffffffff81478170-ffffffff81478180: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a6050)
Location: crypto/algapi.c:1267
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff814a6050-ffffffff814a60a5: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814c09a0)
Location: crypto/algapi.c:1277
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff814c09a0-ffffffff814c09f5: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815211c0)
Location: crypto/algapi.c:1249
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff815211c0-ffffffff81521230: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153e210)
Location: crypto/algapi.c:1268
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff8153e210-ffffffff8153e280: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1268
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff81546960-ffffffff815469d0: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1250
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff815a71b0-ffffffff815a7220: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1292
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff8164e220-ffffffff8164e2b4: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1240
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff81707350-ffffffff817073e4: crypto_stats_skcipher_decrypt (STB_GLOBAL)
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1277
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffff8000105ba770-ffff8000105ba7b0: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1277
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
c0768ee4-c0768f04: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c000000000741370)
Location: crypto/algapi.c:1277
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
c000000000741370-c00000000074146c: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (0)
Location: crypto/algapi.c:1277
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffe000400a54-ffffffe000400a8c: crypto_stats_skcipher_decrypt (STB_GLOBAL)
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
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b8f80)
Location: crypto/algapi.c:1277
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff814b8f80-ffffffff814b8fd5: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a99a0)
Location: crypto/algapi.c:1277
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff814a99a0-ffffffff814a99f5: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b5010)
Location: crypto/algapi.c:1277
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff814b5010-ffffffff814b5065: crypto_stats_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crypto_stats_skcipher_decrypt(unsigned int cryptlen, int ret, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cda90)
Location: crypto/algapi.c:1277
Inline: False
Direct callers:
  - crypto/skcipher.c:crypto_skcipher_decrypt
```
**Symbols:**

```
ffffffff814cda90-ffffffff814cdae5: crypto_stats_skcipher_decrypt (STB_GLOBAL)
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
