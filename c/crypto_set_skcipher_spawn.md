# Function: <code>crypto_set_skcipher_spawn</code>

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
In crypto/blkcipher.c (ffffffff813a0df1)
Location: include/crypto/internal/skcipher.h:28
Inline: True
Inline callers:
  - crypto/blkcipher.c:skcipher_geniv_alloc
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
In crypto/cts.c (ffffffff813e7eb5)
Location: include/crypto/internal/skcipher.h:62
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:62
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
In crypto/cts.c (ffffffff81400ce5)
Location: include/crypto/internal/skcipher.h:98
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81401637)
Location: include/crypto/internal/skcipher.h:98
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:98
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
In crypto/cts.c (ffffffff8140dc8d)
Location: include/crypto/internal/skcipher.h:98
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8140e9f2)
Location: include/crypto/internal/skcipher.h:98
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:98
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
In crypto/cts.c (ffffffff8143672d)
Location: include/crypto/internal/skcipher.h:98
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814374c2)
Location: include/crypto/internal/skcipher.h:98
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (0)
Location: include/crypto/internal/skcipher.h:98
Inline: True
```
```
In crypto/gcm.c (ffffffff814398fa)
Location: include/crypto/internal/skcipher.h:98
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
In crypto/cts.c (ffffffff814692a7)
Location: include/crypto/internal/skcipher.h:98
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81469dee)
Location: include/crypto/internal/skcipher.h:98
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8146aa8e)
Location: include/crypto/internal/skcipher.h:98
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8146c5da)
Location: include/crypto/internal/skcipher.h:98
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
In crypto/cts.c (ffffffff81486c72)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81487ade)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8148830f)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81489d4a)
Location: include/crypto/internal/skcipher.h:96
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
In crypto/cts.c (ffffffff814b4d88)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b57e7)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b5d58)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b7631)
Location: include/crypto/internal/skcipher.h:91
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
In crypto/cts.c (ffffffff814cd858)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814ce9e7)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814cef58)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814d0851)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
In crypto/cts.c (ffff8000105c9734)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffff8000105ca654)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffff8000105cadc0)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffff8000105cc0d4)
Location: include/crypto/internal/skcipher.h:91
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
In crypto/cts.c (c07772c4)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c0778264)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c0778980)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c0779a14)
Location: include/crypto/internal/skcipher.h:91
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
In crypto/cts.c (c000000000753e34)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (c0000000007555e0)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (c000000000755dc8)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (c000000000758ba0)
Location: include/crypto/internal/skcipher.h:91
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
In crypto/cts.c (ffffffe00040e414)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffe00040edcc)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffe00040f4f8)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffe000411382)
Location: include/crypto/internal/skcipher.h:91
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
In crypto/cts.c (ffffffff814c5e38)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c6fc7)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c7538)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c8e31)
Location: include/crypto/internal/skcipher.h:91
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
In crypto/cts.c (ffffffff814b6858)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814b79e7)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814b7f58)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814b9851)
Location: include/crypto/internal/skcipher.h:91
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
In crypto/cts.c (ffffffff814c1ec8)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814c3057)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814c35c8)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814c4ec1)
Location: include/crypto/internal/skcipher.h:91
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
In crypto/cts.c (ffffffff814da998)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff814dbb27)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff814dc098)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff814dd991)
Location: include/crypto/internal/skcipher.h:91
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
</details>
</li>
</ul>

## Differences
