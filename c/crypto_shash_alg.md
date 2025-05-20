# Function: <code>crypto_shash_alg</code>

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
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:685
Inline: True
```
```
In security/keys/trusted.c (ffffffff81336f4e)
Location: include/crypto/hash.h:685
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:685
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:685
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/crypto/hash.h:685
Inline: True
```
```
In crypto/shash.c (ffffffff813a33ad)
Location: include/crypto/hash.h:685
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_compat_digest
```
```
In crypto/hmac.c (ffffffff813a4b0c)
Location: include/crypto/hash.h:685
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
```
```
In crypto/sha256_generic.c (ffffffff813a7a87)
Location: include/crypto/hash.h:685
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In crypto/sha512_generic.c (ffffffff813a88e2)
Location: include/crypto/hash.h:685
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/crypto/hash.h:685
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813af247)
Location: include/crypto/hash.h:685
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/crypto/hash.h:685
Inline: True
```
```
In lib/digsig.c (0)
Location: include/crypto/hash.h:685
Inline: True
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
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In security/keys/trusted.c (ffffffff8136c55e)
Location: include/crypto/hash.h:723
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In crypto/shash.c (ffffffff813df57d)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff813e25b3)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff813e508e)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In crypto/sha512_generic.c (ffffffff813e5d90)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff813ec193)
Location: include/crypto/hash.h:723
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813f2e3a)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In lib/digsig.c (0)
Location: include/crypto/hash.h:723
Inline: True
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
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In security/keys/trusted.c (ffffffff81382d7e)
Location: include/crypto/hash.h:723
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In crypto/shash.c (ffffffff813f7b0d)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff813fb5d3)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff813fe0ae)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In crypto/sha512_generic.c (ffffffff813fedb0)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff814059d3)
Location: include/crypto/hash.h:723
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8140c6aa)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In lib/digsig.c (0)
Location: include/crypto/hash.h:723
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/crypto/hash.h:723
Inline: True
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
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:729
Inline: True
```
```
In security/keys/dh.c (ffffffff8139628b)
Location: include/crypto/hash.h:729
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81397421)
Location: include/crypto/hash.h:729
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:729
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:729
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/crypto/hash.h:729
Inline: True
```
```
In crypto/shash.c (ffffffff81403fdd)
Location: include/crypto/hash.h:729
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814080b0)
Location: include/crypto/hash.h:729
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff8140b3a2)
Location: include/crypto/hash.h:729
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In crypto/sha512_generic.c (ffffffff8140c0ca)
Location: include/crypto/hash.h:729
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff81413143)
Location: include/crypto/hash.h:729
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/crypto/hash.h:729
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81419e57)
Location: include/crypto/hash.h:729
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/crypto/hash.h:729
Inline: True
```
```
In lib/digsig.c (0)
Location: include/crypto/hash.h:729
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/crypto/hash.h:729
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
Location: include/crypto/hash.h:737
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/crypto/hash.h:737
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/crypto/hash.h:737
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:737
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:737
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/crypto/hash.h:737
Inline: True
```
```
In crypto/shash.c (ffffffff8142c8d5)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff81430a64)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff81433dc2)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In crypto/sha512_generic.c (ffffffff81434aea)
Location: include/crypto/hash.h:737
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (0)
Location: include/crypto/hash.h:737
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/crypto/hash.h:737
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/crypto/hash.h:737
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/crypto/hash.h:737
Inline: True
```
```
In lib/digsig.c (0)
Location: include/crypto/hash.h:737
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/crypto/hash.h:737
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
In kernel/kexec_file.c (ffffffff81139737)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In security/keys/dh.c (ffffffff813ec362)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff813ed99b)
Location: include/crypto/hash.h:736
Inline: True
```
```
In security/apparmor/crypto.c (ffffffff827178bb)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81452e8c)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8145700f)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8145f535)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff81463743)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff81466936)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In crypto/sha512_generic.c (ffffffff81467643)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff814731ed)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8147683e)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81477761)
Location: include/crypto/hash.h:736
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81478346)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffff814f634a)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a97c4)
Location: include/crypto/hash.h:736
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In kernel/kexec_file.c (ffffffff81145007)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In security/keys/dh.c (ffffffff81406f58)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff814089a3)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff828cf310)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828d00f8)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814747c1)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8147cf65)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814813c3)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff814845a6)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In crypto/sha512_generic.c (ffffffff814852b3)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff81490f6d)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814949de)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8149596c)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8149656d)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffff8150a74a)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e02c4)
Location: include/crypto/hash.h:748
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In kernel/kexec_file.c (ffffffff811503f9)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In security/keys/dh.c (ffffffff814340d1)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81436194)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff828e8d78)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828e9e96)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a24ca)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814ab255)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814af593)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff814b27d6)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_final
```
```
In crypto/sha512_generic.c (ffffffff814b3567)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff814be0fc)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814c23c7)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814c3702)
Location: include/crypto/hash.h:747
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c400c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81539260)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4ef22)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In kernel/kexec_file.c (ffffffff8115c089)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff8134b96a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffff8144de21)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff8144ff34)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff828f1864)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828f2b2d)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814bd19a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814c5f15)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814ca223)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff814cb875)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
```
In crypto/sha512_generic.c (ffffffff814cc2d7)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff814d6f4c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814db1f7)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814dc55a)
Location: include/crypto/hash.h:747
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814dceec)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8155a080)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a85bb2)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In kernel/kexec_file.c (ffffffff8116cfeb)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813912ba)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffff8149ff85)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a1a04)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff82d068e9)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81517c9f)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8151dab8)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8152551f)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff81529693)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff8152ad30)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In crypto/sha512_generic.c (ffffffff8152b71d)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff815364cc)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8153aae7)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8153bf50)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8153ccbc)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815e39b5)
Location: include/crypto/hash.h:760
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80b16)
Location: include/crypto/hash.h:760
Inline: True
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
In kernel/kexec_file.c (ffffffff8116966b)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813a271a)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffff814bd9a0)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814bf3c4)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff82ff3cb4)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81534daf)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8153a938)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8154244f)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff81546643)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff81547d00)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In crypto/sha512_generic.c (ffffffff815486ed)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff8155343c)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81557918)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81558bf0)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8155981c)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81607e45)
Location: include/crypto/hash.h:768
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90386)
Location: include/crypto/hash.h:768
Inline: True
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
In kernel/kexec_file.c (ffffffff8116a39d)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813a989d)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffff814c3810)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c5624)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff831fe7cf)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153d3df)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81542ffb)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8154aaef)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff8154ed03)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff815503c0)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In crypto/sha512_generic.c (ffffffff81550db9)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff8155bbbc)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81560218)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81561520)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8156212f)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815eab55)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7f5c9)
Location: include/crypto/hash.h:772
Inline: True
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
In kernel/kexec_file.c (ffffffff8118ff5c)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813f90dd)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffff8151c1e0)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_ctr
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151e044)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff832e5ae1)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159c25f)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff815a360d)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff815ab2cf)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff815af653)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff815b0d40)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In crypto/sha512_generic.c (ffffffff815b1d7f)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff815bceec)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff815c15c8)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff815c2968)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815c353f)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81657055)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81a06838)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4ae79)
Location: include/crypto/hash.h:772
Inline: True
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
In kernel/kexec_file.c (ffffffff811bf70d)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff8146becd)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffff815af446)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b156c)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff8349c8cc)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8164126f)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81649e74)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81652acf)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff816578e3)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff81659760)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In crypto/sha512_generic.c (ffffffff8165a8af)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff8166688d)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8166ba41)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8166ceb4)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8166db1f)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff8166e2c5)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_setkey
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff8176e893)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81b6e555)
Location: include/crypto/hash.h:772
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In net/ipv6/seg6_hmac.c (ffffffff81dea6e8)
Location: include/crypto/hash.h:772
Inline: True
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
In kernel/kexec_file.c (ffffffff81201a2d)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff814fd1fd)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffff81659c56)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165c06c)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff83ed3fc7)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f921b)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81702ee8)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8170c70f)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff81711aff)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff81713a80)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In crypto/sha512_generic.c (ffffffff81714b7b)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff81720c89)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81726671)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81727eb0)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81728c0f)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff817291e5)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_setkey
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff8189e183)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81d0aacf)
Location: include/crypto/hash.h:774
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbdf28)
Location: include/crypto/hash.h:774
Inline: True
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
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e0bb3)
Location: include/crypto/hash.h:826
Inline: True
```
```
In kernel/kexec_file.c (ffffffff81216dfd)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81534760)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/verity/hash_algs.c (ffffffff8153c49b)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_hash_block
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/keys/dh.c (ffffffff816924c5)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8169498c)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff836f9107)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8173336e)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8173cf88)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81746109)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/hmac.c (ffffffff8174c6bf)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff8174e880)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In crypto/sha512_generic.c (ffffffff8174fab1)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/sha3_generic.c (ffffffff8175031a)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/sha3_generic.c:crypto_sha3_final
  - crypto/sha3_generic.c:crypto_sha3_init
```
```
In crypto/drbg.c (ffffffff8175c539)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/jitterentropy-kcapi.c (ffffffff836fd3d7)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_init
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - crypto/jitterentropy-kcapi.c:jent_hash_time
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff817629ef)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff817642e8)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81764f3f)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff81765545)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_setkey
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff818e0743)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81d73c0f)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201ee89)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e9433)
Location: include/crypto/hash.h:752
Inline: True
```
```
In kernel/kexec_file.c (ffffffff8122ecde)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81569720)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In fs/verity/hash_algs.c (ffffffff815715c4)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
```
```
In security/keys/dh.c (ffffffff816cea95)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d0fbc)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff8392c517)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81773d8e)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8177dda8)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/ahash.c (ffffffff81787a8e)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init
  - crypto/ahash.c:shash_ahash_digest
```
```
In crypto/shash.c (ffffffff81788749)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/shash.c:crypto_clone_shash
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:crypto_shash_exit_tfm
  - crypto/shash.c:crypto_shash_import
  - crypto/shash.c:crypto_shash_export
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_default_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_default_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff8178e718)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff817904d0)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
```
```
In crypto/sha512_generic.c (ffffffff81791701)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/sha3_generic.c (ffffffff81791f6a)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/sha3_generic.c:crypto_sha3_final
  - crypto/sha3_generic.c:crypto_sha3_init
```
```
In crypto/drbg.c (ffffffff8179e439)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/jitterentropy-kcapi.c (ffffffff839309de)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_init
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/jitterentropy-kcapi.c:jent_hash_time
  - crypto/jitterentropy-kcapi.c:jent_hash_time
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff817a44df)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff817a5f08)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff817a6b5f)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff817a7145)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_setkey
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff81927283)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81e2ad1f)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
```
In net/ipv6/seg6_hmac.c (ffffffff820edfb7)
Location: include/crypto/hash.h:752
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In fs/crypto/hkdf.c (ffff80001040c3ec)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffff8000105386a0)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted.c (ffff80001053a92c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffff80001146baa8)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffff80001146cf8c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffff8000105b5ee4)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffff8000105c0f08)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffff8000105c5f14)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffff8000105c7834)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
```
In crypto/sha512_generic.c (ffff8000105c81b0)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In crypto/drbg.c (ffff8000105d1f58)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffff8000105d74b4)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffff8000105d8b5c)
Location: include/crypto/hash.h:747
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffff8000105d944c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffff80001066686c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffff800010d521b0)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In fs/crypto/hkdf.c (c05d9500)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (c06ef07c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted.c (c06f1138)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (c1544724)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (c1545c94)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (c0764ff4)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (c076e838)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (c0772c14)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (c07742b8)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
```
In crypto/sha512_generic.c (c07757c4)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In crypto/drbg.c (c077e23c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hash
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (c0784b60)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (c078615c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (c0786c7c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (c080f4d4)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (c0e528c8)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In kernel/kexec_file.c (c000000000234c20)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
```
In fs/crypto/hkdf.c (c0000000005193a8)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (c0000000006871b0)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (c00000000068a1cc)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (c00000000139a660)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (c00000000139bff8)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (c000000000739b34)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (c000000000749270)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (c00000000074f948)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (c00000000075142c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
```
In crypto/sha512_generic.c (c000000000751f60)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (c00000000075ccbc)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hash
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (c0000000007665f4)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (c0000000007683e8)
Location: include/crypto/hash.h:747
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (c000000000769484)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (c00000000081c41c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (c000000000e8a150)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In fs/crypto/hkdf.c (ffffffe0002b5cf2)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffe000397394)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted.c (ffffffe000398978)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffe000026a94)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffe000027728)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffe0003fccc0)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffe000405d0c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffe000409fae)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffe00040b7a6)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
```
In crypto/sha512_generic.c (ffffffe00040c21a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
```
```
In crypto/drbg.c (ffffffe0004156a6)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hash
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffe00041b38a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffe00041c736)
Location: include/crypto/hash.h:747
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffe00041cf7c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffe00049296e)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a1ca)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In kernel/kexec_file.c (ffffffff811546a9)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81343f4a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffff81446401)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81448514)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff828da718)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828db9e1)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b577a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814be4f5)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814c2803)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff814c3e55)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
```
In crypto/sha512_generic.c (ffffffff814c48b7)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff814cf52c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814d37d7)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814d4b3a)
Location: include/crypto/hash.h:747
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d54cc)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81552660)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25242)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In kernel/kexec_file.c (ffffffff811479c9)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81334c2a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffff81436e51)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81438f64)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff828d2e34)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828d40fd)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a619a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814aef15)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814b3223)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff814b4875)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
```
In crypto/sha512_generic.c (ffffffff814b52d7)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff814bff4c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814c41f7)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814c555a)
Location: include/crypto/hash.h:747
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c5eec)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81542940)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2002)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In kernel/kexec_file.c (ffffffff81152489)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81341a1a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffff814424a1)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff814445b4)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff828ed48c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828ee755)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b180a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814ba585)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814be893)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff814bfee5)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
```
In crypto/sha512_generic.c (ffffffff814c0947)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff814cb5bc)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814cf867)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814d0bca)
Location: include/crypto/hash.h:747
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d155c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8154e3a0)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a8fcc2)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In kernel/kexec_file.c (ffffffff8115f379)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81354d1a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
```
```
In security/keys/dh.c (ffffffff814597d1)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff8145b8e4)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff828f28ae)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/apparmor/crypto.c:init_profile_hash
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828f3b77)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814ca28a)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814d3035)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_init_tfm
  - crypto/shash.c:shash_async_import
  - crypto/shash.c:shash_async_export
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/hmac.c (ffffffff814d7363)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/sha256_generic.c (ffffffff814d89b5)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_final
```
```
In crypto/sha512_generic.c (ffffffff814d9417)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/drbg.c (ffffffff814e408c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814e8337)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814e967a)
Location: include/crypto/hash.h:747
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814ea00c)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815681f0)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9caa2)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
</details>
</li>
</ul>

## Differences
