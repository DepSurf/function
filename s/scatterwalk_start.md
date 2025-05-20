# Function: <code>scatterwalk_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void scatterwalk_start(struct scatter_walk *walk, struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8139e840)
Location: crypto/scatterwalk.c:33
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
Direct callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
```
**Symbols:**

```
ffffffff8139e840-ffffffff8139e84b: scatterwalk_start.part.6 (STB_LOCAL)
ffffffff8139e850-ffffffff8139e86f: scatterwalk_start (STB_GLOBAL)
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
In crypto/scatterwalk.c (ffffffff813db9f8)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff813dcfa5)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff813ddc89)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff813f310c)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff813f4875)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff813f5539)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff813f6b6d)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff81401ac7)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/scatterwalk.c (ffffffff813ff464)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff81400bc5)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff81401805)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff81402f3d)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff8140ee7a)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/scatterwalk.c (ffffffff81427a19)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814291c5)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff81429e15)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8142b5df)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff8143794a)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/scatterwalk.c (ffffffff8145a879)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff8145bf85)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff8145cb65)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8145e2e6)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff8146a283)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/scatterwalk.c (ffffffff814783e9)
Location: include/crypto/scatterwalk.h:69
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff81479885)
Location: include/crypto/scatterwalk.h:69
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff8147a3f5)
Location: include/crypto/scatterwalk.h:69
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8147bba6)
Location: include/crypto/scatterwalk.h:69
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814a622f)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814a76d9)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814a8415)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814a9f46)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814c0ebf)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814c2359)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814c3085)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814c4c36)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff81521763)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81523ac6)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff8153e5d3)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81540a16)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff81546c98)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81549076)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff815a7478)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff815a9856)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff8164e8c4)
Location: include/crypto/scatterwalk.h:65
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81650cb6)
Location: include/crypto/scatterwalk.h:65
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff81707d34)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff8170a4a6)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff81741454)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81743cf6)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_async
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_virt
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff817822f4)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff817860d6)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffff8000105bb148)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffff8000105bca6c)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffff8000105bd790)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffff8000105bf6f0)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (c076943c)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (c076a934)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c076b628)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c076d40c)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (c000000000741858)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (c0000000007438b0)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c000000000744b70)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c000000000747478)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffe000400c3e)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffe000402270)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffe000402db8)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffe000404868)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814b949f)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814ba939)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814bb665)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814bd216)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814a9ebf)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814ab359)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814ac085)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814adc36)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814b552f)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814b69c9)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814b76f5)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814b92a6)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814cdfc7)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814cf459)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_phys
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814d01d5)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_first
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814d1d46)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_skcipher
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
