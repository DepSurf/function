# Function: <code>crypto_shash_tfm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:646
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:646
Inline: True
```
```
In fs/ext4/super.c (ffffffff812b9028)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/jbd2/journal.c (ffffffff812f1d89)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In security/keys/trusted.c (ffffffff8139bacf)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8139bb04)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:646
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81f9a10f)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8139b375)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff813a39dd)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
  - crypto/shash.c:crypto_init_shash_ops
  - crypto/shash.c:crypto_exit_shash_ops_compat
```
```
In crypto/hmac.c (ffffffff813a4f1f)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:646
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:646
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:646
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff813adba8)
Location: include/crypto/hash.h:646
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813aed0f)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813af548)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff820af837)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff820af84d)
Location: include/crypto/hash.h:646
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In fs/ext4/super.c (ffffffff812eabf4)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff8131f629)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff81339c81)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff8133d13a)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/trusted.c (ffffffff813d892f)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813d8964)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813d489c)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813d81dd)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff813dfb3d)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff813e271f)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In crypto/drbg.c (ffffffff813eb7fb)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff813f1a6a)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813f2939)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813f354f)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/crc-t10dif.c (ffffffff820e74b6)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff820e74cc)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In fs/ext4/super.c (ffffffff81300a98)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff813356b2)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff8134fa21)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff81352eca)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/trusted.c (ffffffff813f05df)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813f0614)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
  - security/keys/encrypted-keys/encrypted.c:encrypted_shash_release
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813ec2ec)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813efe8d)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff813f80cd)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff813fb73f)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:674
Inline: True
```
```
In crypto/drbg.c (ffffffff81404f5b)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8140b2ba)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8140c1a9)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8140cdbf)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/crc-t10dif.c (ffffffff821cd3d2)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff821cd3e8)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a4956)
Location: include/crypto/hash.h:674
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:680
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:680
Inline: True
```
```
In fs/crypto/keyinfo.c (ffffffff822c2069)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:fscrypt_essiv_cleanup
```
```
In fs/ext4/super.c (ffffffff81335908)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff8134a43a)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff813644ba)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff813679f5)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff81395f08)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81398be9)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff822c22d2)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:680
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813f86dc)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813fc4b2)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8140458d)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff814081df)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:680
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:680
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:680
Inline: True
```
```
In crypto/drbg.c (ffffffff8141272b)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81418dfe)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/crypto/hash.h:680
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8141a5d6)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff822c253d)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff822c2553)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cb123)
Location: include/crypto/hash.h:680
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:688
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:688
Inline: True
```
```
In fs/crypto/keyinfo.c (ffffffff828d51e9)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:fscrypt_essiv_cleanup
```
```
In fs/ext4/super.c (ffffffff81359e12)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff8136ea8a)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff813891da)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff8138c73a)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff813bb688)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff813be3f9)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff828d5452)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:688
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81420a5d)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814249d5)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8142ce8d)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff81430bff)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:688
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:688
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:688
Inline: True
```
```
In crypto/drbg.c (ffffffff8143cebb)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:688
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8144392e)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/crypto/hash.h:688
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8144567b)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/crc-t10dif.c (ffffffff828d5711)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff828d5727)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In net/ipv6/seg6_hmac.c (ffffffff8194fec3)
Location: include/crypto/hash.h:688
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:687
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:687
Inline: True
```
```
In fs/crypto/keyinfo.c (ffffffff82906a38)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:fscrypt_essiv_cleanup
```
```
In fs/ext4/super.c (ffffffff813887a8)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff8139d0c6)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff813b803e)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff813bb4fe)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff813ec52d)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff82715cb7)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82906ca1)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:687
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81452f07)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81457121)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8145fafa)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff8146375f)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:687
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:687
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:687
Inline: True
```
```
In crypto/drbg.c (ffffffff8146fcab)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:687
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814768d5)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814777fe)
Location: include/crypto/hash.h:687
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814783ca)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/crc-t10dif.c (ffffffff82906f83)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff82906f99)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9603)
Location: include/crypto/hash.h:687
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:699
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:699
Inline: True
```
```
In fs/crypto/keyinfo.c (ffffffff81310d23)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_essiv_salt
  - fs/crypto/keyinfo.c:fscrypt_essiv_cleanup
```
```
In fs/ext4/super.c (ffffffff813a1a10)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff813b5e36)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff813d15be)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff813d4b2d)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff814070d6)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff828cd0fc)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82adea73)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:699
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81470067)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814745d0)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8147d57a)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff814813df)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:699
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:699
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:699
Inline: True
```
```
In crypto/drbg.c (ffffffff8148d66b)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:699
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81494a75)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/crypto/hash.h:699
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814965f1)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/crc-t10dif.c (ffffffff82aded28)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff82aded3b)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In arch/x86/power/hibernate.c (ffffffff8188f10c)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0103)
Location: include/crypto/hash.h:699
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In fs/crypto/keyinfo.c (ffffffff81338266)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:derive_essiv_salt
  - fs/crypto/keyinfo.c:fscrypt_essiv_cleanup
