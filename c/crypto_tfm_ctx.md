# Function: <code>crypto_tfm_ctx</code>

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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81076636)
Location: include/linux/crypto.h:676
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:676
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:676
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:676
Inline: True
```
```
In crypto/chainiv.c (ffffffff813a219a)
Location: include/linux/crypto.h:676
Inline: True
Inline callers:
  - crypto/chainiv.c:async_chainiv_givencrypt_tail
  - crypto/chainiv.c:async_chainiv_givencrypt
```
```
In crypto/eseqiv.c (0)
Location: include/linux/crypto.h:676
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:676
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/linux/crypto.h:676
Inline: True
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:676
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:676
Inline: True
```
```
In crypto/aes_generic.c (ffffffff813a9b8d)
Location: include/linux/crypto.h:676
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:676
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:676
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81077c26)
Location: include/linux/crypto.h:651
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/xts.c (ffffffff813e84d9)
Location: include/linux/crypto.h:651
Inline: True
Inline callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/aes_generic.c (ffffffff813e952d)
Location: include/linux/crypto.h:651
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:651
Inline: True
```
```
In crypto/drbg.c (ffffffff813ee30f)
Location: include/linux/crypto.h:651
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:651
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107ba16)
Location: include/linux/crypto.h:654
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/aes_generic.c (ffffffff81402b5d)
Location: include/linux/crypto.h:654
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/drbg.c (ffffffff81407b4f)
Location: include/linux/crypto.h:654
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:654
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107a1c6)
Location: include/linux/crypto.h:654
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/aes_generic.c (ffffffff8140ff1d)
Location: include/linux/crypto.h:654
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:654
Inline: True
```
```
In crypto/drbg.c (ffffffff81415289)
Location: include/linux/crypto.h:654
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:654
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810808b6)
Location: include/linux/crypto.h:702
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/aes_generic.c (ffffffff8143a8d8)
Location: include/linux/crypto.h:702
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/drbg.c (ffffffff8143fa59)
Location: include/linux/crypto.h:702
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:702
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81083b35)
Location: include/linux/crypto.h:715
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/blkcipher.c (ffffffff8145c204)
Location: include/linux/crypto.h:715
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/hmac.c (ffffffff81463735)
Location: include/linux/crypto.h:715
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/aes_generic.c (ffffffff8146d325)
Location: include/linux/crypto.h:715
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff8146efc5)
Location: include/linux/crypto.h:715
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/drbg.c (ffffffff8147289d)
Location: include/linux/crypto.h:715
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:715
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:715
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108a805)
Location: include/linux/crypto.h:886
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/blkcipher.c (ffffffff81479b04)
Location: include/linux/crypto.h:886
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/hmac.c (ffffffff814813b5)
Location: include/linux/crypto.h:886
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/aes_generic.c (ffffffff8148acd5)
Location: include/linux/crypto.h:886
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff8148c975)
Location: include/linux/crypto.h:886
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/drbg.c (ffffffff8148fced)
Location: include/linux/crypto.h:886
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:886
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:886
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e605)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814a7a84)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/hmac.c (ffffffff814af585)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/aes_generic.c (ffffffff814b83b5)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff814ba065)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/drbg.c (ffffffff814be59d)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108f265)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814c26e4)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/hmac.c (ffffffff814ca215)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/aes_generic.c (ffffffff814d2be5)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff814d2e35)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/drbg.c (ffffffff814d73ed)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/geniv.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/hmac.c (ffffffff81529685)
Location: include/linux/crypto.h:702
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/aes_generic.c (ffffffff81531d45)
Location: include/linux/crypto.h:702
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff81531ee5)
Location: include/linux/crypto.h:702
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/drbg.c (ffffffff81534a1a)
Location: include/linux/crypto.h:702
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:702
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:702
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/geniv.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/hmac.c (ffffffff81546635)
Location: include/linux/crypto.h:738
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/aes_generic.c (ffffffff8154ec95)
Location: include/linux/crypto.h:738
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff8154ee35)
Location: include/linux/crypto.h:738
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/drbg.c (ffffffff8155196a)
Location: include/linux/crypto.h:738
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:738
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:738
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/geniv.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/hmac.c (ffffffff8154ecf5)
Location: include/linux/crypto.h:734
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/aes_generic.c (ffffffff81557505)
Location: include/linux/crypto.h:734
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff815576a5)
Location: include/linux/crypto.h:734
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/drbg.c (ffffffff81559f89)
Location: include/linux/crypto.h:734
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:734
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:734
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/geniv.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/hmac.c (ffffffff815af645)
Location: include/linux/crypto.h:708
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/aes_generic.c (ffffffff815b87b5)
Location: include/linux/crypto.h:708
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff815b8955)
Location: include/linux/crypto.h:708
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/drbg.c (ffffffff815bb209)
Location: include/linux/crypto.h:708
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:708
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:708
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/geniv.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/hmac.c (ffffffff81657d95)
Location: include/linux/crypto.h:717
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/aes_generic.c (ffffffff81661b05)
Location: include/linux/crypto.h:717
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff81661d65)
Location: include/linux/crypto.h:717
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/drbg.c (ffffffff81664bfd)
Location: include/linux/crypto.h:717
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:717
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:717
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/geniv.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/shash.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/dh.c (ffffffff8170da25)
Location: include/crypto/algapi.h:201
Inline: True
Inline callers:
  - crypto/dh.c:dh_exit_tfm
  - crypto/dh.c:dh_set_secret
