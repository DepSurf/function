# Function: <code>crypto_ahash_set_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8142c477)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
```
```
In crypto/shash.c (ffffffff8142d481)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff8143a4f0)
Location: include/crypto/hash.h:356
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff8145f147)
Location: include/crypto/hash.h:355
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
```
```
In crypto/shash.c (ffffffff814600db)
Location: include/crypto/hash.h:355
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff8146ce6c)
Location: include/crypto/hash.h:355
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff8147cb30)
Location: include/crypto/hash.h:359
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8147db4a)
Location: include/crypto/hash.h:359
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff81489466)
Location: include/crypto/hash.h:359
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff814aaae0)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814abde6)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff814b7086)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff814c57a0)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814c6ac6)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff814d02a6)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff81524b60)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff81525d76)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff81530305)
Location: include/crypto/hash.h:371
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff81541a38)
Location: include/crypto/hash.h:379
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff81542cab)
Location: include/crypto/hash.h:379
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff8154d254)
Location: include/crypto/hash.h:379
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff8154a098)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8154b34b)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff815551cf)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff815aa878)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff815abb2b)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff815b61ff)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff81651ee8)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8165345b)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff8165f4ad)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff8170b938)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff8170d19b)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff817188dd)
Location: include/crypto/hash.h:381
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff817453ce)
Location: include/crypto/hash.h:412
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff81746b5b)
Location: include/crypto/hash.h:412
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff8175424d)
Location: include/crypto/hash.h:412
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff81787682)
Location: include/crypto/hash.h:393
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/gcm.c (ffffffff81795bbd)
Location: include/crypto/hash.h:393
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffff8000105c04b4)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffff8000105c1fa4)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffff8000105cc770)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (c076e010)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (c076f528)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (c077a65c)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (c00000000074854c)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (c00000000074a604)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (c000000000757bf4)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffe000405414)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffe000406ae2)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffe0004106cc)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff814bdd80)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814bf0a6)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff814c8886)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff814ae7a0)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814afac6)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff814b92a6)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff814b9e10)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814bb136)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff814c4916)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/ahash.c (ffffffff814d28c0)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/ahash.c:crypto_ahash_setkey
```
```
In crypto/shash.c (ffffffff814d3c06)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
```
```
In crypto/gcm.c (ffffffff814dd3e6)
Location: include/crypto/hash.h:358
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
</details>
</li>
</ul>

## Differences
