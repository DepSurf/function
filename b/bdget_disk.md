# Function: <code>bdget_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813ca070)
Location: block/genhd.c:722
Inline: False
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:blkdev_get
  - block/genhd.c:invalidate_partition
  - block/genhd.c:add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff813ca070-ffffffff813ca0d7: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140e2e0)
Location: block/genhd.c:748
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - block/genhd.c:invalidate_partition
  - block/genhd.c:device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8140e2e0-ffffffff8140e347: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81429670)
Location: block/genhd.c:748
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - block/genhd.c:invalidate_partition
  - block/genhd.c:device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81429670-ffffffff814296d7: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814379b0)
Location: block/genhd.c:760
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - block/genhd.c:invalidate_partition
  - block/genhd.c:device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff814379b0-ffffffff81437a17: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814637c0)
Location: block/genhd.c:825
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - block/genhd.c:invalidate_partition
  - block/genhd.c:device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff814637c0-ffffffff81463827: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814971d0)
Location: block/genhd.c:873
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff814971d0-ffffffff81497237: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b10f0)
Location: block/genhd.c:895
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff814b10f0-ffffffff814b1157: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814df310)
Location: block/genhd.c:917
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814df310-ffffffff814df34b: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f8740)
Location: block/genhd.c:926
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814f8740-ffffffff814f877b: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155a180)
Location: block/genhd.c:1030
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - block/genhd.c:invalidate_partition
  - block/genhd.c:register_disk
  - block/partitions/core.c:bdev_del_partition
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_closing
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8155a180-ffffffff8155a1e6: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815773b1)
Location: block/genhd.c:926
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
```
**Symbols:**

```
ffffffff81577120-ffffffff81577166: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157f1a4)
Location: block/genhd.c:708
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
```
**Symbols:**

```
ffffffff8157f0d0-ffffffff8157f11b: bdget_disk (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105f9b40)
Location: block/genhd.c:926
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffff8000105f9b40-ffff8000105f9b98: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a4e08)
Location: block/genhd.c:926
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c07a4e08-c07a4e48: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000792790)
Location: block/genhd.c:926
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c000000000792790-c00000000079281c: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000436302)
Location: block/genhd.c:926
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffe000436302-ffffffe000436366: bdget_disk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f0d20)
Location: block/genhd.c:926
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814f0d20-ffffffff814f0d5b: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e1260)
Location: block/genhd.c:926
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814e1260-ffffffff814e129b: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ecdb0)
Location: block/genhd.c:926
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814ecdb0-ffffffff814ecdeb: bdget_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct block_device *bdget_disk(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81505e20)
Location: block/genhd.c:926
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - block/genhd.c:invalidate_partition
  - block/genhd.c:__device_add_disk
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81505e20-ffffffff81505e5b: bdget_disk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
