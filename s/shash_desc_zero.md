# Function: <code>shash_desc_zero</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813392d2)
Location: include/crypto/hash.h:913
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
In fs/ecryptfs/crypto.c (ffffffff8134f072)
Location: include/crypto/hash.h:913
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
In fs/ecryptfs/crypto.c (ffffffff81363b22)
Location: include/crypto/hash.h:919
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81398d2c)
Location: include/crypto/hash.h:919
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/ecryptfs/crypto.c (ffffffff81388892)
Location: include/crypto/hash.h:937
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813be53c)
Location: include/crypto/hash.h:937
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/ecryptfs/crypto.c (ffffffff813b76f5)
Location: include/crypto/hash.h:936
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813ef44f)
Location: include/crypto/hash.h:936
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/ecryptfs/crypto.c (ffffffff813d0906)
Location: include/crypto/hash.h:948
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140a6a1)
Location: include/crypto/hash.h:948
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/ecryptfs/crypto.c (ffffffff813fb51e)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814378b9)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/crypto/hkdf.c (ffffffff8134ba35)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ecryptfs/crypto.c (ffffffff814153eb)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81451a86)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/crypto/hkdf.c (ffffffff81391385)
Location: include/crypto/hash.h:987
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In crypto/shash.c (ffffffff81525bbb)
Location: include/crypto/hash.h:987
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
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
In fs/crypto/hkdf.c (ffffffff813a27e5)
Location: include/crypto/hash.h:995
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In crypto/shash.c (ffffffff81542aeb)
Location: include/crypto/hash.h:995
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
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
In fs/crypto/hkdf.c (ffffffff813a9968)
Location: include/crypto/hash.h:999
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In crypto/shash.c (ffffffff8154b18b)
Location: include/crypto/hash.h:999
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
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
In fs/crypto/hkdf.c (ffffffff813f91a8)
Location: include/crypto/hash.h:999
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In crypto/shash.c (ffffffff815ab96b)
Location: include/crypto/hash.h:999
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
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
In fs/crypto/hkdf.c (ffffffff8146c022)
Location: include/crypto/hash.h:999
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In crypto/shash.c (ffffffff81653274)
Location: include/crypto/hash.h:999
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/kdf_sp800108.c (ffffffff8166e189)
Location: include/crypto/hash.h:999
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
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
In fs/crypto/hkdf.c (ffffffff814fd352)
Location: include/crypto/hash.h:1001
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In crypto/shash.c (ffffffff8170cf84)
Location: include/crypto/hash.h:1001
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/kdf_sp800108.c (ffffffff81729379)
Location: include/crypto/hash.h:1001
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
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
In fs/crypto/hkdf.c (ffffffff815348b5)
Location: include/crypto/hash.h:1053
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In crypto/shash.c (ffffffff817468e4)
Location: include/crypto/hash.h:1053
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/jitterentropy-kcapi.c (ffffffff836fd3f4)
Location: include/crypto/hash.h:1053
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
  - crypto/jitterentropy-kcapi.c:jent_hash_time
```
```
In crypto/kdf_sp800108.c (ffffffff817656d9)
Location: include/crypto/hash.h:1053
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
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
In fs/crypto/hkdf.c (ffffffff81569875)
Location: include/crypto/hash.h:968
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In crypto/shash.c (ffffffff81788a64)
Location: include/crypto/hash.h:968
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/jitterentropy-kcapi.c (ffffffff83930a04)
Location: include/crypto/hash.h:968
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
  - crypto/jitterentropy-kcapi.c:jent_hash_time
```
```
In crypto/kdf_sp800108.c (ffffffff817a72d9)
Location: include/crypto/hash.h:968
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
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
In fs/crypto/hkdf.c (ffff80001040c490)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ecryptfs/crypto.c (ffff8000104f6a6c)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053d00c)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/crypto/hkdf.c (c05d95bc)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ecryptfs/crypto.c (c06b44cc)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/encrypted-keys/encrypted.c (c06f2c8c)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/crypto/hkdf.c (c000000000519498)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ecryptfs/crypto.c (c000000000637a60)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068c680)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/crypto/hkdf.c (ffffffe0002b5d74)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ecryptfs/crypto.c (ffffffe0003656b8)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a26a)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/crypto/hkdf.c (ffffffff81344015)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ecryptfs/crypto.c (ffffffff8140d9cb)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a066)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/crypto/hkdf.c (ffffffff81334cf5)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ecryptfs/crypto.c (ffffffff813fe44b)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143aab6)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/crypto/hkdf.c (ffffffff81341ae5)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ecryptfs/crypto.c (ffffffff8140ad4b)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446106)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
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
In fs/crypto/hkdf.c (ffffffff81354de5)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ecryptfs/crypto.c (ffffffff814209eb)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d436)
Location: include/crypto/hash.h:955
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
</details>
</li>
</ul>

## Differences
