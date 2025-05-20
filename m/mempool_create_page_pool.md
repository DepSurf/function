# Function: <code>mempool_create_page_pool</code>

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
In fs/ext4/crypto.c (ffffffff812e5392)
Location: include/linux/mempool.h:69
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_init_crypto
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
In fs/crypto/crypto.c (ffffffff812888f4)
Location: include/linux/mempool.h:70
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8129dd0b)
Location: include/linux/mempool.h:70
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812ac7ad)
Location: include/linux/mempool.h:70
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812cffc1)
Location: include/linux/mempool.h:71
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812fa362)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
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
In fs/crypto/crypto.c (ffffffff8130f6b2)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In drivers/scsi/sd.c (ffffffff828e6fcc)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff81336b73)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In drivers/scsi/sd.c (ffffffff829017ff)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff8134a6f3)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In drivers/scsi/sd.c (ffffffff8290aa19)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff8138feba)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In block/blk-crypto-fallback.c (ffffffff8158213f)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In drivers/scsi/sd.c (ffffffff82d204bf)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff813a14fa)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In block/blk-crypto-fallback.c (ffffffff8159f10f)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In drivers/scsi/sd.c (ffffffff8300e29a)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff813a868a)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In block/blk-crypto-fallback.c (ffffffff815a5f3f)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In drivers/scsi/sd.c (ffffffff83219137)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff813f7dca)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In block/blk-crypto-fallback.c (ffffffff8160ea5b)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In drivers/scsi/sd.c (ffffffff83302c0d)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff8146aaed)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In block/blk-crypto-fallback.c (ffffffff816c31f3)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In drivers/scsi/sd.c (ffffffff834bbe8e)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff814fbaad)
Location: include/linux/mempool.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In block/blk-crypto-fallback.c (ffffffff81784674)
Location: include/linux/mempool.h:110
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In drivers/scsi/sd.c (ffffffff83efa057)
Location: include/linux/mempool.h:110
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff81532ddc)
Location: include/linux/mempool.h:110
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In block/blk-crypto-fallback.c (ffffffff817c49df)
Location: include/linux/mempool.h:110
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In drivers/scsi/sd.c (ffffffff8371fdd9)
Location: include/linux/mempool.h:110
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff81567cdc)
Location: include/linux/mempool.h:111
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In block/blk-crypto-fallback.c (ffffffff818096ce)
Location: include/linux/mempool.h:111
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In drivers/scsi/sd.c (ffffffff839537a9)
Location: include/linux/mempool.h:111
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffff80001040af08)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In drivers/scsi/sd.c (ffff80001149a250)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (c05d8094)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In drivers/scsi/sd.c (c159afc8)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (c000000000517948)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In drivers/scsi/sd.c (c0000000013adfc0)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffe0002b4c40)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In drivers/scsi/sd.c (ffffffe000033694)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff81342cd3)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In drivers/scsi/sd.c (ffffffff828f1dbe)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff813339b3)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In drivers/scsi/sd.c (ffffffff828e9269)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff813407a3)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In drivers/scsi/sd.c (ffffffff82905e14)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
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
In fs/crypto/crypto.c (ffffffff81353aa3)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_initialize
```
```
In drivers/scsi/sd.c (ffffffff8290ba7b)
Location: include/linux/mempool.h:105
Inline: True
Inline callers:
  - drivers/scsi/sd.c:init_sd
```
</details>
</li>
</ul>

## Differences
