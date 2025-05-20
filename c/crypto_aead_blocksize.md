# Function: <code>crypto_aead_blocksize</code>

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
In crypto/blkcipher.c (ffffffff813a19ec)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/blkcipher.c (ffffffff813dde9c)
Location: include/crypto/aead.h:248
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
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
In crypto/blkcipher.c (ffffffff813f574c)
Location: include/crypto/aead.h:248
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff813f6bc9)
Location: include/crypto/aead.h:248
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/blkcipher.c (ffffffff814019ec)
Location: include/crypto/aead.h:248
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff81402f99)
Location: include/crypto/aead.h:248
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/blkcipher.c (ffffffff8142a00c)
Location: include/crypto/aead.h:248
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff8142b682)
Location: include/crypto/aead.h:248
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/blkcipher.c (ffffffff8145cd4c)
Location: include/crypto/aead.h:248
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff8145e38e)
Location: include/crypto/aead.h:248
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/blkcipher.c (ffffffff8147a5dc)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff8147bc4e)
Location: include/crypto/aead.h:245
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
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
In crypto/blkcipher.c (ffffffff814a860c)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814a9ff0)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff819eebdd)
Location: include/crypto/aead.h:240
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
In crypto/blkcipher.c (ffffffff814c327c)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814c4ce0)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25abd)
Location: include/crypto/aead.h:240
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
In crypto/skcipher.c (ffffffff81523b70)
Location: include/crypto/aead.h:256
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17593)
Location: include/crypto/aead.h:256
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
In crypto/skcipher.c (ffffffff81540ac0)
Location: include/crypto/aead.h:261
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff81b25653)
Location: include/crypto/aead.h:261
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
In crypto/skcipher.c (ffffffff81549120)
Location: include/crypto/aead.h:263
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff81b13173)
Location: include/crypto/aead.h:263
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
In crypto/skcipher.c (ffffffff815a9900)
Location: include/crypto/aead.h:263
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd7073)
Location: include/crypto/aead.h:263
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
In crypto/skcipher.c (ffffffff81650d60)
Location: include/crypto/aead.h:265
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6da33)
Location: include/crypto/aead.h:265
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
In crypto/skcipher.c (ffffffff8170a550)
Location: include/crypto/aead.h:265
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff81f39033)
Location: include/crypto/aead.h:265
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
In crypto/skcipher.c (ffffffff81743da0)
Location: include/crypto/aead.h:287
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff81f988c3)
Location: include/crypto/aead.h:287
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
In crypto/skcipher.c (ffffffff81786180)
Location: include/crypto/aead.h:299
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff82065c33)
Location: include/crypto/aead.h:299
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
In crypto/blkcipher.c (ffff8000105bda44)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffff8000105bf7a8)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffff800010ce2f7c)
Location: include/crypto/aead.h:240
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
In crypto/blkcipher.c (c076b890)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (c076d4c8)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (c0dec740)
Location: include/crypto/aead.h:240
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
In crypto/blkcipher.c (c000000000744e60)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (c00000000074754c)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (c000000000e06420)
Location: include/crypto/aead.h:240
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
In crypto/blkcipher.c (ffffffe000402ff6)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffe0004048ee)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffe00083184e)
Location: include/crypto/aead.h:240
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
In crypto/blkcipher.c (ffffffff814bb85c)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814bd2c0)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff819c514d)
Location: include/crypto/aead.h:240
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
In crypto/blkcipher.c (ffffffff814ac27c)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814adce0)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff81981f3d)
Location: include/crypto/aead.h:240
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
In crypto/blkcipher.c (ffffffff814b78ec)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814b9350)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2fbcd)
Location: include/crypto/aead.h:240
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
In crypto/blkcipher.c (ffffffff814d03cc)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_aead_walk_virt_block
```
```
In crypto/skcipher.c (ffffffff814d1df0)
Location: include/crypto/aead.h:240
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3b56d)
Location: include/crypto/aead.h:240
Inline: True
```
</details>
</li>
</ul>

## Differences