```
```
In crypto/rsa.c (ffffffff8170e9a5)
Location: include/crypto/algapi.h:201
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/hmac.c (ffffffff817120ce)
Location: include/crypto/algapi.h:201
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/aes_generic.c (ffffffff8171b9b5)
Location: include/crypto/algapi.h:201
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff8171bc55)
Location: include/crypto/algapi.h:201
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/drbg.c (ffffffff8171ef7d)
Location: include/crypto/algapi.h:201
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/crypto/algapi.h:201
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:201
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/geniv.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/shash.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/akcipher.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/sig.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/dh.c (ffffffff81748295)
Location: include/crypto/algapi.h:184
Inline: True
Inline callers:
  - crypto/dh.c:dh_exit_tfm
  - crypto/dh.c:dh_set_secret
```
```
In crypto/rsa.c (ffffffff81749305)
Location: include/crypto/algapi.h:184
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/hmac.c (ffffffff8174cd9e)
Location: include/crypto/algapi.h:184
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_clone_tfm
  - crypto/hmac.c:hmac_clone_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/aes_generic.c (ffffffff81757145)
Location: include/crypto/algapi.h:184
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff817576f5)
Location: include/crypto/algapi.h:184
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/drbg.c (ffffffff8175a88d)
Location: include/crypto/algapi.h:184
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:184
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/geniv.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/lskcipher.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/akcipher.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/sig.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/dh.c (ffffffff8178a105)
Location: include/crypto/algapi.h:184
Inline: True
Inline callers:
  - crypto/dh.c:dh_exit_tfm
  - crypto/dh.c:dh_set_secret
```
```
In crypto/rsa.c (ffffffff8178b1a5)
Location: include/crypto/algapi.h:184
Inline: True
Inline callers:
  - crypto/rsa.c:rsa_exit_tfm
  - crypto/rsa.c:rsa_set_priv_key
  - crypto/rsa.c:rsa_set_pub_key
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/hmac.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/ecb.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/aes_generic.c (ffffffff81799105)
Location: include/crypto/algapi.h:184
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff817995f5)
Location: include/crypto/algapi.h:184
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/drbg.c (ffffffff8179c78d)
Location: include/crypto/algapi.h:184
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/crypto/algapi.h:184
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/crypto/algapi.h:184
Inline: True
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/blkcipher.c (ffff8000105bcd78)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/hmac.c (ffff8000105c5f00)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/aes_generic.c (ffff8000105cf0b4)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffff8000105cf390)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/drbg.c (ffff8000105d1944)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/blkcipher.c (c076ad20)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/hmac.c (c0772c08)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/aes_generic.c (c077cf08)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (c077d174)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/drbg.c (c0780854)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/blkcipher.c (c000000000743e2c)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/hmac.c (c00000000074f92c)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/aes_generic.c (c00000000075af10)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (c00000000075b290)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/drbg.c (c0000000007601c0)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
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
In crypto/aead.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/blkcipher.c (ffffffe0004024ca)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/hmac.c (ffffffe000409f9c)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/aes_generic.c (ffffffe0004140d4)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffe000414308)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/drbg.c (ffffffe000416646)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e225)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814bacc4)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/hmac.c (ffffffff814c27f5)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/aes_generic.c (ffffffff814cb1c5)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff814cb415)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/drbg.c (ffffffff814cf9cd)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107cd35)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814ab6e4)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/hmac.c (ffffffff814b3215)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/aes_generic.c (ffffffff814bbbe5)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff814bbe35)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/drbg.c (ffffffff814c03ed)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e1d5)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814b6d54)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/hmac.c (ffffffff814be885)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/aes_generic.c (ffffffff814c7255)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff814c74a5)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/drbg.c (ffffffff814cba5d)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810905b5)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_digest
```
```
In crypto/aead.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/blkcipher.c (ffffffff814cf7e4)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/blkcipher.c:crypto_init_blkcipher_ops
```
```
In crypto/skcipher.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/seqiv.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/shash.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/scompress.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/hmac.c (ffffffff814d7355)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_exit_tfm
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/ecb.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/cts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/xts.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/aes_generic.c (ffffffff814dfd25)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/aes_generic.c:crypto_aes_set_key
```
```
In crypto/deflate.c (ffffffff814dff75)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_decompress
  - crypto/deflate.c:deflate_compress
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_init
```
```
In crypto/crc32c_generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/lzo-rle.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/drbg.c (ffffffff814e452d)
Location: include/linux/crypto.h:883
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_random
  - crypto/drbg.c:drbg_kcapi_cleanup
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
```
In crypto/ghash-generic.c (0)
Location: include/linux/crypto.h:883
Inline: True
```
</details>
</li>
</ul>

## Differences
