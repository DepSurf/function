# Function: <code>scatterwalk_pagedone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8139e870)
Location: crypto/scatterwalk.c:50
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_done
  - crypto/scatterwalk.c:scatterwalk_copychunks
Direct callers:
  - crypto/scatterwalk.c:scatterwalk_done
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
**Symbols:**

```
ffffffff8139e870-ffffffff8139e8bc: scatterwalk_pagedone.isra.8.part.9 (STB_LOCAL)
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
In crypto/scatterwalk.c (ffffffff813db7ae)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff813dcb15)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff813dda26)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
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
In crypto/scatterwalk.c (ffffffff813f30e5)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff813f43f5)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff813f52d6)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff813f6172)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff81401abf)
Location: include/crypto/scatterwalk.h:95
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
In crypto/scatterwalk.c (ffffffff813ff43d)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff8140073d)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814015fc)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814025d4)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff8140ee6c)
Location: include/crypto/scatterwalk.h:95
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
In crypto/scatterwalk.c (ffffffff814279f6)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff81428d3d)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff81429c0c)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8142b62f)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff8143793c)
Location: include/crypto/scatterwalk.h:95
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
In crypto/scatterwalk.c (ffffffff8145a860)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff8145bb71)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff8145c55e)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8145e33b)
Location: include/crypto/scatterwalk.h:95
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff8146a26e)
Location: include/crypto/scatterwalk.h:95
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
In crypto/scatterwalk.c (ffffffff814783d0)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff81479471)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff8147a1fe)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8147bbfb)
Location: include/crypto/scatterwalk.h:82
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff814a6207)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814a7534)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814a8111)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814a9f9c)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff814c0e97)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814c21a4)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814c2d71)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814c4c8c)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff81521741)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81523b1c)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff8153e5b1)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81540a6c)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff81546c7e)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff815490cc)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff815a745e)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff815a98ac)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff8164e7c1)
Location: include/crypto/scatterwalk.h:78
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81650d0c)
Location: include/crypto/scatterwalk.h:78
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff81707c21)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff8170a4fc)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff8174135b)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81743d4c)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff817821fb)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff8178612c)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffff8000105bb100)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffff8000105bc5fc)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffff8000105bd524)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffff8000105bf748)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (c07693e0)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (c076a6f0)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c076b2cc)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c076d468)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (c000000000741808)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (c000000000743570)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c00000000074464c)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c0000000007474e0)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffe000400c20)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffe000401e82)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffe000402c16)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffe0004048ac)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff814b9477)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814ba784)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814bb351)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814bd26c)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff814a9e97)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814ab1a4)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814abd71)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814adc8c)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff814b5507)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814b6814)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814b73e1)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814b92fc)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/scatterwalk.c (ffffffff814cdf9f)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814cf2b4)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814cfea1)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814d1d9c)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
</ul>

## Differences
