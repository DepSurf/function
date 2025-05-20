# Function: <code>crypto_shash_tfm_digest</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int crypto_shash_tfm_digest(struct crypto_shash *tfm, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:209
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_do_sha256
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff81525db7-ffffffff81525dc3: crypto_shash_tfm_digest.cold (STB_LOCAL)
ffffffff81525b80-ffffffff81525c02: crypto_shash_tfm_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int crypto_shash_tfm_digest(struct crypto_shash *tfm, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:209
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff81bf2067-ffffffff81bf2073: crypto_shash_tfm_digest.cold (STB_LOCAL)
ffffffff81542ab0-ffffffff81542b32: crypto_shash_tfm_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int crypto_shash_tfm_digest(struct crypto_shash *tfm, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:221
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff81be405b-ffffffff81be4067: crypto_shash_tfm_digest.cold (STB_LOCAL)
ffffffff8154b150-ffffffff8154b1d2: crypto_shash_tfm_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int crypto_shash_tfm_digest(struct crypto_shash *tfm, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/shash.c (0)
Location: crypto/shash.c:221
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff81cd777a-ffffffff81cd7786: crypto_shash_tfm_digest.cold (STB_LOCAL)
ffffffff815ab930-ffffffff815ab9b2: crypto_shash_tfm_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_shash_tfm_digest(struct crypto_shash *tfm, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81653220)
Location: crypto/shash.c:221
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff81653220-ffffffff816532bb: crypto_shash_tfm_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_shash_tfm_digest(struct crypto_shash *tfm, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170cf30)
Location: crypto/shash.c:211
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff8170cf30-ffffffff8170cfcb: crypto_shash_tfm_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_shash_tfm_digest(struct crypto_shash *tfm, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81746890)
Location: crypto/shash.c:253
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff81746890-ffffffff8174692b: crypto_shash_tfm_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_shash_tfm_digest(struct crypto_shash *tfm, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81788a10)
Location: crypto/shash.c:151
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
```
**Symbols:**

```
ffffffff81788a10-ffffffff81788aab: crypto_shash_tfm_digest (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
