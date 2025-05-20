# Function: <code>crypto_skcipher_alg_max_keysize</code>

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
In crypto/cts.c (ffffffff813e7fe7)
Location: include/crypto/internal/skcipher.h:160
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff813e900e)
Location: include/crypto/internal/skcipher.h:160
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81400e17)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814017b7)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff81402632)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff8140ddd0)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8140eb70)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8140f75b)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81436870)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81437640)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8143825b)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814693cd)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81469f6e)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8146abf0)
Location: include/crypto/internal/skcipher.h:197
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81486da4)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81487c56)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff81488462)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814b4e8e)
Location: include/crypto/internal/skcipher.h:190
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b59bf)
Location: include/crypto/internal/skcipher.h:190
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b5eb2)
Location: include/crypto/internal/skcipher.h:190
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814cd95e)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814cebbf)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814cf0b2)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff8152cd3f)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8152de07)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8152e34c)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81549dc6)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8154ade3)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff8154b2fa)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81552408)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8155340e)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff8155391f)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff815b3408)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff815b443e)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff815b494f)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff8165c41a)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8165d2d6)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff8165d846)
Location: include/crypto/internal/skcipher.h:170
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff81715dfa)
Location: include/crypto/internal/skcipher.h:200
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81716dc6)
Location: include/crypto/internal/skcipher.h:200
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff817173c6)
Location: include/crypto/internal/skcipher.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff817516b3)
Location: include/crypto/internal/skcipher.h:200
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81752698)
Location: include/crypto/internal/skcipher.h:200
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81752cdf)
Location: include/crypto/internal/skcipher.h:200
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In crypto/cts.c (ffff8000105c986c)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffff8000105ca82c)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffff8000105caf48)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (c07773fc)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c0778448)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c0778ad8)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (c000000000753fc0)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c000000000755754)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c000000000755fc0)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffe00040e534)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffe00040ef96)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffe00040f644)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814c5f3e)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c719f)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c7692)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814b695e)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b7bbf)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b80b2)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814c1fce)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c322f)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c3722)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/cts.c (ffffffff814daa9e)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814dbcff)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814dc1f2)
Location: include/crypto/internal/skcipher.h:195
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
</ul>

## Differences
