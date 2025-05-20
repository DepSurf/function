# Function: <code>memzero_explicit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void memzero_explicit(void *s, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f2010)
Location: lib/string.c:696
Inline: False
Direct callers:
  - fs/ext4/crypto_key.c:_ext4_get_encryption_info
  - fs/ext4/crypto_key.c:_ext4_get_encryption_info
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - crypto/sha256_generic.c:sha256_transform
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_entropy
  - drivers/char/random.c:extract_entropy_user
```
**Symbols:**

```
ffffffff813f2010-ffffffff813f2025: memzero_explicit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void memzero_explicit(void *s, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814389b0)
Location: lib/string.c:693
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - crypto/sha256_generic.c:sha256_transform
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff814389b0-ffffffff814389c5: memzero_explicit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void memzero_explicit(void *s, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814559a0)
Location: lib/string.c:693
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - crypto/sha256_generic.c:sha256_transform
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
**Symbols:**

```
ffffffff814559a0-ffffffff814559b5: memzero_explicit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memzero_explicit(void *s, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f72e0)
Location: lib/string.c:719
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_crypt
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - crypto/sha256_generic.c:sha256_transform
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
**Symbols:**

```
ffffffff818f72e0-ffffffff818f72f0: memzero_explicit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memzero_explicit(void *s, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197dce0)
Location: lib/string.c:720
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - crypto/sha256_generic.c:sha256_transform
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
**Symbols:**

```
ffffffff8197dce0-ffffffff8197dcf0: memzero_explicit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memzero_explicit(void *s, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819da1c0)
Location: lib/string.c:720
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - crypto/sha256_generic.c:sha256_transform
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
  - arch/x86/power/hibernate_64.c:get_e820_md5
```
**Symbols:**

```
ffffffff819da1c0-ffffffff819da1d0: memzero_explicit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memzero_explicit(void *s, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a123e0)
Location: lib/string.c:721
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - crypto/sha256_generic.c:sha256_transform
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81a123e0-ffffffff81a123f0: memzero_explicit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memzero_explicit(void *s, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a818b0)
Location: lib/string.c:763
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/sha1_generic.c:sha1_generic_block_fn
  - crypto/sha256_generic.c:sha256_transform
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
  - crypto/ghash-generic.c:ghash_setkey
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
```
**Symbols:**

