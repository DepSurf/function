# Function: <code>crypto_shash_final</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813a3760)
Location: crypto/shash.c:134
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_finup_unaligned
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_compat_digest
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff813a3760-ffffffff813a381e: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813df8d0)
Location: crypto/shash.c:134
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff813df8d0-ffffffff813df991: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813f7e60)
Location: crypto/shash.c:134
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff813f7e60-ffffffff813f7f21: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81404320)
Location: crypto/shash.c:135
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81404320-ffffffff814043e8: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8142cc00)
Location: crypto/shash.c:143
Inline: False
Direct callers:
  - kernel/kexec_file.c:SyS_kexec_file_load
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8142cc00-ffffffff8142cccc: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8145f870)
Location: crypto/shash.c:143
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:__keyctl_dh_compute
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8145f870-ffffffff8145f93d: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8147d390)
Location: crypto/shash.c:157
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8147d390-ffffffff8147d3b7: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814ab670)
Location: crypto/shash.c:152
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814ab670-ffffffff814ab697: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814c6350)
Location: crypto/shash.c:152
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814c6350-ffffffff814c6377: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81525aa7)
Location: crypto/shash.c:151
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:kdf_ctr
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81525290-ffffffff815252b7: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815429d7)
Location: crypto/shash.c:151
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:kdf_ctr
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81542180-ffffffff815421a7: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154b077)
Location: crypto/shash.c:163
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:kdf_ctr
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8154a820-ffffffff8154a847: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab857)
Location: crypto/shash.c:163
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:kdf_ctr
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
**Symbols:**

```
ffffffff815ab000-ffffffff815ab027: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81653127)
Location: crypto/shash.c:163
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - lib/digsig.c:digsig_verify
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
**Symbols:**

```
ffffffff81652760-ffffffff81652797: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170ce07)
Location: crypto/shash.c:153
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:crypto_shash_finup
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - lib/digsig.c:digsig_verify
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
**Symbols:**

```
ffffffff8170c640-ffffffff8170c677: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81746470)
Location: crypto/shash.c:168
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/hmac.c:hmac_final
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - lib/digsig.c:digsig_verify
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
**Symbols:**

```
ffffffff81746470-ffffffff817464d0: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81788900)
Location: crypto/shash.c:76
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/ahash.c:crypto_ahash_final
  - crypto/ahash.c:shash_ahash_finup
  - crypto/hmac.c:hmac_final
  - crypto/jitterentropy-kcapi.c:jent_read_random_block
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
  - lib/digsig.c:digsig_verify
  - drivers/md/dm-ima.c:dm_ima_measure_on_table_load
```
**Symbols:**

```
ffffffff81788900-ffffffff81788936: crypto_shash_final (STB_GLOBAL)
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
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffff8000105c14c8)
Location: crypto/shash.c:152
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffff8000105c14c8-ffff8000105c152c: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c076ecdc)
Location: crypto/shash.c:152
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_field_array_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/drbg.c:drbg_kcapi_hash
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
c076ecdc-c076ed18: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c000000000749910)
Location: crypto/shash.c:152
Inline: False
Direct callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/drbg.c:drbg_kcapi_hash
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
c000000000749910-c000000000749974: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffe0004061c6)
Location: crypto/shash.c:152
Inline: False
Direct callers:
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/drbg.c:drbg_kcapi_hash
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffe0004061c6-ffffffe00040621c: crypto_shash_final (STB_GLOBAL)
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
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814be930)
Location: crypto/shash.c:152
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814be930-ffffffff814be957: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814af350)
Location: crypto/shash.c:152
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814af350-ffffffff814af377: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814ba9c0)
Location: crypto/shash.c:152
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814ba9c0-ffffffff814ba9e7: crypto_shash_final (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_shash_final(struct shash_desc *desc, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814d3470)
Location: crypto/shash.c:152
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate_tfm
  - security/integrity/ima/ima_crypto.c:calc_buffer_shash_tfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
  - security/integrity/evm/evm_crypto.c:hmac_add_misc
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_finup_unaligned
  - crypto/hmac.c:hmac_final
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814d3470-ffffffff814d3497: crypto_shash_final (STB_GLOBAL)
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
