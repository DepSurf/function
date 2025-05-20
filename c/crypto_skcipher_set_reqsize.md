# Function: <code>crypto_skcipher_set_reqsize</code>

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
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:108
Inline: True
```
```
In crypto/ctr.c (ffffffff813e8cea)
Location: include/crypto/internal/skcipher.h:108
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:130
Inline: True
```
```
In crypto/xts.c (ffffffff81401270)
Location: include/crypto/internal/skcipher.h:130
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814022fa)
Location: include/crypto/internal/skcipher.h:130
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:130
Inline: True
```
```
In crypto/xts.c (ffffffff8140e700)
Location: include/crypto/internal/skcipher.h:130
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8140f41a)
Location: include/crypto/internal/skcipher.h:130
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:130
Inline: True
```
```
In crypto/xts.c (ffffffff814371d0)
Location: include/crypto/internal/skcipher.h:130
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff81437e2a)
Location: include/crypto/internal/skcipher.h:130
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff814691bd)
Location: include/crypto/internal/skcipher.h:130
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81469a03)
Location: include/crypto/internal/skcipher.h:130
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8146a77d)
Location: include/crypto/internal/skcipher.h:130
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff81486b8d)
Location: include/crypto/internal/skcipher.h:128
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814877c3)
Location: include/crypto/internal/skcipher.h:128
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff81487fdd)
Location: include/crypto/internal/skcipher.h:128
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff814b4cad)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814b54a8)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814b5bad)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff814cd77d)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814ce6f8)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814cedad)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff8152cb9d)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff8152daf8)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8152e0cd)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff81549c0d)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff8154aac8)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff8154afcd)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff8155224d)
Location: include/crypto/internal/skcipher.h:119
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff815530e8)
Location: include/crypto/internal/skcipher.h:119
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff815535ed)
Location: include/crypto/internal/skcipher.h:119
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff815b324d)
Location: include/crypto/internal/skcipher.h:119
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff815b4118)
Location: include/crypto/internal/skcipher.h:119
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff815b461d)
Location: include/crypto/internal/skcipher.h:119
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff8165c22d)
Location: include/crypto/internal/skcipher.h:119
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff8165cf68)
Location: include/crypto/internal/skcipher.h:119
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff8165d4cd)
Location: include/crypto/internal/skcipher.h:119
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff81715bed)
Location: include/crypto/internal/skcipher.h:127
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81716a28)
Location: include/crypto/internal/skcipher.h:127
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff81716ffd)
Location: include/crypto/internal/skcipher.h:127
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff8175149d)
Location: include/crypto/internal/skcipher.h:127
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff817522d8)
Location: include/crypto/internal/skcipher.h:127
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff817528fd)
Location: include/crypto/internal/skcipher.h:127
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/skcipher.c (ffffffff81785420)
Location: include/crypto/internal/skcipher.h:181
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_init_tfm
```
```
In crypto/cts.c (ffffffff817932ed)
Location: include/crypto/internal/skcipher.h:181
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81794158)
Location: include/crypto/internal/skcipher.h:181
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff8179486d)
Location: include/crypto/internal/skcipher.h:181
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffff8000105c9668)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffff8000105ca598)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffff8000105cad08)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (c0777208)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (c07781b8)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (c07788d4)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (c000000000753cc8)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (c000000000755158)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (c000000000755b38)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffe00040e334)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffe00040eaea)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffe00040f1fe)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff814c5d5d)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814c6cd8)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814c738d)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff814b677d)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814b76f8)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814b7dad)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff814c1ded)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814c2d68)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814c341d)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
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
In crypto/cts.c (ffffffff814da8bd)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814db838)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814dbeed)
Location: include/crypto/internal/skcipher.h:123
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
</details>
</li>
</ul>

## Differences