```
ffffffff81a818b0-ffffffff81a818c0: memzero_explicit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff8134b932)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/crypto/keyring.c (ffffffff8134cf9f)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff8134daa3)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In fs/ecryptfs/crypto.c (ffffffff814153f8)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/gc.c (ffffffff81444639)
Location: include/linux/string.h:247
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8144968c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/dh.c (ffffffff8144e373)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814522a8)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In crypto/sha1_generic.c (ffffffff814cb377)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_generic_block_fn
```
```
In crypto/cts.c (ffffffff814cde17)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff814d5ff6)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (ffffffff814d8391)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In lib/crypto/sha256.c (ffffffff8153120f)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/char/random.c (ffffffff816bf81c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127305f)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
```
```
In mm/slab_common.c (ffffffff8127d9f7)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - mm/slab_common.c:kzfree
```
```
In fs/crypto/hkdf.c (ffffffff81391282)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keyring.c (ffffffff813930ba)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff81393376)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/verity/hash_algs.c (ffffffff81396895)
Location: include/linux/string.h:248
Inline: True
```
```
In security/keys/gc.c (ffffffff81495670)
Location: include/linux/string.h:248
Inline: True
```
```
In security/keys/dh.c (ffffffff8149ff11)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a4fde)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In crypto/shash.c (ffffffff81525bc8)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/sha1_generic.c (ffffffff8152ab15)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/cts.c (ffffffff8152d1c6)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff81535bb6)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (ffffffff81537b91)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In block/keyslot-manager.c (ffffffff81580f97)
Location: include/linux/string.h:248
Inline: True
```
```
In lib/crypto/sha256.c (ffffffff8159540b)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/char/random.c (ffffffff817734e6)
Location: include/linux/string.h:248
Inline: True
Inline callers:
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d7c9)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
```
```
In mm/slab_common.c (ffffffff81287bfc)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
```
```
In fs/crypto/hkdf.c (ffffffff813a26e2)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keyring.c (ffffffff813a441a)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff813a476e)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/verity/hash_algs.c (ffffffff813a84c5)
Location: include/linux/string.h:242
Inline: True
```
```
In security/keys/gc.c (ffffffff814b30d0)
Location: include/linux/string.h:242
Inline: True
```
```
In security/keys/dh.c (ffffffff814bd921)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c27b7)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In crypto/shash.c (ffffffff81542af8)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/sha1_generic.c (ffffffff81547ae5)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha512_generic.c (ffffffff81548711)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/cts.c (ffffffff8154a236)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff81552b26)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (ffffffff81554a11)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In block/keyslot-manager.c (ffffffff8159dfb7)
Location: include/linux/string.h:242
Inline: True
```
```
In lib/crypto/sha256.c (ffffffff815b109e)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256_update
```
```
In drivers/tty/tty_io.c (ffffffff81750c01)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:iterate_tty_read
```
```
In drivers/char/random.c (ffffffff8178e4b6)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282999)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
```
```
In mm/slab_common.c (ffffffff8128cd8c)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
```
```
In fs/crypto/hkdf.c (ffffffff813a9865)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keyring.c (ffffffff813ab60a)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff813ab8ae)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/verity/hash_algs.c (ffffffff813af515)
Location: include/linux/string.h:242
Inline: True
```
```
In security/keys/gc.c (ffffffff814b8f10)
Location: include/linux/string.h:242
Inline: True
```
```
In security/keys/dh.c (ffffffff814c378e)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c90a7)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In crypto/shash.c (ffffffff8154b198)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/sha1_generic.c (ffffffff815501a5)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha512_generic.c (ffffffff81550ddd)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/cts.c (ffffffff81552873)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff8155b3e6)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (ffffffff8155d181)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In block/keyslot-manager.c (ffffffff815a4d07)
Location: include/linux/string.h:242
Inline: True
```
```
In lib/crypto/sha256.c (ffffffff815bbeae)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256_update
```
```
In drivers/tty/tty_io.c (ffffffff81734afe)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/char/random.c (ffffffff81770d26)
Location: include/linux/string.h:242
Inline: True
Inline callers:
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0b99)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
```
```
In mm/slab_common.c (ffffffff812cd31e)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
```
```
In mm/kfence/core.c (ffffffff8133c44c)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In fs/crypto/hkdf.c (ffffffff813f90a5)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keyring.c (ffffffff813fae9a)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff813fb13e)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/verity/hash_algs.c (ffffffff813ff0c5)
Location: include/linux/string.h:235
Inline: True
```
```
In security/keys/gc.c (ffffffff81511740)
Location: include/linux/string.h:235
Inline: True
```
```
In security/keys/dh.c (ffffffff8151c15e)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81521567)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In crypto/shash.c (ffffffff815ab978)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/sha1_generic.c (ffffffff815b0b25)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha512_generic.c (ffffffff815b1db9)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/cts.c (ffffffff815b387a)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff815bbd86)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (ffffffff815be4b1)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In block/keyslot-manager.c (ffffffff8160d777)
Location: include/linux/string.h:235
Inline: True
```
```
In lib/crypto/sha256.c (ffffffff81622cf1)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha256_update
```
```
In drivers/tty/tty_io.c (ffffffff817b545e)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/char/random.c (ffffffff817f6835)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d74f)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
```
```
In mm/slab_common.c (ffffffff8132bc2d)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
```
```
In mm/kfence/core.c (ffffffff813af68c)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In fs/crypto/hkdf.c (ffffffff8146be93)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keyring.c (ffffffff8146dc19)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:fscrypt_key_destroy
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff8146e459)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/verity/hash_algs.c (ffffffff814733fd)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/keys/gc.c (ffffffff815a3a30)
Location: include/linux/string.h:235
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b4e90)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In crypto/shash.c (ffffffff81653274)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/sha1_generic.c (ffffffff8165908a)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha512_generic.c (ffffffff8165a8e9)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/cts.c (ffffffff8165c5e3)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff8166556a)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
```
```
In crypto/ghash-generic.c (ffffffff81667f03)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In crypto/kdf_sp800108.c (ffffffff8166e28d)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In block/blk-crypto-profile.c (ffffffff816c2293)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In lib/crypto/blake2s.c (ffffffff816f03f4)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - lib/crypto/blake2s.c:blake2s_final
```
```
In lib/crypto/sha256.c (ffffffff816f28ad)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_update
```
```
In drivers/tty/tty_io.c (ffffffff818f1378)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/char/random.c (ffffffff81934330)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:mix_interrupt_randomness
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_fast_key_erasure
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff83e73d22)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
```
```
In mm/util.c (ffffffff8139142f)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
```
```
In mm/slab_common.c (ffffffff813a25cd)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
```
```
In mm/kfence/core.c (ffffffff8142fc1c)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In fs/crypto/hkdf.c (ffffffff814fd1c3)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keyring.c (ffffffff814ff1f9)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff814ffa92)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In fs/verity/hash_algs.c (ffffffff8150528d)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/keys/gc.c (ffffffff8164d6c0)
Location: include/linux/string.h:235
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165fe80)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In crypto/shash.c (ffffffff8170cf84)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/sha1_generic.c (ffffffff8171350a)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:sha1_final
```
```
In crypto/sha512_generic.c (ffffffff81714bb5)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/cts.c (ffffffff81715fd3)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff8172037a)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
```
```
In crypto/ghash-generic.c (ffffffff817225c3)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In crypto/kdf_sp800108.c (ffffffff81729479)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In block/blk-crypto-profile.c (ffffffff81783593)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_profile_init
```
```
In lib/crypto/blake2s.c (ffffffff817e1ef4)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - lib/crypto/blake2s.c:blake2s_final
```
```
In lib/crypto/sha256.c (ffffffff817e46bd)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_update
```
```
In drivers/tty/tty_io.c (ffffffff81a4a558)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/char/random.c (ffffffff81a93f60)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:mix_interrupt_randomness
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_fast_key_erasure
  - drivers/char/random.c:crng_reseed
```
```
In drivers/firmware/efi/efi.c (ffffffff83f07b50)
Location: include/linux/string.h:235
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff836957e7)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
```
```
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e0bef)
Location: include/linux/string.h:236
Inline: True
```
```
In mm/util.c (ffffffff813c3dff)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
```
```
In mm/slab_common.c (ffffffff813d5a8d)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
```
```
In mm/kfence/core.c (ffffffff81465689)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In fs/crypto/hkdf.c (ffffffff81534723)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keyring.c (ffffffff81536dac)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff81537062)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In security/keys/gc.c (ffffffff81685e60)
Location: include/linux/string.h:236
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816987e5)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In crypto/shash.c (ffffffff817468e4)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/sha1_generic.c (ffffffff8174e688)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
```
In crypto/sha512_generic.c (ffffffff8174fae9)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/cts.c (ffffffff817518c7)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff8175bc6f)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
```
```
In crypto/jitterentropy-kcapi.c (ffffffff836fd3f4)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - crypto/jitterentropy-kcapi.c:jent_hash_time
```
```
In crypto/ghash-generic.c (ffffffff8175e8e3)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In crypto/kdf_sp800108.c (ffffffff817657d9)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In block/blk-crypto-profile.c (ffffffff817c3697)
Location: include/linux/string.h:236
Inline: True
```
```
In lib/crypto/blake2s.c (ffffffff81821e54)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - lib/crypto/blake2s.c:blake2s_final
```
```
In lib/crypto/sha256.c (ffffffff818247e9)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_transform_blocks
```
```
In drivers/tty/tty_io.c (ffffffff81a9478c)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/char/random.c (ffffffff81adea90)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:mix_interrupt_randomness
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_fast_key_erasure
  - drivers/char/random.c:crng_reseed
