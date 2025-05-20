# Function: <code>mempool_initialized</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/mempool.h:28
Inline: True
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
In block/bio.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/mempool.h:28
Inline: True
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
In block/bio.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/mempool.h:28
Inline: True
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
In block/bio.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/mempool.h:28
Inline: True
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
In block/bio.c (ffffffff8153f0d6)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/bounce.c (ffffffff81566e6e)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:init_emergency_isa_pool
```
```
In block/bio-integrity.c (ffffffff81576ce1)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/bio-integrity.c:bio_integrity_alloc
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
In block/bio.c (ffffffff8155b8c6)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/bounce.c (ffffffff81581c9e)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:init_emergency_isa_pool
```
```
In block/bio-integrity.c (ffffffff815939f1)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/bio-integrity.c:bio_integrity_alloc
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
In block/bio.c (ffffffff81563f30)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/bio-integrity.c (ffffffff8159a7d1)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/bio-integrity.c:bio_integrity_alloc
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
In block/bio.c (ffffffff815c8112)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/bio-integrity.c (ffffffff816029b1)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/bio-integrity.c:bio_integrity_alloc
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
In fs/notify/fanotify/fanotify.c (ffffffff81452a6f)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8145673f)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
```
In block/bio.c (ffffffff81672dfa)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/bio-integrity.c (ffffffff816b4fe5)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio-integrity.c:bioset_integrity_create
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/bio-integrity.c:bio_integrity_alloc
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
In fs/notify/fanotify/fanotify.c (ffffffff814e171f)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e5841)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
```
In block/bio.c (ffffffff8172e91a)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/bio-integrity.c (ffffffff81774b05)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio-integrity.c:bioset_integrity_create
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/bio-integrity.c:bio_integrity_alloc
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
In fs/notify/fanotify/fanotify.c (ffffffff81517fdf)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151c2dd)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
```
In block/bio.c (ffffffff8176ab4a)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/bio-integrity.c (ffffffff817b4825)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio-integrity.c:bioset_integrity_create
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/bio-integrity.c:bio_integrity_alloc
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
In fs/notify/fanotify/fanotify.c (ffffffff8154c3bf)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81550893)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
```
In block/bio.c (ffffffff817acfda)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/bio-integrity.c (ffffffff817f8845)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio-integrity.c:bioset_integrity_create
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
  - block/bio-integrity.c:bio_integrity_alloc
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
In block/bio.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/mempool.h:28
Inline: True
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
In block/bio.c (c0789600)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/bounce.c (c07b39d0)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
  - block/bounce.c:init_emergency_isa_pool
```
```
In block/bio-integrity.c (c07c53ac)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
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
In block/bio.c (c00000000076d0f0)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/bio-integrity.c (c0000000007bc6d4)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
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
In block/bio.c (ffffffe00041f636)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
```
```
In block/bio-integrity.c (ffffffe0004505a8)
Location: include/linux/mempool.h:28
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_alloc
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
In block/bio.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/mempool.h:28
Inline: True
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
In block/bio.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/mempool.h:28
Inline: True
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
In block/bio.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/mempool.h:28
Inline: True
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
In block/bio.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bounce.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/linux/mempool.h:28
Inline: True
```
</details>
</li>
</ul>

## Differences
