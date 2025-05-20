# Function: <code>bdi_get</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e14d9)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff8125355c)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/block_dev.c (ffffffff81292229)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffff811f74f9)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff8127565c)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/block_dev.c (ffffffff812b4ffb)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffff81218909)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff8129bf2c)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/block_dev.c (ffffffff812dd2a0)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffff8122b669)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff812b0fbc)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/block_dev.c (ffffffff812f2751)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffff8123b2ce)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff812cd95c)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super
```
```
In fs/block_dev.c (ffffffff81314190)
Location: include/linux/backing-dev.h:21
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffff812494c5)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff812df380)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff81327964)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffff812777a2)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff81316766)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff81360c65)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffff81281e52)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff81322197)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff8136ded1)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/fuse/inode.c (ffffffff81499bcd)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
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
In mm/backing-dev.c (ffffffff81286e12)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff81328257)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff8137486b)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In fs/fuse/inode.c (ffffffff8149edfd)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
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
In mm/backing-dev.c (ffffffff812c63c2)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff8137582e)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/fuse/inode.c (ffffffff814f64d2)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
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
In mm/backing-dev.c (ffffffff813243cd)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In fs/super.c (ffffffff813f4d5e)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/fuse/inode.c (ffffffff815862f0)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
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
In mm/backing-dev.c (ffffffff81398ced)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In fs/super.c (ffffffff8147deae)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/fuse/inode.c (ffffffff8162c55e)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
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
In mm/backing-dev.c (ffffffff813cbc4d)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In fs/super.c (ffffffff814b2c3b)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/fuse/inode.c (ffffffff8166478c)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
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
In mm/backing-dev.c (ffffffff813f65bd)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:cgwb_create
```
```
In fs/super.c (ffffffff814e40e3)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - fs/super.c:setup_bdev_super
```
```
In fs/fuse/inode.c (ffffffff8169ea1c)
Location: include/linux/backing-dev.h:20
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_submount
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
In mm/backing-dev.c (ffff8000102deb54)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffff800010386018)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffff8000103e286c)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (c0503b74)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (c056eed4)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (c05baab8)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In drivers/mtd/mtdsuper.c (c0a9115c)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - drivers/mtd/mtdsuper.c:mtd_set_super
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
In mm/backing-dev.c (c00000000039e494)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (c00000000047be50)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (c0000000004e8594)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffe0001f6a86)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffe0002588e0)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffe000298d66)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffff81241b15)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff812d7960)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff8131ff44)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffff81234b05)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff812c85e0)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff81310ae4)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffff8123f8b5)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff812d5770)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff8131da14)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
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
In mm/backing-dev.c (ffffffff8124f035)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_get_by_id
  - mm/backing-dev.c:wb_init
```
```
In fs/super.c (ffffffff812e65c0)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
```
In fs/block_dev.c (ffffffff8132f714)
Location: include/linux/backing-dev.h:22
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
</details>
</li>
</ul>

## Differences
