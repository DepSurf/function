# Function: <code>shash_desc_ctx</code>

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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81076656)
Location: include/crypto/hash.h:744
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:744
Inline: True
```
```
In crypto/hmac.c (ffffffff813a4afc)
Location: include/crypto/hash.h:744
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_export
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
```
```
In crypto/md5.c (ffffffff813a5482)
Location: include/crypto/hash.h:744
Inline: True
Inline callers:
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff813a5860)
Location: include/crypto/hash.h:744
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff813a79c0)
Location: include/crypto/hash.h:744
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff813a8800)
Location: include/crypto/hash.h:744
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:744
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:744
Inline: True
```
```
In drivers/staging/skein/skein_generic.c (ffffffff816e3256)
Location: include/crypto/hash.h:744
Inline: True
Inline callers:
  - drivers/staging/skein/skein_generic.c:skein1024_final
  - drivers/staging/skein/skein_generic.c:skein1024_update
  - drivers/staging/skein/skein_generic.c:skein1024_init
  - drivers/staging/skein/skein_generic.c:skein512_final
  - drivers/staging/skein/skein_generic.c:skein512_update
  - drivers/staging/skein/skein_generic.c:skein512_init
  - drivers/staging/skein/skein_generic.c:skein256_final
  - drivers/staging/skein/skein_generic.c:skein256_update
  - drivers/staging/skein/skein_generic.c:skein256_init
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81077c46)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:782
Inline: True
```
```
In crypto/hmac.c (ffffffff813e25a8)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff813e2c62)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff813e31cf)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff813e51df)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:sha256_final
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff813e5ef6)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:782
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:782
Inline: True
```
```
In drivers/staging/skein/skein_generic.c (ffffffff817472d6)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - drivers/staging/skein/skein_generic.c:skein1024_final
  - drivers/staging/skein/skein_generic.c:skein1024_update
  - drivers/staging/skein/skein_generic.c:skein1024_init
  - drivers/staging/skein/skein_generic.c:skein512_final
  - drivers/staging/skein/skein_generic.c:skein512_update
  - drivers/staging/skein/skein_generic.c:skein512_init
  - drivers/staging/skein/skein_generic.c:skein256_final
  - drivers/staging/skein/skein_generic.c:skein256_update
  - drivers/staging/skein/skein_generic.c:skein256_init
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107ba36)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:782
Inline: True
```
```
In crypto/hmac.c (ffffffff813fb5c8)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff813fbc82)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff813fc1ef)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff813fe1ff)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:sha256_final
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff813fef16)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:782
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:782
Inline: True
```
```
In drivers/staging/skein/skein_generic.c (ffffffff8177a506)
Location: include/crypto/hash.h:782
Inline: True
Inline callers:
  - drivers/staging/skein/skein_generic.c:skein1024_final
  - drivers/staging/skein/skein_generic.c:skein1024_update
  - drivers/staging/skein/skein_generic.c:skein1024_init
  - drivers/staging/skein/skein_generic.c:skein512_final
  - drivers/staging/skein/skein_generic.c:skein512_update
  - drivers/staging/skein/skein_generic.c:skein512_init
  - drivers/staging/skein/skein_generic.c:skein256_final
  - drivers/staging/skein/skein_generic.c:skein256_update
  - drivers/staging/skein/skein_generic.c:skein256_init
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107a1e6)
Location: include/crypto/hash.h:788
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:788
Inline: True
```
```
In crypto/hmac.c (ffffffff814080ab)
Location: include/crypto/hash.h:788
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff814090ee)
Location: include/crypto/hash.h:788
Inline: True
Inline callers:
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff814094bf)
Location: include/crypto/hash.h:788
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff8140b4df)
Location: include/crypto/hash.h:788
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:sha256_final
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff8140c226)
Location: include/crypto/hash.h:788
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:788
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:788
Inline: True
```
```
In drivers/staging/skein/skein_generic.c (ffffffff817988e6)
Location: include/crypto/hash.h:788
Inline: True
Inline callers:
  - drivers/staging/skein/skein_generic.c:skein1024_final
  - drivers/staging/skein/skein_generic.c:skein1024_update
  - drivers/staging/skein/skein_generic.c:skein1024_init
  - drivers/staging/skein/skein_generic.c:skein512_final
  - drivers/staging/skein/skein_generic.c:skein512_update
  - drivers/staging/skein/skein_generic.c:skein512_init
  - drivers/staging/skein/skein_generic.c:skein256_final
  - drivers/staging/skein/skein_generic.c:skein256_update
  - drivers/staging/skein/skein_generic.c:skein256_init
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810808d6)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (0)
Location: include/crypto/hash.h:796
Inline: True
```
```
In crypto/hmac.c (ffffffff81430a58)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff81431b0e)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff81431edf)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff81433eff)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:sha256_final
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff81434c46)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:796
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:796
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff814412d1)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
```
```
In drivers/staging/skein/skein_generic.c (ffffffff8180ef66)
Location: include/crypto/hash.h:796
Inline: True
Inline callers:
  - drivers/staging/skein/skein_generic.c:skein1024_final
  - drivers/staging/skein/skein_generic.c:skein1024_update
  - drivers/staging/skein/skein_generic.c:skein1024_init
  - drivers/staging/skein/skein_generic.c:skein512_final
  - drivers/staging/skein/skein_generic.c:skein512_update
  - drivers/staging/skein/skein_generic.c:skein512_init
  - drivers/staging/skein/skein_generic.c:skein256_final
  - drivers/staging/skein/skein_generic.c:skein256_update
  - drivers/staging/skein/skein_generic.c:skein256_init
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81083b55)
Location: include/crypto/hash.h:795
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (ffffffff8145f635)
Location: include/crypto/hash.h:795
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814635da)
Location: include/crypto/hash.h:795
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff814645f5)
Location: include/crypto/hash.h:795
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff814649e5)
Location: include/crypto/hash.h:795
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff81466a15)
Location: include/crypto/hash.h:795
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:sha256_final
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff81467775)
Location: include/crypto/hash.h:795
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:795
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:795
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff814741e5)
Location: include/crypto/hash.h:795
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
```
```
In drivers/staging/skein/skein_generic.c (ffffffff81858da5)
Location: include/crypto/hash.h:795
Inline: True
Inline callers:
  - drivers/staging/skein/skein_generic.c:skein1024_import
  - drivers/staging/skein/skein_generic.c:skein1024_export
  - drivers/staging/skein/skein_generic.c:skein1024_final
  - drivers/staging/skein/skein_generic.c:skein1024_update
  - drivers/staging/skein/skein_generic.c:skein1024_init
  - drivers/staging/skein/skein_generic.c:skein512_import
  - drivers/staging/skein/skein_generic.c:skein512_export
  - drivers/staging/skein/skein_generic.c:skein512_final
  - drivers/staging/skein/skein_generic.c:skein512_update
  - drivers/staging/skein/skein_generic.c:skein512_init
  - drivers/staging/skein/skein_generic.c:skein256_import
  - drivers/staging/skein/skein_generic.c:skein256_export
  - drivers/staging/skein/skein_generic.c:skein256_final
  - drivers/staging/skein/skein_generic.c:skein256_update
  - drivers/staging/skein/skein_generic.c:skein256_init
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108a825)
Location: include/crypto/hash.h:807
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (ffffffff8147d065)
Location: include/crypto/hash.h:807
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff8148125a)
Location: include/crypto/hash.h:807
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff81482265)
Location: include/crypto/hash.h:807
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff81482655)
Location: include/crypto/hash.h:807
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff81484685)
Location: include/crypto/hash.h:807
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:sha256_final
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff814853e5)
Location: include/crypto/hash.h:807
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:807
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:807
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff81491d55)
Location: include/crypto/hash.h:807
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e625)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (ffffffff814ab365)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814af454)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff814b04a5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff814b0895)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff814b28b5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:sha256_final
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff814b35f5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff814bf415)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108f285)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (ffffffff814c6025)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814ca0e4)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff814cb115)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff814cb505)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff814cb8a5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff814cc365)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff814d81b5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
Location: include/crypto/hash.h:819
Inline: True
```
```
In crypto/shash.c (ffffffff81524f55)
Location: include/crypto/hash.h:819
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff8152923a)
Location: include/crypto/hash.h:819
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff8152a4b5)
Location: include/crypto/hash.h:819
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (0)
Location: include/crypto/hash.h:819
Inline: True
```
```
In crypto/sha256_generic.c (ffffffff8152ad15)
Location: include/crypto/hash.h:819
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:819
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:819
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:819
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff815379b5)
Location: include/crypto/hash.h:819
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
Location: include/crypto/hash.h:827
Inline: True
```
```
In crypto/shash.c (ffffffff81541e45)
Location: include/crypto/hash.h:827
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff8154620a)
Location: include/crypto/hash.h:827
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff81547465)
Location: include/crypto/hash.h:827
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (0)
Location: include/crypto/hash.h:827
Inline: True
```
```
In crypto/sha256_generic.c (ffffffff81547ce5)
Location: include/crypto/hash.h:827
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:827
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:827
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:827
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff81554835)
Location: include/crypto/hash.h:827
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/shash.c (ffffffff8154a4e5)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff8154e89a)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff8154fb25)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/sha256_generic.c (ffffffff815503a5)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff8155cfa5)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/shash.c (ffffffff815aacc5)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff815af1ea)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff815b0475)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/sha256_generic.c (ffffffff815b0d25)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff815be2d5)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/shash.c (ffffffff816523b5)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff816578fa)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff81658a55)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/sha256_generic.c (ffffffff81659745)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/crc64_rocksoft_generic.c (0)
Location: include/crypto/hash.h:831
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff81667f55)
Location: include/crypto/hash.h:831
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
Location: include/crypto/hash.h:833
Inline: True
```
```
In crypto/shash.c (ffffffff8170be95)
Location: include/crypto/hash.h:833
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff81711b24)
Location: include/crypto/hash.h:833
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff81712e75)
Location: include/crypto/hash.h:833
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (0)
Location: include/crypto/hash.h:833
Inline: True
```
```
In crypto/sha256_generic.c (ffffffff81713a65)
Location: include/crypto/hash.h:833
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (0)
Location: include/crypto/hash.h:833
Inline: True
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:833
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:833
Inline: True
```
```
In crypto/crc64_rocksoft_generic.c (0)
Location: include/crypto/hash.h:833
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff81722665)
Location: include/crypto/hash.h:833
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e05d0)
Location: include/crypto/hash.h:885
Inline: True
```
```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:885
Inline: True
```
```
In crypto/shash.c (ffffffff81745895)
Location: include/crypto/hash.h:885
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff8174c6e4)
Location: include/crypto/hash.h:885
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff8174db15)
Location: include/crypto/hash.h:885
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff8174e66a)
Location: include/crypto/hash.h:885
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
```
In crypto/sha256_generic.c (ffffffff8174e865)
Location: include/crypto/hash.h:885
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff8174fac0)
Location: include/crypto/hash.h:885
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/sha3_generic.c (ffffffff817502f5)
Location: include/crypto/hash.h:885
Inline: True
Inline callers:
  - crypto/sha3_generic.c:crypto_sha3_final
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:885
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:885
Inline: True
```
```
In crypto/crc64_rocksoft_generic.c (0)
Location: include/crypto/hash.h:885
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff8175e945)
Location: include/crypto/hash.h:885
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_init
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
In arch/x86/crypto/sha512_ssse3_glue.c (ffffffff810e8e50)
Location: include/crypto/hash.h:811
Inline: True
```
```
In arch/x86/crypto/crc32c-intel_glue.c (0)
Location: include/crypto/hash.h:811
Inline: True
```
```
In crypto/shash.c (ffffffff81788230)
Location: include/crypto/hash.h:811
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_import
  - crypto/shash.c:crypto_shash_export
```
```
In crypto/hmac.c (ffffffff8178e72b)
Location: include/crypto/hash.h:811
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_init
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff8178f765)
Location: include/crypto/hash.h:811
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff817902ba)
Location: include/crypto/hash.h:811
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
```
```
In crypto/sha256_generic.c (ffffffff817904b5)
Location: include/crypto/hash.h:811
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff81791710)
Location: include/crypto/hash.h:811
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_final
```
```
In crypto/sha3_generic.c (ffffffff81791f45)
Location: include/crypto/hash.h:811
Inline: True
Inline callers:
  - crypto/sha3_generic.c:crypto_sha3_final
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:811
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:811
Inline: True
```
```
In crypto/crc64_rocksoft_generic.c (0)
Location: include/crypto/hash.h:811
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff817a0135)
Location: include/crypto/hash.h:811
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_init
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
In crypto/shash.c (ffff8000105c10c4)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffff8000105c5d7c)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffff8000105c70bc)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffff8000105c72f4)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffff8000105c7898)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffff8000105c80c0)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/ghash-generic.c (ffff8000105d3fcc)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
In crypto/shash.c (c076e9a8)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (c0772af4)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (c0773d08)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (c0773fe4)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (c07742f0)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (c0775684)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/ghash-generic.c (c0781abc)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
In crypto/shash.c (c00000000074942c)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (c00000000074f6ec)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (c000000000750c2c)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (c000000000751028)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (c0000000007514a4)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (c000000000752038)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/ghash-generic.c (c000000000761580)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
In crypto/shash.c (ffffffe000405e18)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffe000409e60)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffe00040b0b8)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffe00040b506)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffe00040b804)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffe00040c0ca)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/ghash-generic.c (ffffffe0004186b0)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e245)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (ffffffff814be605)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814c26c4)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff814c36f5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff814c3ae5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff814c3e85)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff814c4945)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff814d0795)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8107cd55)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (ffffffff814af025)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814b30e4)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff814b4115)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff814b4505)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff814b48a5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff814b5365)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff814c11b5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff8108e1f5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (ffffffff814ba695)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814be754)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff814bf785)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff814bfb75)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff814bff15)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff814c09d5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff814cc825)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
```
```
In lib/libcrc32c.c (0)
Location: include/crypto/hash.h:806
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
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff810905d5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_pcl_intel_finup
```
```
In crypto/shash.c (ffffffff814d3145)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814d7224)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_finup
  - crypto/hmac.c:hmac_final
  - crypto/hmac.c:hmac_update
  - crypto/hmac.c:hmac_import
  - crypto/hmac.c:hmac_export
```
```
In crypto/md5.c (ffffffff814d8255)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/md5.c:md5_import
  - crypto/md5.c:md5_export
  - crypto/md5.c:md5_final
```
```
In crypto/sha1_generic.c (ffffffff814d8645)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha1_generic.c:crypto_sha1_finup
  - crypto/sha1_generic.c:sha1_final
  - crypto/sha1_generic.c:crypto_sha1_update
```
```
In crypto/sha256_generic.c (ffffffff814d89e5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha256_generic.c:crypto_sha256_finup
  - crypto/sha256_generic.c:crypto_sha256_update
```
```
In crypto/sha512_generic.c (ffffffff814d94a5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/sha512_generic.c:crypto_sha512_finup
  - crypto/sha512_generic.c:sha512_final
  - crypto/sha512_generic.c:crypto_sha512_update
```
```
In crypto/crc32c_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/crct10dif_generic.c (0)
Location: include/crypto/hash.h:806
Inline: True
```
```
In crypto/ghash-generic.c (ffffffff814e52f5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/ghash-generic.c:ghash_final
  - crypto/ghash-generic.c:ghash_init
```
</details>
</li>
</ul>

## Differences
