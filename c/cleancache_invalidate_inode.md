# Function: <code>cleancache_invalidate_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8119e7c9)
Location: include/linux/cleancache.h:113
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff812473b7)
Location: include/linux/cleancache.h:113
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff811b42b1)
Location: include/linux/cleancache.h:111
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8126fc77)
Location: include/linux/cleancache.h:111
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff811c4921)
Location: include/linux/cleancache.h:111
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff81282e77)
Location: include/linux/cleancache.h:111
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff811cd07f)
Location: include/linux/cleancache.h:111
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff812907c9)
Location: include/linux/cleancache.h:111
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff811e22aa)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff812b3489)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff81203b32)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff812db189)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff81216413)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff812f06d9)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff81225de7)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8131205b)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff81233c46)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff81324fbb)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff8126128d)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8135eb4b)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff8126b68b)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8136c30b)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff812707f2)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff81372c4b)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff812ae47d)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In block/bdev.c (ffffffff815c3b9e)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - block/bdev.c:invalidate_bdev
```
</details>
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
In mm/truncate.c (ffff8000102c4118)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffff8000103df558)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (c04eeb70)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (c05b7880)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (c00000000037e2dc)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (c0000000004e431c)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffe0001e4c5c)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffe0002963b4)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff8122c296)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8131d59b)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff8121f370)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8130e13b)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff8122a036)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8131b06b)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
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
In mm/truncate.c (ffffffff81239423)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8132cd0b)
Location: include/linux/cleancache.h:112
Inline: True
Inline callers:
  - fs/block_dev.c:invalidate_bdev
```
</details>
</li>
</ul>

## Differences
