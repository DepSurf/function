# Function: <code>disk_get_part</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813c9950)
Location: block/genhd.c:61
Inline: True
Inline callers:
  - block/genhd.c:bdget_disk
  - block/genhd.c:blk_lookup_devt
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff813c9950-ffffffff813c998b: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140e4cc)
Location: block/genhd.c:62
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff8140dbc0-ffffffff8140dbfe: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8142985c)
Location: block/genhd.c:62
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
Direct callers:
  - init/do_mounts.c:name_to_dev_t
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff81428f50-ffffffff81428f8e: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81437bac)
Location: block/genhd.c:62
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff81437290-ffffffff814372d3: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814639bc)
Location: block/genhd.c:108
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff81463050-ffffffff81463093: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814973c0)
Location: block/genhd.c:120
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff81496990-ffffffff814969d3: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b12e0)
Location: block/genhd.c:133
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff814b08b0-ffffffff814b08f3: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814decd0)
Location: block/genhd.c:134
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff814decd0-ffffffff814ded18: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f8110)
Location: block/genhd.c:134
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff814f8110-ffffffff814f8158: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155b17b)
Location: block/genhd.c:171
Inline: True
Inline callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
```
**Symbols:**

```
ffffffff8155a800-ffffffff8155a847: disk_get_part (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105f9350)
Location: block/genhd.c:134
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffff8000105f9350-ffff8000105f93c0: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a45ec)
Location: block/genhd.c:134
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
c07a45ec-c07a4644: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000791960)
Location: block/genhd.c:134
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
c000000000791960-c0000000007919f4: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000435b30)
Location: block/genhd.c:134
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffe000435b30-ffffffe000435b90: disk_get_part (STB_GLOBAL)
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
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f06f0)
Location: block/genhd.c:134
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff814f06f0-ffffffff814f0738: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e0c30)
Location: block/genhd.c:134
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff814e0c30-ffffffff814e0c78: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ec780)
Location: block/genhd.c:134
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff814ec780-ffffffff814ec7c8: disk_get_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hd_struct *disk_get_part(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815057c0)
Location: block/genhd.c:134
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff815057c0-ffffffff8150581e: disk_get_part (STB_GLOBAL)
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
