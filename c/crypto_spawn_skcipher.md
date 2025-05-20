# Function: <code>crypto_spawn_skcipher</code>

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
In crypto/blkcipher.c (ffffffff813a0ce6)
Location: include/crypto/internal/skcipher.h:50
Inline: True
Inline callers:
  - crypto/blkcipher.c:skcipher_geniv_init
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
In crypto/cts.c (ffffffff813e7daa)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/ctr.c (ffffffff813e8cba)
Location: include/crypto/internal/skcipher.h:96
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
In crypto/cts.c (ffffffff81400bda)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81401229)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814022ca)
Location: include/crypto/internal/skcipher.h:124
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
In crypto/cts.c (ffffffff8140db8a)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff8140e6b9)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8140f3ea)
Location: include/crypto/internal/skcipher.h:124
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
In crypto/cts.c (ffffffff8143662a)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81437189)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff81437dfa)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff81438ce1)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff81469195)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814699b9)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8146a755)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff8146afeb)
Location: include/crypto/internal/skcipher.h:124
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff81486b65)
Location: include/crypto/internal/skcipher.h:122
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81487779)
Location: include/crypto/internal/skcipher.h:122
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff81487fb5)
Location: include/crypto/internal/skcipher.h:122
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff814888eb)
Location: include/crypto/internal/skcipher.h:122
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff814b4c85)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814b5469)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814b5b85)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff814b66d0)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff814cd755)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814ce6b9)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814ced85)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff814cf8f0)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff8152cb75)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff8152dab9)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8152e0a5)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff8152eaf0)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff81549be5)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff8154aa89)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff8154afa5)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff8154ba70)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff81552225)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff815530a9)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff815535c5)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff81554070)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff815b3225)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff815b40d9)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff815b45f5)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff815b50a0)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff8165c205)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff8165cf29)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff8165d4a5)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff8165e140)
Location: include/crypto/internal/skcipher.h:113
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff81715bc5)
Location: include/crypto/internal/skcipher.h:121
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff817169e9)
Location: include/crypto/internal/skcipher.h:121
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff81716fd5)
Location: include/crypto/internal/skcipher.h:121
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff81717ab0)
Location: include/crypto/internal/skcipher.h:121
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff81751475)
Location: include/crypto/internal/skcipher.h:121
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81752299)
Location: include/crypto/internal/skcipher.h:121
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff817528d5)
Location: include/crypto/internal/skcipher.h:121
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff81753490)
Location: include/crypto/internal/skcipher.h:121
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff817932c5)
Location: include/crypto/internal/skcipher.h:169
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81794119)
Location: include/crypto/internal/skcipher.h:169
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff81794845)
Location: include/crypto/internal/skcipher.h:169
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff81795360)
Location: include/crypto/internal/skcipher.h:169
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffff8000105c964c)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffff8000105ca560)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffff8000105cacec)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffff8000105cba20)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (c07771e0)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (c077817c)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (c07788b8)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (c077943c)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (c000000000753ca0)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (c000000000755114)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (c000000000755b10)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (c000000000756c10)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffe00040e31e)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffe00040eab6)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffe00040f1e6)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffe00040fd58)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff814c5d35)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814c6c99)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814c7365)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff814c7ed0)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff814b6755)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814b76b9)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814b7d85)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff814b88f0)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff814c1dc5)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814c2d29)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814c33f5)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff814c3f60)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
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
In crypto/cts.c (ffffffff814da895)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814db7f9)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814dbec5)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
```
In crypto/gcm.c (ffffffff814dca30)
Location: include/crypto/internal/skcipher.h:117
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_init_tfm
```
</details>
</li>
</ul>

## Differences
