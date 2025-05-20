# Function: <code>rescan_partitions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff813cd840)
Location: block/partition-generic.c:421
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff813cd840-ffffffff813cdae8: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81411c70)
Location: block/partition-generic.c:433
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff81411c70-ffffffff81411f18: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff8142d000)
Location: block/partition-generic.c:483
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff8142d000-ffffffff8142d37a: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff8143a320)
Location: block/partition-generic.c:484
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff8143a320-ffffffff8143a66a: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81466340)
Location: block/partition-generic.c:496
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff81466340-ffffffff8146668d: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partition-generic.c (0)
Location: block/partition-generic.c:502
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff81499f9d-ffffffff8149a06c: rescan_partitions.cold.20 (STB_LOCAL)
ffffffff81499c20-ffffffff81499ead: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partition-generic.c (0)
Location: block/partition-generic.c:505
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff814b42ad-ffffffff814b437c: rescan_partitions.cold.20 (STB_LOCAL)
ffffffff814b3f30-ffffffff814b41bd: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partition-generic.c (0)
Location: block/partition-generic.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff814e278f-ffffffff814e2892: rescan_partitions.cold (STB_LOCAL)
ffffffff814e2420-ffffffff814e269f: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partition-generic.c (0)
Location: block/partition-generic.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff814fbb4f-ffffffff814fbc52: rescan_partitions.cold (STB_LOCAL)
ffffffff814fb7e0-ffffffff814fba5f: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffff8000105fd778)
Location: block/partition-generic.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffff8000105fd778-ffff8000105fdb28: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c07a8620)
Location: block/partition-generic.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
c07a8620-c07a8abc: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c000000000797100)
Location: block/partition-generic.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
c000000000797100-c000000000797568: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffe000439312)
Location: block/partition-generic.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffe000439312-ffffffe0004395c6: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partition-generic.c (0)
Location: block/partition-generic.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff814f412f-ffffffff814f4232: rescan_partitions.cold (STB_LOCAL)
ffffffff814f3dc0-ffffffff814f403f: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partition-generic.c (0)
Location: block/partition-generic.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff814e463f-ffffffff814e4742: rescan_partitions.cold (STB_LOCAL)
ffffffff814e42d0-ffffffff814e454f: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partition-generic.c (0)
Location: block/partition-generic.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff814f01bf-ffffffff814f02c2: rescan_partitions.cold (STB_LOCAL)
ffffffff814efe50-ffffffff814f00cf: rescan_partitions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rescan_partitions(struct gendisk *disk, struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partition-generic.c (0)
Location: block/partition-generic.c:512
Inline: False
Direct callers:
  - fs/block_dev.c:bdev_disk_changed
  - block/ioctl.c:__blkdev_reread_part
```
**Symbols:**

```
ffffffff8150924f-ffffffff81509352: rescan_partitions.cold (STB_LOCAL)
ffffffff81508ee0-ffffffff8150915f: rescan_partitions (STB_GLOBAL)
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
