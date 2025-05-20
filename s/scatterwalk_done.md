# Function: <code>scatterwalk_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scatterwalk_done(struct scatter_walk *walk, int out, int more);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8139e8c0)
Location: crypto/scatterwalk.c:73
Inline: False
Direct callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
**Symbols:**

```
ffffffff8139e8c0-ffffffff8139e8fa: scatterwalk_done (STB_GLOBAL)
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:114
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff813dcaed)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff813dd9fe)
Location: include/crypto/scatterwalk.h:114
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:114
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff813f43cd)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff813f52ae)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff813f6158)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff81401a9c)
Location: include/crypto/scatterwalk.h:114
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:114
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff8140071d)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814015dc)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff81402588)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff8140ee45)
Location: include/crypto/scatterwalk.h:114
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:114
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff81428d1d)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff81429bec)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8142b619)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff81437915)
Location: include/crypto/scatterwalk.h:114
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:114
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff8145bb5d)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff8145c546)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8145e325)
Location: include/crypto/scatterwalk.h:114
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
```
In crypto/xts.c (ffffffff8146a25c)
Location: include/crypto/scatterwalk.h:114
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:101
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff8147945d)
Location: include/crypto/scatterwalk.h:101
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff8147a1e6)
Location: include/crypto/scatterwalk.h:101
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8147bbe5)
Location: include/crypto/scatterwalk.h:101
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814a751d)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814a80f6)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814a9f86)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814c218d)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814c2d56)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814c4c76)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/skcipher.c (ffffffff81523b06)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/skcipher.c (ffffffff81540a56)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/skcipher.c (ffffffff815490b6)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:91
Inline: True
```
```
In crypto/skcipher.c (ffffffff815a9896)
Location: include/crypto/scatterwalk.h:91
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:92
Inline: True
```
```
In crypto/skcipher.c (ffffffff81650cf6)
Location: include/crypto/scatterwalk.h:92
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:86
Inline: True
```
```
In crypto/skcipher.c (ffffffff8170a4e6)
Location: include/crypto/scatterwalk.h:86
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:86
Inline: True
```
```
In crypto/skcipher.c (ffffffff81743d36)
Location: include/crypto/scatterwalk.h:86
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:86
Inline: True
```
```
In crypto/skcipher.c (ffffffff81786116)
Location: include/crypto/scatterwalk.h:86
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
In crypto/scatterwalk.c (ffff8000105bb250)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/ablkcipher.c (ffff8000105bc5e0)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffff8000105bd508)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffff8000105bf728)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (c0769538)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/ablkcipher.c (c076a6d0)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c076b2ac)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c076d444)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (c0000000007419a4)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/ablkcipher.c (c00000000074354c)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c000000000744628)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c0000000007474b8)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/ablkcipher.c (ffffffe000401e70)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffe000402c04)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffe00040489a)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814ba76d)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814bb336)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814bd256)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814ab18d)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814abd56)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814adc76)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814b67fd)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814b73c6)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814b92e6)
Location: include/crypto/scatterwalk.h:96
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
In crypto/scatterwalk.c (0)
Location: include/crypto/scatterwalk.h:96
Inline: True
```
```
In crypto/ablkcipher.c (ffffffff814cf29d)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffffffff814cfe86)
Location: include/crypto/scatterwalk.h:96
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814d1d86)
Location: include/crypto/scatterwalk.h:96
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
<b>Regular</b>
<ul>
</ul>
