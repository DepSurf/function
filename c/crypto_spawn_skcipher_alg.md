# Function: <code>crypto_spawn_skcipher_alg</code>

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
Location: include/crypto/internal/skcipher.h:90
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:90
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
Location: include/crypto/internal/skcipher.h:118
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:118
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
Location: include/crypto/internal/skcipher.h:118
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:118
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
In crypto/cts.c (ffffffff81436750)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff8143812f)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8143992d)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff814692d3)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff8146aac7)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8146c60c)
Location: include/crypto/internal/skcipher.h:118
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
In crypto/cts.c (ffffffff81486c9e)
Location: include/crypto/internal/skcipher.h:116
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff81488348)
Location: include/crypto/internal/skcipher.h:116
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81489d7c)
Location: include/crypto/internal/skcipher.h:116
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
In crypto/cts.c (ffffffff814b4db1)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff814b5d8e)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b7666)
Location: include/crypto/internal/skcipher.h:111
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
In crypto/cts.c (ffffffff814cd881)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff814cef8e)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814d0886)
Location: include/crypto/internal/skcipher.h:111
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
Location: include/crypto/internal/skcipher.h:106
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff8152e27d)
Location: include/crypto/internal/skcipher.h:106
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8152fc4c)
Location: include/crypto/internal/skcipher.h:106
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
Location: include/crypto/internal/skcipher.h:106
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff8154b248)
Location: include/crypto/internal/skcipher.h:106
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8154ced4)
Location: include/crypto/internal/skcipher.h:106
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
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff81553871)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81554e68)
Location: include/crypto/internal/skcipher.h:107
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
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff815b48a1)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff815b5e98)
Location: include/crypto/internal/skcipher.h:107
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
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff8165d794)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8165f120)
Location: include/crypto/internal/skcipher.h:107
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
Location: include/crypto/internal/skcipher.h:115
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff81717314)
Location: include/crypto/internal/skcipher.h:115
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff817190b0)
Location: include/crypto/internal/skcipher.h:115
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
Location: include/crypto/internal/skcipher.h:115
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff81752c24)
Location: include/crypto/internal/skcipher.h:115
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81754a30)
Location: include/crypto/internal/skcipher.h:115
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
In crypto/cts.c (ffff8000105c975c)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffff8000105cadf8)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffff8000105cc104)
Location: include/crypto/internal/skcipher.h:111
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
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (c07789bc)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c0779a40)
Location: include/crypto/internal/skcipher.h:111
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
In crypto/cts.c (c000000000753e70)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (c000000000755dfc)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c000000000758bdc)
Location: include/crypto/internal/skcipher.h:111
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
In crypto/cts.c (ffffffe00040e43c)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffe00040f528)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffe0004113a6)
Location: include/crypto/internal/skcipher.h:111
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
In crypto/cts.c (ffffffff814c5e61)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff814c756e)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c8e66)
Location: include/crypto/internal/skcipher.h:111
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
In crypto/cts.c (ffffffff814b6881)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff814b7f8e)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b9886)
Location: include/crypto/internal/skcipher.h:111
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
In crypto/cts.c (ffffffff814c1ef1)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff814c35fe)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c4ef6)
Location: include/crypto/internal/skcipher.h:111
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
In crypto/cts.c (ffffffff814da9c1)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff814dc0ce)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814dd9c6)
Location: include/crypto/internal/skcipher.h:111
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
</details>
</li>
</ul>

## Differences
