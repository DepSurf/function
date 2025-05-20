# Function: <code>crypto_destroy_tfm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8139c4d0)
Location: crypto/api.c:583
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/crypto_key.c:ext4_derive_key_aes
  - fs/ext4/crypto_key.c:ext4_free_crypt_info
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/blkcipher.c:skcipher_geniv_exit
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/shash.c:crypto_init_shash_ops
  - crypto/shash.c:crypto_exit_shash_ops_compat
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/ecb.c:crypto_ecb_exit_tfm
  - crypto/cbc.c:crypto_cbc_exit_tfm
  - crypto/rng.c:crypto_get_default_rng
  - crypto/rng.c:crypto_del_default_rng
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
```
**Symbols:**

```
ffffffff8139c4d0-ffffffff8139c547: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813d93c0)
Location: crypto/api.c:583
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/big_key.c:big_key_crypto_init
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/ecb.c:crypto_ecb_exit_tfm
  - crypto/cbc.c:crypto_cbc_exit_tfm
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/ctr.c:crypto_ctr_exit_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
```
**Symbols:**

```
ffffffff813d93c0-ffffffff813d9442: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813f0dd0)
Location: crypto/api.c:567
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/ecb.c:crypto_ecb_exit_tfm
  - crypto/cbc.c:crypto_cbc_exit_tfm
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/ctr.c:crypto_ctr_exit_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - arch/x86/power/hibernate_64.c:get_e820_md5
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff813f0dd0-ffffffff813f0e72: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813fd000)
Location: crypto/api.c:567
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/crypto/keyinfo.c:fscrypt_essiv_cleanup
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/ecb.c:crypto_ecb_exit_tfm
  - crypto/cbc.c:crypto_cbc_exit_tfm
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/ctr.c:crypto_ctr_exit_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - arch/x86/power/hibernate_64.c:get_e820_md5
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff813fd000-ffffffff813fd09c: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81425570)
Location: crypto/api.c:568
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/crypto/keyinfo.c:fscrypt_essiv_cleanup
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/ecb.c:crypto_ecb_exit_tfm
  - crypto/cbc.c:crypto_cbc_exit_tfm
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/ctr.c:crypto_ctr_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - arch/x86/power/hibernate_64.c:get_e820_md5
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff81425570-ffffffff81425615: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814583b0)
Location: crypto/api.c:571
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/crypto/keyinfo.c:fscrypt_essiv_cleanup
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/ecb.c:crypto_ecb_exit_tfm
  - crypto/cbc.c:crypto_cbc_exit_tfm
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/ctr.c:crypto_ctr_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - arch/x86/power/hibernate_64.c:get_e820_md5
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff814583b0-ffffffff8145845a: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81475a00)
Location: crypto/api.c:571
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:derive_essiv_salt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/crypto/keyinfo.c:fscrypt_essiv_cleanup
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/ecb.c:crypto_ecb_exit_tfm
  - crypto/cbc.c:crypto_cbc_exit_tfm
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/ctr.c:crypto_ctr_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff81475a00-ffffffff81475aaa: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a38e0)
Location: crypto/api.c:566
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/crypto/keyinfo.c:derive_essiv_salt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/crypto/keyinfo.c:fscrypt_essiv_cleanup
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff814a38e0-ffffffff814a3992: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814be500)
Location: crypto/api.c:567
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff814be500-ffffffff814be5b2: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8151eb20)
Location: crypto/api.c:555
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/fname.c:fscrypt_do_sha256
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:kdf_alloc
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_shash_release
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/geniv.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/digsig.c:digsig_cleanup
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - arch/x86/power/hibernate.c:get_e820_md5
```
**Symbols:**

```
ffffffff8151eb20-ffffffff8151eba1: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8153b980)
Location: crypto/api.c:561
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:kdf_alloc
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_shash_release
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/geniv.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/digsig.c:digsig_cleanup
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - arch/x86/power/hibernate.c:get_e820_md5
```
**Symbols:**

```
ffffffff8153b980-ffffffff8153ba01: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81544070)
Location: crypto/api.c:561
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:kdf_alloc
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/geniv.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/digsig.c:digsig_cleanup
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff81544070-ffffffff815440f8: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff815a4810)
Location: crypto/api.c:561
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:kdf_alloc
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/geniv.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/digsig.c:digsig_cleanup
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff815a4810-ffffffff815a4898: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8164b280)
Location: crypto/api.c:616
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/geniv.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/dh.c:dh_safe_prime_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/digsig.c:digsig_cleanup
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff8164b280-ffffffff8164b320: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff817044a0)
Location: crypto/api.c:615
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_init
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/geniv.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/dh.c:dh_safe_prime_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/digsig.c:digsig_cleanup
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff817044a0-ffffffff81704540: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8173e710)
Location: crypto/api.c:651
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_init
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/geniv.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/ahash.c:crypto_clone_ahash
  - crypto/shash.c:crypto_clone_shash
  - crypto/shash.c:crypto_clone_shash_ops_async
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/akcipher.c:crypto_exit_akcipher_ops_sig
  - crypto/dh.c:dh_safe_prime_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/digsig.c:digsig_cleanup
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff8173e710-ffffffff8173e7ef: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8177f590)
Location: crypto/api.c:651
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - mm/zswap.c:zswap_cpu_comp_dead
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_init_common
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/geniv.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/ahash.c:crypto_clone_ahash
  - crypto/ahash.c:crypto_exit_ahash_using_shash
  - crypto/shash.c:crypto_clone_shash
  - crypto/akcipher.c:crypto_exit_akcipher_ops_sig
  - crypto/dh.c:dh_safe_prime_exit_tfm
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/ecb.c:lskcipher_exit_tfm_simple2
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_exit_tfm
  - crypto/xts.c:xts_init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - block/blk-crypto-fallback.c:blk_crypto_fallback_start_using_mode
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
  - lib/digsig.c:digsig_cleanup
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_end
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_start
  - net/ipv4/tcp_sigpool.c:cpool_cleanup_work_cb
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_alloc_ahash
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff8177f590-ffffffff8177f66f: crypto_destroy_tfm (STB_GLOBAL)
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
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffff8000105b7308)
Location: crypto/api.c:567
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffff8000105b7308-ffff8000105b73c4: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (c07661e0)
Location: crypto/api.c:567
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
c07661e0-c0766294: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (c00000000073bf20)
Location: crypto/api.c:567
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
c00000000073bf20-c00000000073c06c: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffe0003fdcf6)
Location: crypto/api.c:567
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffe0003fdcf6-ffffffe0003fdd62: crypto_destroy_tfm (STB_GLOBAL)
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
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b6ae0)
Location: crypto/api.c:567
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff814b6ae0-ffffffff814b6b92: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a7500)
Location: crypto/api.c:567
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff814a7500-ffffffff814a75b2: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b2b70)
Location: crypto/api.c:567
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/libcrc32c.c:libcrc32c_mod_fini
  - lib/digsig.c:digsig_cleanup
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff814b2b70-ffffffff814b2c22: crypto_destroy_tfm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crypto_destroy_tfm(void *mem, struct crypto_tfm *tfm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814cb5f0)
Location: crypto/api.c:567
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_dead
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypto
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/pstore/platform.c:pstore_unregister
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:init_desc
  - crypto/aead.c:aead_exit_geniv
  - crypto/skcipher.c:skcipher_exit_tfm_simple
  - crypto/skcipher.c:crypto_alloc_sync_skcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_ablkcipher
  - crypto/skcipher.c:crypto_exit_skcipher_ops_blkcipher
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/rsa-pkcs1pad.c:pkcs1pad_exit_tfm
  - crypto/scompress.c:crypto_exit_scomp_ops_async
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/crypto_null.c:crypto_put_default_null_skcipher
  - crypto/cts.c:crypto_cts_exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:exit_tfm
  - crypto/xts.c:init_tfm
  - crypto/ctr.c:crypto_rfc3686_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_exit_tfm
  - crypto/gcm.c:crypto_rfc4543_init_tfm
  - crypto/gcm.c:crypto_rfc4106_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_exit_tfm
  - crypto/gcm.c:crypto_gcm_init_tfm
  - crypto/rng.c:crypto_del_default_rng
  - crypto/rng.c:crypto_get_default_rng
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_async_seed
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/public_key.c:software_key_query
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/digsig.c:digsig_cleanup
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
**Symbols:**

```
ffffffff814cb5f0-ffffffff814cb6a2: crypto_destroy_tfm (STB_GLOBAL)
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
