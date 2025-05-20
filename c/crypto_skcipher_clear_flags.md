# Function: <code>crypto_skcipher_clear_flags</code>

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
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:342
Inline: True
```
```
In crypto/cts.c (ffffffff813e7743)
Location: include/crypto/skcipher.h:342
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/ctr.c (ffffffff813e8839)
Location: include/crypto/skcipher.h:342
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:342
Inline: True
```
```
In crypto/cts.c (ffffffff81400573)
Location: include/crypto/skcipher.h:342
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8140136d)
Location: include/crypto/skcipher.h:342
Inline: True
```
```
In crypto/ctr.c (ffffffff81401e49)
Location: include/crypto/skcipher.h:342
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:376
Inline: True
```
```
In crypto/cts.c (ffffffff8140d873)
Location: include/crypto/skcipher.h:376
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8140e5fd)
Location: include/crypto/skcipher.h:376
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff8140f294)
Location: include/crypto/skcipher.h:376
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
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
In fs/crypto/keyinfo.c (0)
Location: include/crypto/skcipher.h:376
Inline: True
```
```
In crypto/cts.c (ffffffff81436303)
Location: include/crypto/skcipher.h:376
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814370c2)
Location: include/crypto/skcipher.h:376
Inline: True
Inline callers:
  - crypto/xts.c:setkey
```
```
In crypto/ctr.c (ffffffff81437e64)
Location: include/crypto/skcipher.h:376
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8143a391)
Location: include/crypto/skcipher.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff8145d3ed)
Location: include/crypto/skcipher.h:376
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
```
```
In crypto/cts.c (ffffffff81468e53)
Location: include/crypto/skcipher.h:376
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81469aed)
Location: include/crypto/skcipher.h:376
Inline: True
```
```
In crypto/ctr.c (ffffffff8146a7c4)
Location: include/crypto/skcipher.h:376
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8146cd41)
Location: include/crypto/skcipher.h:376
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff8147ac6d)
Location: include/crypto/skcipher.h:395
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff81486ad3)
Location: include/crypto/skcipher.h:395
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814879bd)
Location: include/crypto/skcipher.h:395
Inline: True
```
```
In crypto/ctr.c (ffffffff81488024)
Location: include/crypto/skcipher.h:395
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff81489318)
Location: include/crypto/skcipher.h:395
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff814a9bfd)
Location: include/crypto/skcipher.h:330
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814b4940)
Location: include/crypto/skcipher.h:330
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b56d1)
Location: include/crypto/skcipher.h:330
Inline: True
```
```
In crypto/ctr.c (ffffffff814b5ab4)
Location: include/crypto/skcipher.h:330
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b6f61)
Location: include/crypto/skcipher.h:330
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff814c48ed)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814cd6b0)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814ce8d1)
Location: include/crypto/skcipher.h:360
Inline: True
```
```
In crypto/ctr.c (ffffffff814cecb4)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814d0181)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff81522930)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff8152cb1d)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8152dbdf)
Location: include/crypto/skcipher.h:322
Inline: True
```
```
In crypto/ctr.c (ffffffff8152e06b)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff815301f4)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff8153f7f0)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff81549b8d)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8154abaf)
Location: include/crypto/skcipher.h:322
Inline: True
```
```
In crypto/ctr.c (ffffffff8154b08b)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8154d144)
Location: include/crypto/skcipher.h:322
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff81547d80)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff815521dd)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff815531cf)
Location: include/crypto/skcipher.h:324
Inline: True
```
```
In crypto/ctr.c (ffffffff815536ab)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff815550c1)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff815a8560)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff815b31dd)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff815b41ff)
Location: include/crypto/skcipher.h:324
Inline: True
```
```
In crypto/ctr.c (ffffffff815b46db)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff815b60f1)
Location: include/crypto/skcipher.h:324
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff8164fed0)
Location: include/crypto/skcipher.h:328
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff8165c1ad)
Location: include/crypto/skcipher.h:328
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8165d069)
Location: include/crypto/skcipher.h:328
Inline: True
```
```
In crypto/ctr.c (ffffffff8165d59b)
Location: include/crypto/skcipher.h:328
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff8165f3a1)
Location: include/crypto/skcipher.h:328
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff81709600)
Location: include/crypto/skcipher.h:328
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff81715b4d)
Location: include/crypto/skcipher.h:328
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff81716b49)
Location: include/crypto/skcipher.h:328
Inline: True
```
```
In crypto/ctr.c (ffffffff817171db)
Location: include/crypto/skcipher.h:328
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff817187d1)
Location: include/crypto/skcipher.h:328
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff81742e40)
Location: include/crypto/skcipher.h:350
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff817513fd)
Location: include/crypto/skcipher.h:350
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff817523fc)
Location: include/crypto/skcipher.h:350
Inline: True
```
```
In crypto/ctr.c (ffffffff81752aeb)
Location: include/crypto/skcipher.h:350
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff81754141)
Location: include/crypto/skcipher.h:350
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff8178511c)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - crypto/skcipher.c:crypto_skcipher_setkey
```
```
In crypto/cts.c (ffffffff8179324d)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff8179428c)
Location: include/crypto/skcipher.h:575
Inline: True
```
```
In crypto/ctr.c (ffffffff81794a5b)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff81795ab1)
Location: include/crypto/skcipher.h:575
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffff8000105bec0c)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffff8000105c9560)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffff8000105caad0)
Location: include/crypto/skcipher.h:360
Inline: True
```
```
In crypto/ctr.c (ffff8000105cabec)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffff8000105cc65c)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (c076d07c)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (c0777124)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c07786d4)
Location: include/crypto/skcipher.h:360
Inline: True
```
```
In crypto/ctr.c (c07787b8)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c077a538)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (c000000000746f84)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (c000000000753b90)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (c00000000075545c)
Location: include/crypto/skcipher.h:360
Inline: True
```
```
In crypto/ctr.c (c0000000007559cc)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (c000000000757aac)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffe000403dda)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffe00040dd74)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffe00040ecd6)
Location: include/crypto/skcipher.h:360
Inline: True
```
```
In crypto/ctr.c (ffffffe00040f0b4)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffe0004105b6)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff814bcecd)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814c5c90)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c6eb1)
Location: include/crypto/skcipher.h:360
Inline: True
```
```
In crypto/ctr.c (ffffffff814c7294)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c8761)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff814ad8ed)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814b66b0)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814b78d1)
Location: include/crypto/skcipher.h:360
Inline: True
```
```
In crypto/ctr.c (ffffffff814b7cb4)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814b9181)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff814b8f5d)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814c1d20)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814c2f41)
Location: include/crypto/skcipher.h:360
Inline: True
```
```
In crypto/ctr.c (ffffffff814c3324)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814c47f1)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
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
In crypto/skcipher.c (ffffffff814d1a1d)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_setkey
  - crypto/skcipher.c:skcipher_setkey_ablkcipher
  - crypto/skcipher.c:skcipher_setkey_blkcipher
```
```
In crypto/cts.c (ffffffff814da7f0)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_setkey
```
```
In crypto/xts.c (ffffffff814dba11)
Location: include/crypto/skcipher.h:360
Inline: True
```
```
In crypto/ctr.c (ffffffff814dbdf4)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_setkey
```
```
In crypto/gcm.c (ffffffff814dd2c1)
Location: include/crypto/skcipher.h:360
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_setkey
```
</details>
</li>
</ul>

## Differences
