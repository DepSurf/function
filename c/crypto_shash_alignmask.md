# Function: <code>crypto_shash_alignmask</code>

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
In crypto/shash.c (ffffffff813a3583)
Location: include/crypto/hash.h:660
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_final
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
In crypto/shash.c (ffffffff813df8ff)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff813eec41)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff813f7e8f)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff81408481)
Location: include/crypto/hash.h:698
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff8140434f)
Location: include/crypto/hash.h:704
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff81415b46)
Location: include/crypto/hash.h:704
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff8142cc2f)
Location: include/crypto/hash.h:712
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff81440316)
Location: include/crypto/hash.h:712
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff8145fa0c)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff8147321a)
Location: include/crypto/hash.h:711
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff8147d48c)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff81490f9a)
Location: include/crypto/hash.h:723
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff814ab78c)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff814be124)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff814c646c)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff814d6f74)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff81525a57)
Location: include/crypto/hash.h:735
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/drbg.c (ffffffff815364f6)
Location: include/crypto/hash.h:735
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff81542987)
Location: include/crypto/hash.h:743
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/drbg.c (ffffffff81553466)
Location: include/crypto/hash.h:743
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff8154b027)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/drbg.c (ffffffff8155bbe6)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff815ab807)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/drbg.c (ffffffff815bcf16)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff816530cb)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/drbg.c (ffffffff816668b3)
Location: include/crypto/hash.h:747
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff8170cdab)
Location: include/crypto/hash.h:749
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_ahash_finup
  - crypto/shash.c:shash_async_final
  - crypto/shash.c:shash_async_update
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/drbg.c (ffffffff81720caf)
Location: include/crypto/hash.h:749
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff81746a64)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:shash_async_setkey
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:shash_setkey_unaligned
```
```
In crypto/drbg.c (ffffffff8175c55f)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In crypto/shash.c (ffff8000105c16e4)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffff8000105d1f88)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (c076ee1c)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (c0780398)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (c000000000749b4c)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (c00000000075fb6c)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffe00040637e)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffe000416cb6)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff814bea4c)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff814cf554)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff814af46c)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff814bff74)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff814baadc)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff814cb5e4)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
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
In crypto/shash.c (ffffffff814d358c)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_digest
  - crypto/shash.c:crypto_shash_finup
  - crypto/shash.c:crypto_shash_final
  - crypto/shash.c:shash_final_unaligned
  - crypto/shash.c:crypto_shash_update
  - crypto/shash.c:shash_update_unaligned
  - crypto/shash.c:crypto_shash_setkey
```
```
In crypto/drbg.c (ffffffff814e40b4)
Location: include/crypto/hash.h:722
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
</details>
</li>
</ul>

## Differences
