# Function: <code>crypto_shash_get_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:709
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:747
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:747
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:753
Inline: True
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
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:761
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/crypto/hash.h:761
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/crypto/hash.h:761
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:761
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:761
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/crypto/hash.h:761
Inline: True
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:761
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:761
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/hash.h:761
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/crypto/hash.h:761
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/crypto/hash.h:761
Inline: True
```
```
In lib/digsig.c (0)
Location: include/crypto/hash.h:761
Inline: True
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
In kernel/kexec_file.c (ffffffff8113972d)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In security/keys/dh.c (ffffffff813ec77d)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff813ed991)
Location: include/crypto/hash.h:760
Inline: True
```
```
In security/apparmor/crypto.c (ffffffff8144e863)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81452e93)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81457005)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814600db)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814635fb)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff8147071c)
Location: include/crypto/hash.h:760
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81477888)
Location: include/crypto/hash.h:760
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814785b3)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffff814f6344)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff81144ffd)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In security/keys/dh.c (ffffffff81407367)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81408999)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff8146b829)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828d00ec)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814744b4)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8147db4a)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff8148127b)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff8148d8ac)
Location: include/crypto/hash.h:772
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81495ccd)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814967e4)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffff8150a744)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff811503ee)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In security/keys/dh.c (ffffffff81434543)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff8143618a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81498811)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828e9e91)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a21e6)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814abde6)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814af46a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814bb22c)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814c3816)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c404a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8153925a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff8115c07e)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff8134b960)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff8144e29e)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff8144ff2a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff814b2741)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828f2b28)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814bceb6)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814c6ac6)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814ca0fa)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814d3ebc)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814dc63d)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814dcf2a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8155a07a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff8116cfe0)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813912b0)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff8149fe38)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a19fa)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81511981)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516db1)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8151d7d2)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81525d76)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff81529259)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff81533c1c)
Location: include/crypto/hash.h:784
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8153bf46)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8153cd00)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815e39af)
Location: include/crypto/hash.h:784
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff81169660)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813a2710)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff814bd848)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814bf3ba)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff8152e7b1)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81533f71)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8153a643)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81542cab)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff81546229)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff81550b6c)
Location: include/crypto/hash.h:792
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81558be6)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81559860)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81607e3f)
Location: include/crypto/hash.h:792
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff8116a393)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813a9893)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff814c36b8)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c561a)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81534aa1)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153c5a1)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81542d03)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8154b34b)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff8154e8b9)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff8155933c)
Location: include/crypto/hash.h:796
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81561516)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81562170)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815eab4f)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff8118ff52)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813f90d3)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff8151c088)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151e03a)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81593020)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159b281)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff815a340d)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff815abb2b)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff815af209)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff815ba5bc)
Location: include/crypto/hash.h:796
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff815c295e)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815c3580)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8165704f)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81a06864)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
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
In kernel/kexec_file.c (ffffffff811bf702)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff8146bec3)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b1562)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81634ed2)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8164013a)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81649c69)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8165345b)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff81657925)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff81663b0c)
Location: include/crypto/hash.h:796
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8166ceaa)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8166db5a)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff8166e0e2)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff8176e88d)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81b6e581)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
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
In kernel/kexec_file.c (ffffffff81201a22)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff814fd1f3)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165c062)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff816ebaf2)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f7f9a)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81702ca9)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8170d19b)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff81711b65)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff8171de1c)
Location: include/crypto/hash.h:798
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81727ea6)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81728c4a)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff817292d2)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff8189e17d)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81d0aafb)
Location: include/crypto/hash.h:798
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
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
In kernel/kexec_file.c (ffffffff81216df2)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81534756)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/verity/hash_algs.c (ffffffff8153c495)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_block
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff81694982)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81725f22)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8173220a)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8173cc39)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81746b5b)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff8174c725)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff8175971c)
Location: include/crypto/hash.h:850
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (ffffffff836fd3d1)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_init
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/jitterentropy-kcapi.c:jent_hash_time
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81762a86)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff817642de)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81764f81)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff81765632)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff818e073d)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81d73c3b)
Location: include/crypto/hash.h:850
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
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
In kernel/kexec_file.c (ffffffff8122ecd3)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81569716)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/verity/hash_algs.c (ffffffff81571627)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d0fb2)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81767112)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81772aaa)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8177dad9)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/ahash.c (ffffffff817876c4)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/ahash.c:shash_ahash_digest
```
```
In crypto/shash.c (ffffffff8178820c)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_import
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff8178eb3a)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff8179b61c)
Location: include/crypto/hash.h:776
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (ffffffff839309d8)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_init
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/jitterentropy-kcapi.c:jent_hash_time
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff817a4576)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff817a5efe)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff817a6ba1)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff817a7232)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff8192727d)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81e2ad4b)
Location: include/crypto/hash.h:776
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
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
In fs/crypto/hkdf.c (ffff80001040c3e0)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffff800010538428)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted.c (ffff80001053a920)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffff8000105aa134)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffff80001146cf84)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffff8000105b5bac)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffff8000105c1fa4)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffff8000105c5d88)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffff8000105d09f0)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffff8000105d8bf8)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffff8000105d9490)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffff800010666860)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In fs/crypto/hkdf.c (c05d94f4)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (c06eedac)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted.c (c06f112c)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (c0759e40)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (c1545c8c)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (c0764cac)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (c076f528)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (c0772b04)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (c077e230)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hash
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (c0786150)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (c0786cc4)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (c080f4c8)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (c000000000234c14)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
```
In fs/crypto/hkdf.c (c00000000051939c)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (c000000000687650)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (c00000000068a1c0)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (c000000000727874)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (c00000000139bff0)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (c0000000007396cc)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (c00000000074a604)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (c00000000074f700)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (c00000000075ccb0)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hash
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (c0000000007684a4)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (c0000000007694c8)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (c00000000081c410)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In fs/crypto/hkdf.c (ffffffe0002b5cec)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffe00039715e)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted.c (ffffffe000398970)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffe0003f3050)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffe000027720)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffe0003fc9fe)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffe000406ae2)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffe000409e88)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffe0004156a0)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hash
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffe00041c850)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffe00041cfca)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffe000492968)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff8115469e)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81343f40)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff8144687e)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff8144850a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff814aad21)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828db9dc)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b5496)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814bf0a6)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814c26da)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814cc49c)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814d4c1d)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d550a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8155265a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff811479be)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81334c20)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff814372ce)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81438f5a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff8149b741)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828d40f8)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a5eb6)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814afac6)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814b30fa)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814bcebc)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814c563d)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c5f2a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8154293a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff8115247e)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81341a10)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff8144291e)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff814445aa)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff814a6dc1)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828ee750)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b1526)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814bb136)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814be76a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814c852c)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814d0cad)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d159a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8154e39a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff8115f36e)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81354d10)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff81459c4e)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff8145b8da)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff814bf6b1)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828f3b72)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814c9fa6)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814d3c06)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814d723a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814e0ffc)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814e975d)
Location: include/crypto/hash.h:771
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814ea04a)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815681ea)
Location: include/crypto/hash.h:771
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
</details>
</li>
</ul>

## Differences
