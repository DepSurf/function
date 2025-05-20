# Function: <code>crypto_alloc_skcipher</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813a1c40)
Location: crypto/skcipher.c:239
Inline: False
```
**Symbols:**

```
ffffffff813a1c40-ffffffff813a1c5b: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813de520)
Location: crypto/skcipher.c:336
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/big_key.c:big_key_crypto_init
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff813de520-ffffffff813de53b: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813f5f50)
Location: crypto/skcipher.c:878
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/big_key.c:big_key_init
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff813f5f50-ffffffff813f5f6b: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814022e0)
Location: crypto/skcipher.c:918
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/big_key.c:big_key_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814022e0-ffffffff814022fb: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8142a950)
Location: crypto/skcipher.c:924
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff8142a950-ffffffff8142a96b: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8145d6a0)
Location: crypto/skcipher.c:947
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff8145d6a0-ffffffff8145d6bb: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8147af20)
Location: crypto/skcipher.c:951
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff8147af20-ffffffff8147af3b: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a8f80)
Location: crypto/skcipher.c:985
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814a8f80-ffffffff814a8f9b: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c3be0)
Location: crypto/skcipher.c:989
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814c3be0-ffffffff814c3bfb: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81522bb0)
Location: crypto/skcipher.c:758
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
```
**Symbols:**

```
ffffffff81522bb0-ffffffff81522bcb: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153faf0)
Location: crypto/skcipher.c:758
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_process_key_cipher
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
```
**Symbols:**

```
ffffffff8153faf0-ffffffff8153fb11: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81548060)
Location: crypto/skcipher.c:753
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
```
**Symbols:**

```
ffffffff81548060-ffffffff81548081: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a8840)
Location: crypto/skcipher.c:753
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
```
**Symbols:**

```
ffffffff815a8840-ffffffff815a8861: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8164fbc0)
Location: crypto/skcipher.c:753
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
```
**Symbols:**

```
ffffffff8164fbc0-ffffffff8164fbf0: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81709020)
Location: crypto/skcipher.c:753
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
```
**Symbols:**

```
ffffffff81709020-ffffffff81709050: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81742870)
Location: crypto/skcipher.c:800
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
```
**Symbols:**

```
ffffffff81742870-ffffffff817428a0: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81784b60)
Location: crypto/skcipher.c:899
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
```
**Symbols:**

```
ffffffff81784b60-ffffffff81784b90: crypto_alloc_skcipher (STB_GLOBAL)
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
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105be5a0)
Location: crypto/skcipher.c:989
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffff8000105be5a0-ffff8000105be5ec: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076c2f4)
Location: crypto/skcipher.c:989
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
c076c2f4-c076c320: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c000000000745d90)
Location: crypto/skcipher.c:989
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
c000000000745d90-c000000000745dd8: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe0004039b4)
Location: crypto/skcipher.c:989
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffe0004039b4-ffffffe0004039f6: crypto_alloc_skcipher (STB_GLOBAL)
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
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bc1c0)
Location: crypto/skcipher.c:989
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814bc1c0-ffffffff814bc1db: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814acbe0)
Location: crypto/skcipher.c:989
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814acbe0-ffffffff814acbfb: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b8250)
Location: crypto/skcipher.c:989
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814b8250-ffffffff814b826b: crypto_alloc_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct crypto_skcipher *crypto_alloc_skcipher(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d0d30)
Location: crypto/skcipher.c:989
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_ctx
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814d0d30-ffffffff814d0d4b: crypto_alloc_skcipher (STB_GLOBAL)
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