```
```
In fs/ext4/super.c (ffffffff813cbcfc)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff813e0558)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff813fc0f1)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff813ff488)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff8143418e)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff828e6b13)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82b03bc2)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8149da40)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a22e2)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814ab87a)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff814af5af)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/drbg.c (ffffffff814bafec)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814c244f)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814c379c)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c40d8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff82b03e69)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff82b03e7c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In arch/x86/power/hibernate.c (ffffffff818d90ff)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4ed75)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff8134bb39)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keysetup.c (ffffffff8134d586)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/ext4/super.c (ffffffff813e50ae)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff813fa598)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff81415fd1)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff81419378)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff8144dede)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff828ef60d)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82b12a74)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b7e80)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814bcfb2)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814c655a)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff814ca23f)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/drbg.c (ffffffff814d3dbc)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814db27f)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814dc6b0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814dcfb8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff82b12d2d)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff82b12d40)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In arch/x86/power/hibernate.c (ffffffff8190b0ff)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a85a05)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:711
Inline: True
```
```
In fs/crypto/fname.c (ffffffff813905ed)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_do_sha256
```
```
In fs/crypto/hkdf.c (ffffffff81391489)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/ext4/super.c (ffffffff81432211)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff81447aae)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff81464571)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff81468525)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff814a04c4)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff82d04813)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_shash_release
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82f244ef)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:711
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff82d07e21)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8151d8c8)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff815252ca)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff815296af)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:711
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:711
Inline: True
```
```
In crypto/drbg.c (ffffffff8153310c)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8153ab6f)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8153bfb9)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8153cd8e)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff82f247b4)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
```
```
In lib/digsig.c (ffffffff82f247c7)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80a35)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc11f)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067004)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:719
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff813a28e9)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/ext4/super.c (ffffffff8144b018)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff8146446e)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff8147fd31)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff814839a5)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff814bded4)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff82ff1be0)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_shash_release
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8321ca8f)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:719
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff82ff530e)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8153a6bc)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff815421ba)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff8154665f)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:719
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:719
Inline: True
```
```
In crypto/drbg.c (ffffffff8155005c)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff815579a0)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81558c59)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815598ee)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff8321cd54)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
```
```
In lib/digsig.c (ffffffff8321cd67)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b902a5)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
```
In arch/x86/power/hibernate.c (ffffffff81bd10ff)
Location: include/crypto/hash.h:719
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810675a0)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff813a9a79)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/ext4/super.c (ffffffff814509cc)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff81469be1)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff81485581)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff81489431)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff814c3d3e)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c4e92)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83450a62)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff83200020)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81542d7c)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8154a85a)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff8154ed1f)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In crypto/drbg.c (ffffffff8155885c)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff815602a0)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81561589)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815621fe)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff83450d27)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
```
```
In lib/digsig.c (ffffffff83450d3a)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7f4e5)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071950)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff813f92b9)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/ext4/super.c (ffffffff814a4023)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff814c00e3)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff814dcca1)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff814e0c31)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff8151c70e)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151d8b2)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83543fe9)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff832e74c2)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/evm/evm_crypto.c (ffffffff815a3487)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff815ab03a)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff815af66f)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In crypto/drbg.c (ffffffff815b9b0c)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff815c164b)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff815c29cd)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815c360b)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff835442c0)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
```
```
In lib/digsig.c (ffffffff835442d3)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In drivers/md/dm-ima.c (ffffffff81a067c8)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4ad5e)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107fa00)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff8146c0d9)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/ext4/super.c (ffffffff8152bdfc)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff8154a8e5)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff8156ac71)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff8156ee04)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff815af888)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b0c82)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83721ff7)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8349e5cd)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81649d6e)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff816527aa)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff81657dc1)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:721
Inline: True
```
```
In crypto/drbg.c (ffffffff816630ec)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8166bac6)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8166ce57)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8166dbe3)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff81e8b1f8)
Location: include/crypto/hash.h:721
Inline: True
```
```
In lib/crc-t10dif.c (ffffffff837223bd)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
```
```
In lib/crc64-rocksoft.c (ffffffff837223f5)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
```
```
In lib/digsig.c (ffffffff83722412)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In drivers/md/dm-ima.c (ffffffff81b6e4d2)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In net/ipv6/seg6_hmac.c (ffffffff81dea5b1)
Location: include/crypto/hash.h:721
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091af0)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff814fd419)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/ext4/super.c (ffffffff815cb2fb)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff815ea3e5)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff8160ead1)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff81614086)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff8165a0cf)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165b702)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff842afd28)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff83ed63f6)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81702daa)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8170beda)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff817120e9)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In crypto/drbg.c (ffffffff8171d34c)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff817266e6)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81727e5b)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81728cd3)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In lib/crc-t10dif.c (ffffffff842b0473)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
```
```
In lib/crc64-rocksoft.c (ffffffff842b04c3)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
```
```
In lib/digsig.c (ffffffff842b04f8)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In drivers/md/dm-ima.c (ffffffff81d0aa48)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe364)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81094a24)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/crypto/sha512_ssse3_glue.c (0)
Location: include/crypto/hash.h:775
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:775
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff81534979)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/verity/hash_algs.c (ffffffff8153c201)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ext4/super.c (ffffffff816039f8)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff816221d5)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff81646961)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff8164c0e5)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff81692736)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81694022)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83af28a8)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:775
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff836fb57a)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8173cd3a)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff817460f5)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
  - crypto/shash.c:crypto_clone_shash
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff8174cdb9)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:775
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:775
Inline: True
```
```
In crypto/sha3_generic.c (0)
Location: include/crypto/hash.h:775
Inline: True
```
```
In crypto/drbg.c (ffffffff81758bdc)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/jitterentropy-kcapi.c (ffffffff836fd406)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81762a60)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81764345)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81765017)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (0)
Location: include/crypto/hash.h:775
Inline: True
```
```
In lib/crc-t10dif.c (ffffffff83af3023)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
```
```
In lib/crc64-rocksoft.c (ffffffff83af3073)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
```
```
In lib/digsig.c (ffffffff83af30a8)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5e6c7)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
```
```
In drivers/md/dm-ima.c (ffffffff81d73b88)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f1c4)
Location: include/crypto/hash.h:775
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bf04)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
```
```
In arch/x86/crypto/sha512_ssse3_glue.c (0)
Location: include/crypto/hash.h:707
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:707
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff81569939)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/verity/hash_algs.c (ffffffff815714e1)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In fs/ext4/super.c (ffffffff8163be59)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff8165a715)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_init_common
```
```
In fs/ecryptfs/crypto.c (ffffffff8167fe21)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff81685614)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff816ced06)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d0652)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_exit
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff83d4e5d8)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:707
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8392eb7a)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
  - security/integrity/ima/ima_crypto.c:ima_init_crypto
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8177dbda)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/ahash.c (ffffffff81786c6a)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_exit_ahash_using_shash
```
```
In crypto/shash.c (ffffffff81788735)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
  - crypto/shash.c:crypto_clone_shash
```
```
In crypto/hmac.c (ffffffff8178e54a)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:707
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:707
Inline: True
```
```
In crypto/sha3_generic.c (0)
Location: include/crypto/hash.h:707
Inline: True
```
```
In crypto/drbg.c (ffffffff8179aadc)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/jitterentropy-kcapi.c (ffffffff83930a16)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff817a4550)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff817a5f65)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff817a6c37)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (0)
Location: include/crypto/hash.h:707
Inline: True
```
```
In lib/crc-t10dif.c (ffffffff83d4ed53)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
  - lib/crc-t10dif.c:crc_t10dif_rehash
```
```
In lib/crc64-rocksoft.c (ffffffff83d4eda3)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft_mod_fini
  - lib/crc64-rocksoft.c:crc64_rocksoft_rehash
```
```
In lib/digsig.c (ffffffff83d4edd8)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb2035)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
```
```
In drivers/md/dm-ima.c (ffffffff81e2ac98)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee2f4)
Location: include/crypto/hash.h:707
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In fs/crypto/hkdf.c (ffff80001040c52c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keysetup.c (ffff80001040e880)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/ext4/super.c (ffff8000104be870)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffff8000104d75b0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffff8000104f7594)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffff8000104fab50)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffff800010538750)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffff8000114692d8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffff8000114b8a08)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105b0248)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffff8000105b5cc0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffff8000105c1864)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffff8000105c5f34)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/drbg.c (ffff8000105d084c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffff8000105d752c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffff8000105d8c70)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffff8000105d9518)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffff8000114b8e0c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffff8000114b8e2c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In net/ipv6/seg6_hmac.c (ffff800010d51b70)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In fs/crypto/hkdf.c (c05d9650)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keysetup.c (c05db39c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/ext4/super.c (c0682214)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (c06996b8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (c06b4e90)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (c06b82cc)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (c06ef11c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (c1541e24)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (c15bed20)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (c075f974)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (c0764db0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (c076ef38)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (c0772c30)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/drbg.c (c077e1f0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (c0784bdc)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (c07861bc)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (c0786dc0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/crc-t10dif.c (c15bf110)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (c15bf134)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In net/ipv6/seg6_hmac.c (c0e526f0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In fs/crypto/hkdf.c (c000000000519590)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keysetup.c (c00000000051bb10)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/ext4/super.c (c0000000005f4a7c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (c00000000061222c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (c000000000638b94)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (c00000000063d428)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (c0000000006872a4)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (c0000000013973dc)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (c0000000013cbca4)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (c00000000072fce0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (c000000000739880)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (c000000000749cd0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (c00000000074f964)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/drbg.c (c00000000075cc28)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (c00000000076668c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (c000000000768548)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (c000000000769588)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (c0000000013cc3b0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (c0000000013cc3e8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In net/ipv6/seg6_hmac.c (c000000000e89ee8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In fs/crypto/hkdf.c (ffffffe0002b5de8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keysetup.c (ffffffe0002b7642)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/ext4/super.c (ffffffe00033a004)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffe00034d3f8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffe000366028)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffe0003692da)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffe0003976f0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffe000024532)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe0000a0ba0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7ef8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffe0003fcae2)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffe0004064a2)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffe000409fc6)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/drbg.c (ffffffe00041549c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffe00041b406)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffe00041c7ee)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffe00041d2c8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/crc-t10dif.c (ffffffe0000a1010)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffe0000a1034)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In net/ipv6/seg6_hmac.c (ffffffe000889d14)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff81344119)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keysetup.c (ffffffff81345b66)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/ext4/super.c (ffffffff813dd68e)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff813f2b78)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff8140e5b1)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff81411958)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff814464be)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff828d84c1)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82af2c94)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814b0460)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b5592)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814beb3a)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff814c281f)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/drbg.c (ffffffff814cc39c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814d385f)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814d4c90)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d5598)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff82af2f4d)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff82af2f60)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In arch/x86/power/hibernate.c (ffffffff818ab0ff)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25095)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff81334df9)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keysetup.c (ffffffff81336846)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/ext4/super.c (ffffffff813ce10e)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff813e35f8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff813ff031)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff814023d8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff81436f0e)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff828d0bdd)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82ac30bc)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814a0e80)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a5fb2)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814af55a)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff814b323f)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/drbg.c (ffffffff814bcdbc)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814c427f)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814c56b0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c5fb8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff82ac3375)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff82ac3388)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In arch/x86/power/hibernate.c (ffffffff818650ff)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e1e55)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff81341be9)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keysetup.c (ffffffff81343636)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/ext4/super.c (ffffffff813dab2e)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff813efef8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff8140b931)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff8140ecd8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff8144255e)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff828eb241)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82b0dd5c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814ac4f0)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b1622)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814babca)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff814be8af)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/drbg.c (ffffffff814c842c)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814cf8ef)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814d0d20)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d1628)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff82b0e015)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/libcrc32c.c (ffffffff82b0e028)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/libcrc32c.c:libcrc32c_mod_fini
```
```
In lib/digsig.c (ffffffff82b0e03e)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In arch/x86/power/hibernate.c (ffffffff818fc0ff)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a8fb15)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In fs/crypto/hkdf.c (ffffffff81354ee9)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_destroy_hkdf
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/crypto/keysetup.c (ffffffff81356916)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:derive_essiv_salt
```
```
In fs/ext4/super.c (ffffffff813efdfe)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
```
In fs/jbd2/journal.c (ffffffff814058fd)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_destroy
```
```
In fs/ecryptfs/crypto.c (ffffffff814215d1)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_crypt_stat
```
```
In fs/ecryptfs/keystore.c (ffffffff81424948)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff8145988e)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff828f0657)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/trusted.c:init_trusted
  - security/keys/trusted.c:trusted_shash_release
  - security/keys/trusted.c:trusted_shash_release
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff82b028ac)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:cleanup_encrypted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814c4f40)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814ca0a2)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814d367a)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_exit_shash_ops_async
```
```
In crypto/hmac.c (ffffffff814d737f)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/sha256_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/drbg.c (ffffffff814e0efc)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814e83bf)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814e97d0)
Location: include/crypto/hash.h:698
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814ea0d8)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/crc-t10dif.c (ffffffff82b02b65)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_mod_fini
```
```
In lib/digsig.c (ffffffff82b02b78)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - lib/digsig.c:digsig_cleanup
```
```
In arch/x86/power/hibernate.c (ffffffff8191d0ff)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9c8f5)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
```
</details>
</li>
</ul>

## Differences
