# Function: <code>crypto_drop_skcipher</code>

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
In crypto/blkcipher.c (ffffffff813a0cbd)
Location: include/crypto/internal/skcipher.h:39
Inline: True
Inline callers:
  - crypto/blkcipher.c:skcipher_geniv_free
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
In crypto/cts.c (ffffffff813e7f22)
Location: include/crypto/internal/skcipher.h:79
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/ctr.c (ffffffff813e8f1a)
Location: include/crypto/internal/skcipher.h:79
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
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
In crypto/cbc.c (ffffffff813fff8d)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_free
```
```
In crypto/cts.c (ffffffff81400d52)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffff814016a0)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffff81402531)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
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
In crypto/cbc.c (ffffffff8140d29d)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_free
```
```
In crypto/cts.c (ffffffff8140dcff)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffff8140ebea)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffff8140f664)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
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
In crypto/cbc.c (ffffffff81435d0d)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_free
```
```
In crypto/cts.c (ffffffff8143679f)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffff814376ba)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffff81438164)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (ffffffff81439960)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cbc.c (ffffffff81468895)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_free
```
```
In crypto/cts.c (ffffffff8146944a)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffff81469fef)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffff8146aafc)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (ffffffff8146c646)
Location: include/crypto/internal/skcipher.h:107
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cbc.c (ffffffff81486505)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_free
```
```
In crypto/cts.c (ffffffff81486cf5)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffff81487cd3)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffff81488381)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (ffffffff81489db6)
Location: include/crypto/internal/skcipher.h:105
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cts.c (ffffffff814b4deb)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffff814b5884)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffff814b5dc1)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (ffffffff814b7680)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cts.c (ffffffff814cd8bb)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffff814cea84)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffff814cefc1)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (ffffffff814d08a0)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cts.c (ffffffff8152cca6)
Location: include/crypto/internal/skcipher.h:95
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8152dd01)
Location: include/crypto/internal/skcipher.h:95
Inline: True
Inline callers:
  - crypto/xts.c:create
```
```
In crypto/ctr.c (ffffffff8152e290)
Location: include/crypto/internal/skcipher.h:95
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8152fc0d)
Location: include/crypto/internal/skcipher.h:95
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
In crypto/cts.c (ffffffff81549d67)
Location: include/crypto/internal/skcipher.h:95
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8154accc)
Location: include/crypto/internal/skcipher.h:95
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff8154b28c)
Location: include/crypto/internal/skcipher.h:95
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8154ce9f)
Location: include/crypto/internal/skcipher.h:95
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
In crypto/cts.c (ffffffff815523a9)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff815532f5)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff815538b1)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81554e32)
Location: include/crypto/internal/skcipher.h:96
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
In crypto/cts.c (ffffffff815b33a9)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff815b4325)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff815b48e1)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff815b5e62)
Location: include/crypto/internal/skcipher.h:96
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
In crypto/cts.c (ffffffff8165c3af)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8165d1b9)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff8165d7d4)
Location: include/crypto/internal/skcipher.h:96
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff8165f0e9)
Location: include/crypto/internal/skcipher.h:96
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
In crypto/cts.c (ffffffff81715d8f)
Location: include/crypto/internal/skcipher.h:104
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81716ca9)
Location: include/crypto/internal/skcipher.h:104
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81717354)
Location: include/crypto/internal/skcipher.h:104
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81719079)
Location: include/crypto/internal/skcipher.h:104
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
In crypto/cts.c (ffffffff8175163f)
Location: include/crypto/internal/skcipher.h:104
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff81752557)
Location: include/crypto/internal/skcipher.h:104
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81752c64)
Location: include/crypto/internal/skcipher.h:104
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff817549f9)
Location: include/crypto/internal/skcipher.h:104
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffffffff817934c1)
Location: include/crypto/internal/skcipher.h:141
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff8179454a)
Location: include/crypto/internal/skcipher.h:141
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81794c06)
Location: include/crypto/internal/skcipher.h:141
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff81796728)
Location: include/crypto/internal/skcipher.h:141
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
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
In crypto/cts.c (ffff8000105c97a4)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffff8000105ca6fc)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffff8000105cae40)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (ffff8000105cc120)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cts.c (c0777330)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (c0778310)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (c07789fc)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (c0779a54)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cts.c (c000000000753eb8)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (c000000000755804)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (c000000000755e38)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (c000000000758dd4)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cts.c (ffffffe00040e46c)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffe00040ee4c)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffe00040f554)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (ffffffe0004113b8)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cts.c (ffffffff814c5e9b)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffff814c7064)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffff814c75a1)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (ffffffff814c8e80)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cts.c (ffffffff814b68bb)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffff814b7a84)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffff814b7fc1)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (ffffffff814b98a0)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cts.c (ffffffff814c1f2b)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffff814c30f4)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffff814c3631)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (ffffffff814c4f10)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
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
In crypto/cts.c (ffffffff814da9fb)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/cts.c:crypto_cts_free
```
```
In crypto/xts.c (ffffffff814dbbc4)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/xts.c:create
  - crypto/xts.c:free
```
```
In crypto/ctr.c (ffffffff814dc101)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/ctr.c:crypto_rfc3686_free
```
```
In crypto/gcm.c (ffffffff814dd9e0)
Location: include/crypto/internal/skcipher.h:100
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
  - crypto/gcm.c:crypto_gcm_free
```
</details>
</li>
</ul>

## Differences
