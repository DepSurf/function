# Function: <code>crypto_skcipher_spawn_alg</code>

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
In crypto/blkcipher.c (0)
Location: include/crypto/internal/skcipher.h:44
Inline: True
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
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:84
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:84
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
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:112
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:112
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:112
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
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:112
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:112
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:112
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
In crypto/cts.c (0)
Location: include/crypto/internal/skcipher.h:112
Inline: True
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:112
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:112
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/crypto/internal/skcipher.h:112
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
In crypto/cts.c (ffffffff814692db)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81469e30)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8146aace)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8146c613)
Location: include/crypto/internal/skcipher.h:112
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff81486ca5)
Location: include/crypto/internal/skcipher.h:110
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81487b20)
Location: include/crypto/internal/skcipher.h:110
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8148834f)
Location: include/crypto/internal/skcipher.h:110
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81489d83)
Location: include/crypto/internal/skcipher.h:110
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff814b4db8)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b5826)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b5d95)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b766d)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff814cd888)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814cea26)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814cef95)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814d088d)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff8152cc91)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8152dce5)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8152e27d)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8152fc4c)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff81549d1d)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8154acb4)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff8154b248)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8154ced4)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff8155235d)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff815532e2)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81553871)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81554e68)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff815b335d)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff815b4312)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff815b48a1)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff815b5e98)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff8165c364)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8165d1a6)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff8165d794)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8165f120)
Location: include/crypto/internal/skcipher.h:101
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff81715d44)
Location: include/crypto/internal/skcipher.h:109
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81716c96)
Location: include/crypto/internal/skcipher.h:109
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81717314)
Location: include/crypto/internal/skcipher.h:109
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff817190b0)
Location: include/crypto/internal/skcipher.h:109
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff817515f4)
Location: include/crypto/internal/skcipher.h:109
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81752543)
Location: include/crypto/internal/skcipher.h:109
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81752c24)
Location: include/crypto/internal/skcipher.h:109
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81754a30)
Location: include/crypto/internal/skcipher.h:109
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffff8000105c9760)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffff8000105ca694)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffff8000105cadfc)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffff8000105cc108)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (c07772ec)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c07782a8)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c07789bc)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c0779a40)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (c000000000753e74)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c000000000755630)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c000000000755e00)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c000000000758be0)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffe00040e440)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffe00040ee04)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffe00040f52c)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffe0004113aa)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff814c5e68)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c7006)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c7575)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c8e6d)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff814b6888)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b7a26)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b7f95)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b988d)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff814c1ef8)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c3096)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c3605)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c4efd)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff814da9c8)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814dbb66)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814dc0d5)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814dd9cd)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
</details>
</li>
</ul>

## Differences
