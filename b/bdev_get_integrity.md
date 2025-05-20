# Function: <code>bdev_get_integrity</code>

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
In fs/block_dev.c (0)
Location: include/linux/blkdev.h:1514
Inline: True
```
```
In block/bio-integrity.c (ffffffff813e6f1b)
Location: include/linux/blkdev.h:1514
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_enabled
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_verify_fn
```
```
In drivers/md/md.c (ffffffff8168d956)
Location: include/linux/blkdev.h:1514
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (0)
Location: include/linux/blkdev.h:1543
Inline: True
```
```
In block/bio-integrity.c (ffffffff8142d60f)
Location: include/linux/blkdev.h:1543
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_enabled
```
```
In drivers/md/md.c (ffffffff816eefba)
Location: include/linux/blkdev.h:1543
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (0)
Location: include/linux/blkdev.h:1768
Inline: True
```
```
In block/bio-integrity.c (ffffffff814473ef)
Location: include/linux/blkdev.h:1768
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_enabled
```
```
In drivers/md/md.c (ffffffff8172110a)
Location: include/linux/blkdev.h:1768
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (0)
Location: include/linux/blkdev.h:1818
Inline: True
```
```
In block/bio-integrity.c (ffffffff814554c9)
Location: include/linux/blkdev.h:1818
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_trim
  - block/bio-integrity.c:bio_integrity_advance
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_process
```
```
In drivers/md/md.c (ffffffff817381ba)
Location: include/linux/blkdev.h:1818
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff812b368d)
Location: include/linux/blkdev.h:1833
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff817aa9d4)
Location: include/linux/blkdev.h:1833
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff812db55b)
Location: include/linux/blkdev.h:1838
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff817f29e0)
Location: include/linux/blkdev.h:1838
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff812f0aab)
Location: include/linux/blkdev.h:1520
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff8181e8e0)
Location: include/linux/blkdev.h:1520
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff8131241b)
Location: include/linux/blkdev.h:1529
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff81860db0)
Location: include/linux/blkdev.h:1529
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff8132536b)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff818929e0)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff8136189b)
Location: include/linux/blkdev.h:1584
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff81960bd0)
Location: include/linux/blkdev.h:1584
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff8136e635)
Location: include/linux/blkdev.h:1698
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff819674dd)
Location: include/linux/blkdev.h:1698
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff81374f3b)
Location: include/linux/blkdev.h:1695
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff8194b74d)
Location: include/linux/blkdev.h:1695
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In block/bdev.c (ffffffff815c491b)
Location: include/linux/blkdev.h:1686
Inline: True
Inline callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff819f090e)
Location: include/linux/blkdev.h:1686
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In block/bdev.c (ffffffff8166f348)
Location: include/linux/blk-integrity.h:57
Inline: True
Inline callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff81b59a58)
Location: include/linux/blk-integrity.h:57
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In block/bdev.c (ffffffff8172a6c8)
Location: include/linux/blk-integrity.h:57
Inline: True
Inline callers:
  - block/bdev.c:bdev_write_page
  - block/bdev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff81cf1608)
Location: include/linux/blk-integrity.h:57
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d59a02)
Location: include/linux/blk-integrity.h:57
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e10ac2)
Location: include/linux/blk-integrity.h:57
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffff8000103df9a8)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffff800010ae41dc)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (c05b7c74)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (c0bc7368)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (c0000000004e4958)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (c000000000bceed4)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffe000296760)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffe0006db244)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff8131d94b)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff81838860)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff8130e4eb)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff817ffed0)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff8131b41b)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff81887e90)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
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
In fs/block_dev.c (ffffffff8132d0bb)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_write_page
  - fs/block_dev.c:bdev_read_page
```
```
In drivers/md/md.c (ffffffff818a4a00)
Location: include/linux/blkdev.h:1560
Inline: True
Inline callers:
  - drivers/md/md.c:md_integrity_register
```
</details>
</li>
</ul>

## Differences
