# Function: <code>skcipher_alg_instance</code>

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
Location: include/crypto/internal/skcipher.h:45
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:45
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
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/xts.c (ffffffff81401225)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/xts.c (ffffffff8140e6b5)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
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
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/xts.c (ffffffff81437185)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
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
In crypto/cbc.c (ffffffff814688e5)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff81469195)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814699a5)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8146a755)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/cbc.c (ffffffff81486555)
Location: include/crypto/internal/skcipher.h:79
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff81486b65)
Location: include/crypto/internal/skcipher.h:79
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81487765)
Location: include/crypto/internal/skcipher.h:79
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff81487fb5)
Location: include/crypto/internal/skcipher.h:79
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
In crypto/skcipher.c (ffffffff814a91f5)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814b4c85)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814b5455)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814b5b85)
Location: include/crypto/internal/skcipher.h:74
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
In crypto/skcipher.c (ffffffff814c3e65)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814cd755)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814ce6a5)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814ced85)
Location: include/crypto/internal/skcipher.h:74
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
In crypto/skcipher.c (ffffffff81522d65)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff8152cb75)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff8152daa5)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff8152e0a5)
Location: include/crypto/internal/skcipher.h:74
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
In crypto/skcipher.c (ffffffff8153fcb5)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff81549be5)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff8154aa75)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff8154afa5)
Location: include/crypto/internal/skcipher.h:74
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
In crypto/skcipher.c (ffffffff81548225)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff81552225)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81553095)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff815535c5)
Location: include/crypto/internal/skcipher.h:75
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
In crypto/skcipher.c (ffffffff815a8a05)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff815b3225)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff815b40c5)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff815b45f5)
Location: include/crypto/internal/skcipher.h:75
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
In crypto/skcipher.c (ffffffff8164fde5)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff8165c205)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff8165cf15)
Location: include/crypto/internal/skcipher.h:75
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff8165d4a5)
Location: include/crypto/internal/skcipher.h:75
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
In crypto/skcipher.c (ffffffff817092b5)
Location: include/crypto/internal/skcipher.h:83
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff81715bc5)
Location: include/crypto/internal/skcipher.h:83
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff817169d5)
Location: include/crypto/internal/skcipher.h:83
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff81716fd5)
Location: include/crypto/internal/skcipher.h:83
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
In crypto/skcipher.c (ffffffff81742af5)
Location: include/crypto/internal/skcipher.h:83
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff81751475)
Location: include/crypto/internal/skcipher.h:83
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81752285)
Location: include/crypto/internal/skcipher.h:83
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff817528d5)
Location: include/crypto/internal/skcipher.h:83
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
In crypto/skcipher.c (ffffffff81784d35)
Location: include/crypto/internal/skcipher.h:104
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff817932c5)
Location: include/crypto/internal/skcipher.h:104
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff81794105)
Location: include/crypto/internal/skcipher.h:104
Inline: True
Inline callers:
  - crypto/xts.c:xts_init_tfm
```
```
In crypto/ctr.c (ffffffff81794845)
Location: include/crypto/internal/skcipher.h:104
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
In crypto/skcipher.c (ffff8000105be968)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffff8000105c964c)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffff8000105ca55c)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffff8000105cacec)
Location: include/crypto/internal/skcipher.h:74
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
In crypto/skcipher.c (c076c5d4)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (c07771e0)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (c0778178)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (c07788b8)
Location: include/crypto/internal/skcipher.h:74
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
In crypto/skcipher.c (c000000000746210)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (c000000000753ca0)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (c00000000075510c)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (c000000000755b10)
Location: include/crypto/internal/skcipher.h:74
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
In crypto/skcipher.c (ffffffe000403cb6)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffe00040e31e)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffe00040eab2)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffe00040f1e6)
Location: include/crypto/internal/skcipher.h:74
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
In crypto/skcipher.c (ffffffff814bc445)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814c5d35)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814c6c85)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814c7365)
Location: include/crypto/internal/skcipher.h:74
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
In crypto/skcipher.c (ffffffff814ace65)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814b6755)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814b76a5)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814b7d85)
Location: include/crypto/internal/skcipher.h:74
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
In crypto/skcipher.c (ffffffff814b84d5)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814c1dc5)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814c2d15)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814c33f5)
Location: include/crypto/internal/skcipher.h:74
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
In crypto/skcipher.c (ffffffff814d0fb5)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814da895)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_init_tfm
```
```
In crypto/xts.c (ffffffff814db7e5)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/xts.c:init_tfm
```
```
In crypto/ctr.c (ffffffff814dbec5)
Location: include/crypto/internal/skcipher.h:74
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_init_tfm
```
</details>
</li>
</ul>

## Differences
