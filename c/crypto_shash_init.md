# Function: <code>crypto_shash_init</code>

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
In kernel/kexec_file.c (ffffffff8110f3f0)
Location: include/crypto/hash.h:824
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
```
In security/keys/trusted.c (ffffffff81336f4e)
Location: include/crypto/hash.h:824
Inline: True
```
```
In security/apparmor/crypto.c (ffffffff81394d9e)
Location: include/crypto/hash.h:824
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81397c18)
Location: include/crypto/hash.h:824
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8139b2c1)
Location: include/crypto/hash.h:824
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff813a338e)
Location: include/crypto/hash.h:824
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
  - crypto/shash.c:shash_compat_digest
```
```
In crypto/hmac.c (ffffffff813a4ce0)
Location: include/crypto/hash.h:824
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff813adb72)
Location: include/crypto/hash.h:824
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813aec93)
Location: include/crypto/hash.h:824
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813af5a9)
Location: include/crypto/hash.h:824
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff814197d8)
Location: include/crypto/hash.h:824
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff81116b30)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
```
In security/keys/trusted.c (ffffffff8136c55e)
Location: include/crypto/hash.h:862
Inline: True
```
```
In security/apparmor/crypto.c (ffffffff813d0917)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813d4863)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813d8119)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff813df55e)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff813e24e1)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff813ec193)
Location: include/crypto/hash.h:862
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff813f1a2b)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813f28d4)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff813f35f0)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffff81461547)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff8111e270)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
```
In security/keys/trusted.c (ffffffff81382d7e)
Location: include/crypto/hash.h:862
Inline: True
```
```
In security/apparmor/crypto.c (ffffffff813e801b)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813ec2b3)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813efdc9)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff813f7aee)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff813fb501)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814059d3)
Location: include/crypto/hash.h:862
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8140b27b)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8140c144)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8140ce60)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffff81480067)
Location: include/crypto/hash.h:862
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff8111feed)
Location: include/crypto/hash.h:868
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
```
In security/keys/dh.c (ffffffff813962f9)
Location: include/crypto/hash.h:868
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81397421)
Location: include/crypto/hash.h:868
Inline: True
```
```
In security/apparmor/crypto.c (ffffffff813f43f2)
Location: include/crypto/hash.h:868
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff813f867f)
Location: include/crypto/hash.h:868
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813fc3ee)
Location: include/crypto/hash.h:868
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814049f2)
Location: include/crypto/hash.h:868
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff81407fb0)
Location: include/crypto/hash.h:868
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff81413143)
Location: include/crypto/hash.h:868
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81418e3b)
Location: include/crypto/hash.h:868
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81419db3)
Location: include/crypto/hash.h:868
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8141a62f)
Location: include/crypto/hash.h:868
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81489302)
Location: include/crypto/hash.h:868
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In kernel/kexec_file.c (ffffffff8112b68d)
Location: include/crypto/hash.h:881
Inline: True
Inline callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
```
```
In security/keys/dh.c (ffffffff813bba31)
Location: include/crypto/hash.h:881
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff813bcc05)
Location: include/crypto/hash.h:881
Inline: True
```
```
In security/apparmor/crypto.c (ffffffff8141c5f2)
Location: include/crypto/hash.h:881
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff814209f5)
Location: include/crypto/hash.h:881
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814248c9)
Location: include/crypto/hash.h:881
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8142d2f6)
Location: include/crypto/hash.h:881
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff81430930)
Location: include/crypto/hash.h:881
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff8143d8e3)
Location: include/crypto/hash.h:881
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814449b0)
Location: include/crypto/hash.h:881
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814456ee)
Location: include/crypto/hash.h:881
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffff814c5447)
Location: include/crypto/hash.h:881
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In security/keys/dh.c (ffffffff813ec77d)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff813ed98e)
Location: include/crypto/hash.h:880
Inline: True
```
```
In security/apparmor/crypto.c (ffffffff8144e863)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81452e93)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81457005)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8145ff56)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff81463490)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff81470705)
Location: include/crypto/hash.h:880
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81477885)
Location: include/crypto/hash.h:880
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814785b3)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffff814f6344)
Location: include/crypto/hash.h:880
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
Location: include/crypto/hash.h:892
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In security/keys/dh.c (ffffffff81407367)
Location: include/crypto/hash.h:892
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81408996)
Location: include/crypto/hash.h:892
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff8146b829)
Location: include/crypto/hash.h:892
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828d00ec)
Location: include/crypto/hash.h:892
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814744b4)
Location: include/crypto/hash.h:892
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8147d9e6)
Location: include/crypto/hash.h:892
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814810fd)
Location: include/crypto/hash.h:892
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff8148d895)
Location: include/crypto/hash.h:892
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81495cca)
Location: include/crypto/hash.h:892
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814967e4)
Location: include/crypto/hash.h:892
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffff8150a744)
Location: include/crypto/hash.h:892
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
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In security/keys/dh.c (ffffffff81434543)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81436187)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81498811)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828e9e91)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a21e6)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814abc94)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814af2fd)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814bb215)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814c3813)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c404a)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8153925a)
Location: include/crypto/hash.h:896
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
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff8134b960)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff8144e29e)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff8144ff27)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff814b2741)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828f2b28)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814bceb6)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814c6974)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814c9f8d)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814d3ea5)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814dc63a)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814dcf2a)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8155a07a)
Location: include/crypto/hash.h:896
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
Location: include/crypto/hash.h:928
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813912b0)
Location: include/crypto/hash.h:928
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff8149fe38)
Location: include/crypto/hash.h:928
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a19f7)
Location: include/crypto/hash.h:928
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81511981)
Location: include/crypto/hash.h:928
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81516db1)
Location: include/crypto/hash.h:928
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8151d7d2)
Location: include/crypto/hash.h:928
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81525c44)
Location: include/crypto/hash.h:928
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff81529555)
Location: include/crypto/hash.h:928
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff81533c05)
Location: include/crypto/hash.h:928
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8153bf43)
Location: include/crypto/hash.h:928
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8153cd00)
Location: include/crypto/hash.h:928
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815e39af)
Location: include/crypto/hash.h:928
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
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813a2710)
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff814bd848)
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814bf3b7)
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff8152e7b1)
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81533f71)
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8153a643)
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81542b74)
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff81546505)
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff81550b55)
Location: include/crypto/hash.h:936
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81558be3)
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81559860)
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81607e3f)
Location: include/crypto/hash.h:936
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
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813a9893)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff814c36b8)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c5617)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81534aa1)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8153c5a1)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81542d03)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8154b215)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff8154ebc5)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff81559325)
Location: include/crypto/hash.h:940
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81561513)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81562170)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815eab4f)
Location: include/crypto/hash.h:940
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
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813f90d3)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff8151c088)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_ctr
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151e037)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81593020)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8159b281)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff815a340d)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff815ab9f5)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff815af515)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff815ba5a5)
Location: include/crypto/hash.h:940
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff815c2957)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815c3580)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8165704f)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81a0685d)
Location: include/crypto/hash.h:940
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
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff8146bec3)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b155f)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81634ed2)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8164013a)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81649c69)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff816532f5)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff81657c6a)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff81663af5)
Location: include/crypto/hash.h:940
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8166cea3)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8166db5a)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff8166e0e2)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff8176e88d)
Location: include/crypto/hash.h:940
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81b6e57a)
Location: include/crypto/hash.h:940
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
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff814fd1f3)
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165c05f)
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff816ebaf2)
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff816f7f9a)
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81702ca9)
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8170d015)
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:crypto_shash_digest
```
```
In crypto/hmac.c (ffffffff81711ed9)
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff8171de05)
Location: include/crypto/hash.h:942
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81727e9f)
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81728c4a)
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff817292d2)
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff8189e17d)
Location: include/crypto/hash.h:942
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81d0aaf4)
Location: include/crypto/hash.h:942
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
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81534756)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/verity/hash_algs.c (ffffffff8153c340)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8169497f)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81725f22)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff8173220a)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8173cc39)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81746973)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
```
```
In crypto/hmac.c (ffffffff8174caa9)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff81759705)
Location: include/crypto/hash.h:994
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (ffffffff836fd3d1)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_init
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/jitterentropy-kcapi.c:jent_hash_time
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81762a86)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff817642d7)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81764f81)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff81765632)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff818e073d)
Location: include/crypto/hash.h:994
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81d73c34)
Location: include/crypto/hash.h:994
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
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81569716)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/verity/hash_algs.c (ffffffff81571620)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d0faf)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff81767112)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81772aaa)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8177dad9)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/ahash.c (ffffffff81787a88)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init
  - crypto/ahash.c:shash_ahash_digest
