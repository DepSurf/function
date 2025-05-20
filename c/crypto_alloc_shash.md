# Function: <code>crypto_alloc_shash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813a3d90)
Location: crypto/shash.c:576
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
**Symbols:**

```
ffffffff813a3d90-ffffffff813a3dab: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813dfc50)
Location: crypto/shash.c:429
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff813dfc50-ffffffff813dfc6b: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813f81e0)
Location: crypto/shash.c:429
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff813f81e0-ffffffff813f81fb: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814046a0)
Location: crypto/shash.c:430
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff814046a0-ffffffff814046bb: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8142cfa0)
Location: crypto/shash.c:450
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff8142cfa0-ffffffff8142cfbb: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8145fc10)
Location: crypto/shash.c:450
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/digsig.c:digsig_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff8145fc10-ffffffff8145fc2b: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8147d670)
Location: crypto/shash.c:459
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/keyinfo.c:derive_essiv_salt
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/digsig.c:digsig_init
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff8147d670-ffffffff8147d68b: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814ab970)
Location: crypto/shash.c:447
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/keyinfo.c:derive_essiv_salt
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/digsig.c:digsig_init
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff814ab970-ffffffff814ab98b: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814c6650)
Location: crypto/shash.c:447
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/digsig.c:digsig_init
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff814c6650-ffffffff814c666b: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815253e0)
Location: crypto/shash.c:505
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/fname.c:fscrypt_do_sha256
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:kdf_alloc
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/digsig.c:digsig_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - arch/x86/power/hibernate.c:get_e820_md5
```
**Symbols:**

```
ffffffff815253e0-ffffffff815253fb: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81542300)
Location: crypto/shash.c:505
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:kdf_alloc
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/digsig.c:digsig_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - arch/x86/power/hibernate.c:get_e820_md5
```
**Symbols:**

```
ffffffff81542300-ffffffff81542321: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154a9a0)
Location: crypto/shash.c:517
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:kdf_alloc
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/digsig.c:digsig_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff8154a9a0-ffffffff8154a9c1: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab180)
Location: crypto/shash.c:517
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:kdf_alloc
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/digsig.c:digsig_init
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff815ab180-ffffffff815ab1a1: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff816528f0)
Location: crypto/shash.c:517
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ext4/super.c:__ext4_fill_super
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/digsig.c:digsig_init
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff816528f0-ffffffff81652920: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170c060)
Location: crypto/shash.c:507
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/digsig.c:digsig_init
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff8170c060-ffffffff8170c090: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81745a60)
Location: crypto/shash.c:572
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_init
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/digsig.c:digsig_init
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff81745a60-ffffffff81745a90: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff817883d0)
Location: crypto/shash.c:302
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_check_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_init
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/digsig.c:digsig_init
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
**Symbols:**

```
ffffffff817883d0-ffffffff81788400: crypto_alloc_shash (STB_GLOBAL)
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
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffff8000105c1978)
Location: crypto/shash.c:447
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/digsig.c:digsig_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffff8000105c1978-ffff8000105c19c4: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c076f038)
Location: crypto/shash.c:447
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/digsig.c:digsig_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
c076f038-c076f064: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c000000000749e40)
Location: crypto/shash.c:447
Inline: False
Direct callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/digsig.c:digsig_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
c000000000749e40-c000000000749e88: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffe0004065a0)
Location: crypto/shash.c:447
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/digsig.c:digsig_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffe0004065a0-ffffffe0004065e2: crypto_alloc_shash (STB_GLOBAL)
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
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814bec30)
Location: crypto/shash.c:447
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/digsig.c:digsig_init
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff814bec30-ffffffff814bec4b: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814af650)
Location: crypto/shash.c:447
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/digsig.c:digsig_init
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff814af650-ffffffff814af66b: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814bacc0)
Location: crypto/shash.c:447
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/libcrc32c.c:libcrc32c_mod_init
  - lib/digsig.c:digsig_init
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff814bacc0-ffffffff814bacdb: crypto_alloc_shash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct crypto_shash *crypto_alloc_shash(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814d3770)
Location: crypto/shash.c:447
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ext4/super.c:ext4_fill_super
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/ecryptfs/crypto.c:ecryptfs_init_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/apparmor/crypto.c:init_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_alloc_tfm
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_init
  - lib/digsig.c:digsig_init
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
**Symbols:**

```
ffffffff814d3770-ffffffff814d378b: crypto_alloc_shash (STB_GLOBAL)
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
