# Function: <code>crypto_skcipher_alignmask</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cts.c (ffffffff813e7dc5)
Location: include/crypto/skcipher.h:325
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff813e8cd5)
Location: include/crypto/skcipher.h:325
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff813eed95)
Location: include/crypto/skcipher.h:325
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff813f6aa9)
Location: include/crypto/skcipher.h:325
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff81400bf5)
Location: include/crypto/skcipher.h:325
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814022e5)
Location: include/crypto/skcipher.h:325
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814085db)
Location: include/crypto/skcipher.h:325
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff81402e86)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff8140dba5)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8140f405)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff81415ccb)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff8142b4f5)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff81436645)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff81437e15)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814404a3)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff8145d3ba)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff814691bd)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8146a77d)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff81473383)
Location: include/crypto/skcipher.h:359
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff8147ac3a)
Location: include/crypto/skcipher.h:378
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff81486b8d)
Location: include/crypto/skcipher.h:378
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff81487fdd)
Location: include/crypto/skcipher.h:378
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff8148f8fa)
Location: include/crypto/skcipher.h:378
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff814a9bcd)
Location: include/crypto/skcipher.h:313
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff814b4cad)
Location: include/crypto/skcipher.h:313
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814b5bad)
Location: include/crypto/skcipher.h:313
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814be28f)
Location: include/crypto/skcipher.h:313
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff814c48bd)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff814cd77d)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814cedad)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814d70df)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff81522909)
Location: include/crypto/skcipher.h:305
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cts.c (ffffffff8152cb9d)
Location: include/crypto/skcipher.h:305
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8152e0cd)
Location: include/crypto/skcipher.h:305
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff815338ec)
Location: include/crypto/skcipher.h:305
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff8153f7c9)
Location: include/crypto/skcipher.h:305
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cts.c (ffffffff81549c0d)
Location: include/crypto/skcipher.h:305
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8154afcd)
Location: include/crypto/skcipher.h:305
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff8155083c)
Location: include/crypto/skcipher.h:305
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff81547d59)
Location: include/crypto/skcipher.h:307
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cts.c (ffffffff8155224d)
Location: include/crypto/skcipher.h:307
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff815535ed)
Location: include/crypto/skcipher.h:307
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff8155901c)
Location: include/crypto/skcipher.h:307
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff815a8539)
Location: include/crypto/skcipher.h:307
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cts.c (ffffffff815b324d)
Location: include/crypto/skcipher.h:307
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff815b461d)
Location: include/crypto/skcipher.h:307
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff815ba2dc)
Location: include/crypto/skcipher.h:307
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff8164fea9)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cts.c (ffffffff8165c22d)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8165d4cd)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff81663370)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff817095d9)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cts.c (ffffffff81715bed)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff81716ffd)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff8171d600)
Location: include/crypto/skcipher.h:311
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff81742e19)
Location: include/crypto/skcipher.h:333
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
```
```
In crypto/cts.c (ffffffff8175149d)
Location: include/crypto/skcipher.h:333
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff817528fd)
Location: include/crypto/skcipher.h:333
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff81758ee0)
Location: include/crypto/skcipher.h:333
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/lskcipher.c (ffffffff81783e32)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/lskcipher.c:crypto_lskcipher_crypt_sg
```
```
In crypto/skcipher.c (ffffffff81785414)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
  - crypto/skcipher.c:crypto_skcipher_import
  - crypto/skcipher.c:crypto_skcipher_export
  - crypto/skcipher.c:crypto_skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff817932ed)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff8179486d)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff8179ade0)
Location: include/crypto/skcipher.h:552
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffff8000105bebcc)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffff8000105c9668)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffff8000105cad08)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffff8000105d1580)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (c076d03c)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (c0777208)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (c07788d4)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (c07804f8)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (c000000000746f28)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (c000000000753cc8)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (c000000000755b38)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (c00000000075fd24)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffe000403dae)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffe00040e334)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffe00040f1fa)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffe0004162fc)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff814bce9d)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff814c5d5d)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814c738d)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814cf6bf)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff814ad8bd)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff814b677d)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814b7dad)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814c00df)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff814b8f2d)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff814c1ded)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814c341d)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814cb74f)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
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
In crypto/skcipher.c (ffffffff814d19ed)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_walk_skcipher
```
```
In crypto/cts.c (ffffffff814da8bd)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/ctr.c (ffffffff814dbeed)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
  - crypto/ctr.c:crypto_rfc3686_crypt
```
```
In crypto/drbg.c (ffffffff814e421f)
Location: include/crypto/skcipher.h:343
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
</details>
</li>
</ul>

## Differences