```
```
In drivers/firmware/efi/efi.c (ffffffff8372dc6b)
Location: include/linux/string.h:236
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff838c5727)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:parse_setup_data
  - arch/x86/kernel/setup.c:parse_setup_data
```
```
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e946f)
Location: include/linux/string.h:274
Inline: True
```
```
In mm/util.c (ffffffff813ee9af)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - mm/util.c:kvfree_sensitive
```
```
In mm/slab_common.c (ffffffff813ff75d)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - mm/slab_common.c:kfree_sensitive
```
```
In mm/kfence/core.c (ffffffff814941c1)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_late
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
```
In fs/crypto/hkdf.c (ffffffff815696e3)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keyring.c (ffffffff8156be5c)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_add_test_dummy_key
  - fs/crypto/keyring.c:fscrypt_get_test_dummy_key_identifier
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff8156c132)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
```
In security/keys/gc.c (ffffffff816c2280)
Location: include/linux/string.h:274
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d4e65)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
```
```
In crypto/shash.c (ffffffff81788a64)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/sha1_generic.c (ffffffff817902d8)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
```
In crypto/sha512_generic.c (ffffffff81791739)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/cts.c (ffffffff81793747)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff8179db6f)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_seed_from_random
```
```
In crypto/jitterentropy-kcapi.c (ffffffff83930a04)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - crypto/jitterentropy-kcapi.c:jent_kvzfree
```
```
In crypto/ghash-generic.c (ffffffff817a00d3)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In crypto/kdf_sp800108.c (ffffffff817a73d9)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In block/blk-crypto-profile.c (ffffffff81808327)
Location: include/linux/string.h:274
Inline: True
```
```
In lib/crypto/blake2s.c (ffffffff81867e94)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - lib/crypto/blake2s.c:blake2s_final
```
```
In lib/crypto/sha256.c (ffffffff8186a829)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256
  - lib/crypto/sha256.c:sha224_final
  - lib/crypto/sha256.c:sha256_transform_blocks
```
```
In drivers/tty/tty_io.c (ffffffff81ae734b)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/char/random.c (ffffffff81b31eb0)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:mix_interrupt_randomness
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_fast_key_erasure
  - drivers/char/random.c:crng_reseed
```
```
In drivers/char/hw_random/core.c (ffffffff81b3aabe)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:rng_dev_read
```
```
In drivers/firmware/efi/efi.c (ffffffff8396204b)
Location: include/linux/string.h:274
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffff80001040c3b0)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/crypto/keyring.c (ffff80001040debc)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffff80001040ed90)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In fs/ecryptfs/crypto.c (ffff8000104f6a74)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/gc.c (ffff80001052d1c0)
Location: include/linux/string.h:247
Inline: True
```
```
In security/keys/keyctl.c (ffff8000105332d0)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__arm64_sys_add_key
```
```
In security/keys/dh.c (ffff8000105384d0)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053dc90)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In crypto/sha1_generic.c (ffff8000105c727c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_generic_block_fn
```
```
In crypto/cts.c (ffff8000105c9d40)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffff8000105d1df0)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (ffff8000105d41c4)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In lib/crypto/sha256.c (ffff80001063d2b4)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/char/random.c (ffff8000108b0b74)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (c05d94c4)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/crypto/keyring.c (c05dabf8)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (c05db8b4)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In fs/ecryptfs/crypto.c (c06b44cc)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/gc.c (c06e5a08)
Location: include/linux/string.h:247
Inline: True
```
```
In security/keys/keyctl.c (c06eab70)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/dh.c (c06eee44)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/encrypted-keys/encrypted.c (c06f3424)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In crypto/sha1_generic.c (c0773ea8)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_generic_block_fn
```
```
In crypto/cts.c (c077787c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (c077f68c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (c0781cc4)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In lib/crypto/sha256.c (c07e3758)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/char/random.c (c09aa584)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (c000000000519358)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/crypto/keyring.c (c00000000051b2ac)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (c00000000051c438)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In fs/ecryptfs/crypto.c (c000000000637a68)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/gc.c (c0000000006792a4)
Location: include/linux/string.h:247
Inline: True
```
```
In security/keys/keyctl.c (c000000000680ef8)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/dh.c (c0000000006876f8)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068d098)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In crypto/sha1_generic.c (c000000000750e34)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_generic_block_fn
```
```
In crypto/cts.c (c0000000007545ec)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (c00000000075eda8)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (c00000000076187c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In lib/crypto/sha256.c (c0000000007e4bec)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/char/random.c (c0000000009484b4)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffe0002b5cb0)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/crypto/keyring.c (ffffffe0002b6cfe)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:wipe_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffe0002b7b6c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In fs/ecryptfs/crypto.c (ffffffe0003656be)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/gc.c (ffffffe00038ef36)
Location: include/linux/string.h:247
Inline: True
```
```
In security/keys/keyctl.c (ffffffe00039392e)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/dh.c (ffffffe00039726c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039b100)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In crypto/sha1_generic.c (ffffffe00040b33a)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_generic_block_fn
```
```
In crypto/cts.c (ffffffe00040defe)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffe000415580)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (ffffffe00041850e)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In lib/crypto/sha256.c (ffffffe00046affe)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/char/random.c (ffffffe000562298)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff81343f12)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/crypto/keyring.c (ffffffff8134557f)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff81346083)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In fs/ecryptfs/crypto.c (ffffffff8140d9d8)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/gc.c (ffffffff8143cc19)
Location: include/linux/string.h:247
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81441c6c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/dh.c (ffffffff81446953)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a888)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In crypto/sha1_generic.c (ffffffff814c3957)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_generic_block_fn
```
```
In crypto/cts.c (ffffffff814c63f7)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff814ce5d6)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (ffffffff814d0971)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In lib/crypto/sha256.c (ffffffff815297ef)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/char/random.c (ffffffff8168526c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff81334bf2)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/crypto/keyring.c (ffffffff8133625f)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff81336d63)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In fs/ecryptfs/crypto.c (ffffffff813fe458)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/gc.c (ffffffff8142d689)
Location: include/linux/string.h:247
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814326dc)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/dh.c (ffffffff814373a3)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143b2d8)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In crypto/sha1_generic.c (ffffffff814b4377)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_generic_block_fn
```
```
In crypto/cts.c (ffffffff814b6e17)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff814beff6)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (ffffffff814c1391)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In lib/crypto/sha256.c (ffffffff81519acf)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/char/random.c (ffffffff81662f0c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff813419e2)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/crypto/keyring.c (ffffffff8134304f)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff81343b53)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In fs/ecryptfs/crypto.c (ffffffff8140ad58)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/gc.c (ffffffff81438db9)
Location: include/linux/string.h:247
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8143de0c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/dh.c (ffffffff814429f3)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446928)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In crypto/sha1_generic.c (ffffffff814bf9e7)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_generic_block_fn
```
```
In crypto/cts.c (ffffffff814c2487)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff814ca666)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (ffffffff814cca01)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In lib/crypto/sha256.c (ffffffff8152587f)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/char/random.c (ffffffff816b365c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffff81354ce2)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/crypto/keyring.c (ffffffff8135633c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:move_master_key_secret
```
```
In fs/crypto/keysetup.c (ffffffff81356e33)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
```
```
In fs/ecryptfs/crypto.c (ffffffff814209f8)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/gc.c (ffffffff8144ff29)
Location: include/linux/string.h:247
Inline: True
```
```
In security/keys/keyctl.c (ffffffff81454f8c)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/dh.c (ffffffff81459d23)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145dc58)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:datablob_hmac_verify
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In crypto/sha1_generic.c (ffffffff814d84b7)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/sha1_generic.c:sha1_generic_block_fn
```
```
In crypto/cts.c (ffffffff814daf57)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/cts.c:cts_cbc_encrypt
```
```
In crypto/drbg.c (ffffffff814e3136)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - crypto/drbg.c:drbg_seed
  - crypto/drbg.c:drbg_async_seed
```
```
In crypto/ghash-generic.c (ffffffff814e54d1)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_setkey
```
```
In lib/crypto/sha256.c (ffffffff8153f1ff)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
```
```
In drivers/char/random.c (ffffffff816cdbdc)
Location: include/linux/string.h:247
Inline: True
Inline callers:
  - drivers/char/random.c:urandom_read
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:crng_reseed
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
</ul>