```
```
In crypto/hmac.c (ffffffff8178eb33)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff8179b605)
Location: include/crypto/hash.h:909
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (ffffffff839309d8)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_init
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/jitterentropy-kcapi.c:jent_hash_time
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff817a4576)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff817a5ef7)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff817a6ba1)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff817a7232)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff8192727d)
Location: include/crypto/hash.h:909
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/md/dm-ima.c (ffffffff81e2ad44)
Location: include/crypto/hash.h:909
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
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffff800010538428)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted.c (ffff80001053a91c)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffff8000105aa134)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffff80001146cf84)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffff8000105b5bac)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffff8000105c1dc4)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffff8000105c5c1c)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffff8000105d09ec)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffff8000105d8bf4)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffff8000105d9490)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffff800010666860)
Location: include/crypto/hash.h:896
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
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (c06eedac)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted.c (c06f1128)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (c0759e40)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (c1545c8c)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (c0764cac)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (c076f3c0)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (c07729b8)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (c077e224)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hash
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (c078614c)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (c0786cc4)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (c080f4c8)
Location: include/crypto/hash.h:896
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
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
```
In fs/crypto/hkdf.c (c00000000051939c)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (c000000000687650)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (c00000000068a1bc)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (c000000000727874)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (c00000000139bff0)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (c0000000007396cc)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (c00000000074a3c4)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (c00000000074f52c)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (c00000000075ccac)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hash
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (c0000000007684a0)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (c0000000007694c8)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (c00000000081c410)
Location: include/crypto/hash.h:896
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
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffe00039715e)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
```
```
In security/keys/trusted.c (ffffffe00039896e)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffe0003f304a)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffe000027718)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffe0003fc9fe)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffe000406930)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffe000409d46)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffe00041569c)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_hash
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffe00041c84c)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffe00041cfca)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffe000492968)
Location: include/crypto/hash.h:896
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
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81343f40)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff8144687e)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81448507)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff814aad21)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828db9dc)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b5496)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814bef54)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814c256d)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814cc485)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814d4c1a)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d550a)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8155265a)
Location: include/crypto/hash.h:896
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
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81334c20)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff814372ce)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81438f57)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff8149b741)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828d40f8)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a5eb6)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814af974)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814b2f8d)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814bcea5)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814c563a)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c5f2a)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8154293a)
Location: include/crypto/hash.h:896
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
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81341a10)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff8144291e)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff814445a7)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff814a6dc1)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828ee750)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b1526)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814bafe4)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814be5fd)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814c8515)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814d0caa)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d159a)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8154e39a)
Location: include/crypto/hash.h:896
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
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81354d10)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In security/keys/dh.c (ffffffff81459c4e)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff8145b8d7)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
```
```
In security/apparmor/crypto.c (ffffffff814bf6b1)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff828f3b72)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814c9fa6)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814d3a94)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:shash_async_init
  - crypto/shash.c:shash_digest_unaligned
```
```
In crypto/hmac.c (ffffffff814d70cd)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_setkey
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814e0fe5)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814e975a)
Location: include/crypto/hash.h:896
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814ea04a)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815681ea)
Location: include/crypto/hash.h:896
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
</details>
</li>
</ul>

## Differences
