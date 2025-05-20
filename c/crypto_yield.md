# Function: <code>crypto_yield</code>

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
In crypto/ablkcipher.c (ffffffff8139fbde)
Location: include/crypto/algapi.h:385
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff813a11f9)
Location: include/crypto/algapi.h:385
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/ahash.c (ffffffff813a2b87)
Location: include/crypto/algapi.h:385
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff813a3d0f)
Location: include/crypto/algapi.h:385
Inline: True
Inline callers:
  - crypto/shash.c:shash_compat_digest
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
In crypto/ablkcipher.c (ffffffff813dcb32)
Location: include/crypto/algapi.h:443
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff813dda43)
Location: include/crypto/algapi.h:443
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/ahash.c (ffffffff813ded30)
Location: include/crypto/algapi.h:443
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff813dffcf)
Location: include/crypto/algapi.h:443
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
In crypto/ablkcipher.c (ffffffff813f4412)
Location: include/crypto/algapi.h:378
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff813f52f3)
Location: include/crypto/algapi.h:378
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff813f61a8)
Location: include/crypto/algapi.h:378
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff813f72c0)
Location: include/crypto/algapi.h:378
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff813f8559)
Location: include/crypto/algapi.h:378
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
In crypto/ablkcipher.c (ffffffff81400774)
Location: include/crypto/algapi.h:394
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff81401633)
Location: include/crypto/algapi.h:394
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814025b1)
Location: include/crypto/algapi.h:394
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8140361c)
Location: include/crypto/algapi.h:394
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff81404a68)
Location: include/crypto/algapi.h:394
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
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
In crypto/ablkcipher.c (ffffffff81428d74)
Location: include/crypto/algapi.h:413
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff81429c43)
Location: include/crypto/algapi.h:413
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8142ac21)
Location: include/crypto/algapi.h:413
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8142bdad)
Location: include/crypto/algapi.h:413
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff8142d37c)
Location: include/crypto/algapi.h:413
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
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
In crypto/ablkcipher.c (ffffffff8145bb8f)
Location: include/crypto/algapi.h:420
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff8145c580)
Location: include/crypto/algapi.h:420
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8145d97d)
Location: include/crypto/algapi.h:420
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8145ea74)
Location: include/crypto/algapi.h:420
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff8145ffe8)
Location: include/crypto/algapi.h:420
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
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
In crypto/ablkcipher.c (ffffffff8147948f)
Location: include/crypto/algapi.h:422
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff8147a220)
Location: include/crypto/algapi.h:422
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8147b21d)
Location: include/crypto/algapi.h:422
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8147c41f)
Location: include/crypto/algapi.h:422
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
```
```
In crypto/shash.c (ffffffff8147da78)
Location: include/crypto/algapi.h:422
Inline: True
Inline callers:
  - crypto/shash.c:shash_ahash_digest
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
In crypto/ablkcipher.c (ffffffff814a7558)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814a8139)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814a9474)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814aa716)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/ablkcipher.c (ffffffff814c21c8)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814c2d99)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814c411d)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814c53d6)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/skcipher.c (ffffffff815235fd)
Location: include/crypto/algapi.h:269
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8152430c)
Location: include/crypto/algapi.h:269
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/skcipher.c (ffffffff8154054d)
Location: crypto/internal.h:141
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81541185)
Location: crypto/internal.h:141
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/skcipher.c (ffffffff81548bbd)
Location: crypto/internal.h:141
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff815497b5)
Location: crypto/internal.h:141
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/skcipher.c (ffffffff815a939d)
Location: crypto/internal.h:153
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff815a9f95)
Location: crypto/internal.h:153
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/skcipher.c (ffffffff816507fc)
Location: crypto/internal.h:158
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81651d61)
Location: crypto/internal.h:158
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/skcipher.c (ffffffff81709fac)
Location: crypto/internal.h:176
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8170b791)
Location: crypto/internal.h:176
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/skcipher.c (ffffffff8174350c)
Location: crypto/internal.h:203
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff8174558c)
Location: crypto/internal.h:203
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/skcipher.c (ffffffff8178583c)
Location: crypto/internal.h:203
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff81787838)
Location: crypto/internal.h:203
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
In crypto/ablkcipher.c (ffff8000105bc670)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffff8000105bd598)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffff8000105bed80)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffff8000105c0000)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/ablkcipher.c (c076a798)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c076b344)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c076cdac)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (c076db40)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/ablkcipher.c (c00000000074365c)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c00000000074475c)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c0000000007463dc)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (c000000000747f30)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/ablkcipher.c (ffffffe000401e9e)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffe000402c32)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffe00040403a)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffe000405018)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/ablkcipher.c (ffffffff814ba7a8)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814bb379)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814bc6fd)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814bd9b6)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/ablkcipher.c (ffffffff814ab1c8)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814abd99)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814ad11d)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814ae3d6)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/ablkcipher.c (ffffffff814b6838)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814b7409)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814b878d)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/ahash.c (ffffffff814b9a46)
Location: include/crypto/algapi.h:410
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_hash_walk_done
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
In crypto/ablkcipher.c (0)
Location: include/crypto/algapi.h:410
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/crypto/algapi.h:410
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/crypto/algapi.h:410
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/crypto/algapi.h:410
Inline: True
```
</details>
</li>
</ul>

## Differences
