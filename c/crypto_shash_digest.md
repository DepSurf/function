# Function: <code>crypto_shash_digest</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813a38d0)
Location: crypto/shash.c:175
Inline: False
Direct callers:
  - security/keys/trusted.c:key_seal
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - crypto/shash.c:shash_compat_digest
  - crypto/hmac.c:hmac_setkey
```
**Symbols:**

```
ffffffff813a38d0-ffffffff813a38f8: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813dfa50)
Location: crypto/shash.c:175
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:key_seal
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - crypto/hmac.c:hmac_setkey
```
**Symbols:**

```
ffffffff813dfa50-ffffffff813dfa78: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff813f7fe0)
Location: crypto/shash.c:175
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:key_seal
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - crypto/hmac.c:hmac_setkey
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff813f7fe0-ffffffff813f8008: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814044a0)
Location: crypto/shash.c:176
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:key_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff814044a0-ffffffff814044c8: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8142cd90)
Location: crypto/shash.c:184
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:key_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff8142cd90-ffffffff8142cdcd: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8145fa00)
Location: crypto/shash.c:184
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:key_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff8145fa00-ffffffff8145fa3d: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8147d480)
Location: crypto/shash.c:198
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:derive_essiv_salt
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:key_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff8147d480-ffffffff8147d4bd: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814ab780)
Location: crypto/shash.c:193
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:derive_essiv_salt
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:tpm_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff814ab780-ffffffff814ab7bd: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814c6460)
Location: crypto/shash.c:193
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:hkdf_extract
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:tpm_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff814c6460-ffffffff814c649d: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81525b00)
Location: crypto/shash.c:192
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:crypto_shash_tfm_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - arch/x86/power/hibernate.c:get_e820_md5
```
**Symbols:**

```
ffffffff81525b00-ffffffff81525b76: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81542a30)
Location: crypto/shash.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:crypto_shash_tfm_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - arch/x86/power/hibernate.c:get_e820_md5
```
**Symbols:**

```
ffffffff81542a30-ffffffff81542aa6: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8154b0d0)
Location: crypto/shash.c:204
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:crypto_shash_tfm_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
**Symbols:**

```
ffffffff8154b0d0-ffffffff8154b146: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff815ab8b0)
Location: crypto/shash.c:204
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:crypto_shash_tfm_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
**Symbols:**

```
ffffffff815ab8b0-ffffffff815ab926: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff81653190)
Location: crypto/shash.c:204
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:crypto_shash_tfm_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
**Symbols:**

```
ffffffff81653190-ffffffff81653211: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff8170ce90)
Location: crypto/shash.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:crypto_shash_tfm_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
**Symbols:**

```
ffffffff8170ce90-ffffffff8170cf11: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff817467f0)
Location: crypto/shash.c:227
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash
  - fs/verity/hash_algs.c:fsverity_hash_block
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - crypto/shash.c:shash_ahash_digest
  - crypto/shash.c:crypto_shash_tfm_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff817467f0-ffffffff8174687a: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff817889a0)
Location: crypto/shash.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_get_key_hash
  - fs/verity/hash_algs.c:fsverity_hash_block
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - crypto/ahash.c:shash_ahash_digest
  - crypto/shash.c:crypto_shash_tfm_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff817889a0-ffffffff817889f2: crypto_shash_digest (STB_GLOBAL)
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
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffff8000105c16b0)
Location: crypto/shash.c:193
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:hkdf_extract
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:tpm_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffff8000105c16b0-ffff8000105c174c: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c076edf8)
Location: crypto/shash.c:193
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:hkdf_extract
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:tpm_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
c076edf8-c076ee50: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (c000000000749b30)
Location: crypto/shash.c:193
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:hkdf_extract
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:tpm_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
c000000000749b30-c000000000749bb8: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffe000406356)
Location: crypto/shash.c:193
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:hkdf_extract
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:tpm_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffe000406356-ffffffe0004063d2: crypto_shash_digest (STB_GLOBAL)
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
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814bea40)
Location: crypto/shash.c:193
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:hkdf_extract
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:tpm_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff814bea40-ffffffff814bea7d: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814af460)
Location: crypto/shash.c:193
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:hkdf_extract
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:tpm_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff814af460-ffffffff814af49d: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814baad0)
Location: crypto/shash.c:193
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:hkdf_extract
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:tpm_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff814baad0-ffffffff814bab0d: crypto_shash_digest (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_shash_digest(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/shash.c (ffffffff814d3580)
Location: crypto/shash.c:193
Inline: False
Direct callers:
  - fs/crypto/hkdf.c:hkdf_extract
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - security/keys/trusted.c:tpm_seal
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - crypto/shash.c:shash_ahash_digest
  - crypto/hmac.c:hmac_setkey
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff814d3580-ffffffff814d35bd: crypto_shash_digest (STB_GLOBAL)
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
