# Function: <code>skcipher_instance_ctx</code>

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
In crypto/cts.c (ffffffff813e7ea5)
Location: include/crypto/internal/skcipher.h:52
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/ctr.c (ffffffff813e8eaf)
Location: include/crypto/internal/skcipher.h:52
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
In crypto/cbc.c (ffffffff813fffe4)
Location: include/crypto/internal/skcipher.h:88
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff81400cd5)
Location: include/crypto/internal/skcipher.h:88
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:88
Inline: True
```
```
In crypto/ctr.c (ffffffff814024c0)
Location: include/crypto/internal/skcipher.h:88
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
In crypto/cbc.c (ffffffff8140d2f4)
Location: include/crypto/internal/skcipher.h:88
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff8140dc7d)
Location: include/crypto/internal/skcipher.h:88
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:88
Inline: True
```
```
In crypto/ctr.c (ffffffff8140f5ec)
Location: include/crypto/internal/skcipher.h:88
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
In crypto/cbc.c (ffffffff81435d64)
Location: include/crypto/internal/skcipher.h:88
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff8143671d)
Location: include/crypto/internal/skcipher.h:88
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:88
Inline: True
```
```
In crypto/ctr.c (ffffffff814380ec)
Location: include/crypto/internal/skcipher.h:88
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
In crypto/cbc.c (ffffffff814688e5)
Location: include/crypto/internal/skcipher.h:88
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff81469298)
Location: include/crypto/internal/skcipher.h:88
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:88
Inline: True
```
```
In crypto/ctr.c (ffffffff8146aa80)
Location: include/crypto/internal/skcipher.h:88
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
In crypto/cbc.c (ffffffff81486555)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_init_tfm
```
```
In crypto/cts.c (ffffffff81486c67)
Location: include/crypto/internal/skcipher.h:86
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:86
Inline: True
```
```
In crypto/ctr.c (ffffffff81488301)
Location: include/crypto/internal/skcipher.h:86
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
In crypto/skcipher.c (ffffffff814a9304)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814b4d7d)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (ffffffff814b5d4a)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/skcipher.c (ffffffff814c3f74)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814cd84d)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (ffffffff814cef4a)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/cts.c (ffffffff8152cc62)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (ffffffff8152e239)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/cts.c (ffffffff81549ceb)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (ffffffff8154b214)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/skcipher.h:82
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:82
Inline: True
```
```
In crypto/cts.c (ffffffff8155232b)
Location: include/crypto/internal/skcipher.h:82
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:82
Inline: True
```
```
In crypto/ctr.c (ffffffff8155383a)
Location: include/crypto/internal/skcipher.h:82
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/skcipher.h:82
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:82
Inline: True
```
```
In crypto/cts.c (ffffffff815b332b)
Location: include/crypto/internal/skcipher.h:82
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:82
Inline: True
```
```
In crypto/ctr.c (ffffffff815b486a)
Location: include/crypto/internal/skcipher.h:82
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/skcipher.h:82
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:82
Inline: True
```
```
In crypto/cts.c (ffffffff8165c32e)
Location: include/crypto/internal/skcipher.h:82
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:82
Inline: True
```
```
In crypto/ctr.c (ffffffff8165d75e)
Location: include/crypto/internal/skcipher.h:82
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/skcipher.h:90
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:90
Inline: True
```
```
In crypto/cts.c (ffffffff81715d0e)
Location: include/crypto/internal/skcipher.h:90
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:90
Inline: True
```
```
In crypto/ctr.c (ffffffff817172de)
Location: include/crypto/internal/skcipher.h:90
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/skcipher.h:90
Inline: True
```
```
In crypto/cbc.c (0)
Location: include/crypto/internal/skcipher.h:90
Inline: True
```
```
In crypto/cts.c (ffffffff817515be)
Location: include/crypto/internal/skcipher.h:90
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:90
Inline: True
```
```
In crypto/ctr.c (ffffffff81752bee)
Location: include/crypto/internal/skcipher.h:90
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (0)
Location: include/crypto/internal/skcipher.h:118
Inline: True
```
```
In crypto/cts.c (ffffffff8179343d)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:118
Inline: True
```
```
In crypto/ctr.c (ffffffff81794b8d)
Location: include/crypto/internal/skcipher.h:118
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
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
In crypto/skcipher.c (ffff8000105bea84)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffff8000105c9720)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (ffff8000105cadc0)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/skcipher.c (c076c6c8)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (c07772b4)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (c0778980)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/skcipher.c (c000000000746dd8)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (c000000000753e24)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (c000000000755dc8)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/skcipher.c (ffffffe000403f00)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffe00040e410)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (ffffffe00040f4f4)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/skcipher.c (ffffffff814bc554)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814c5e2d)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (ffffffff814c752a)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/skcipher.c (ffffffff814acf74)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814b684d)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (ffffffff814b7f4a)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/skcipher.c (ffffffff814b85e4)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814c1ebd)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (ffffffff814c35ba)
Location: include/crypto/internal/skcipher.h:81
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
In crypto/skcipher.c (ffffffff814d10c4)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_free_instance_simple
  - crypto/skcipher.c:skcipher_init_tfm_simple
```
```
In crypto/cts.c (ffffffff814da98d)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (0)
Location: include/crypto/internal/skcipher.h:81
Inline: True
```
```
In crypto/ctr.c (ffffffff814dc08a)
Location: include/crypto/internal/skcipher.h:81
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
</details>
</li>
</ul>

## Differences
