# Function: <code>blkdev_nr_zones</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814cba80)
Location: block/blk-zoned.c:85
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffff814cba80-ffffffff814cbac9: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814fa720)
Location: block/blk-zoned.c:89
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffff814fa720-ffffffff814fa76a: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81518680)
Location: block/blk-zoned.c:89
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffff81518680-ffffffff815186ca: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815786c0)
Location: block/blk-zoned.c:126
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff815786c0-ffffffff81578701: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815950b0)
Location: block/blk-zoned.c:126
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff815950b0-ffffffff815950fa: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159be70)
Location: block/blk-zoned.c:118
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8159be70-ffffffff8159beb8: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int blkdev_nr_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:118
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
**Symbols:**

```
ffffffff81cda319-ffffffff81cda346: blkdev_nr_zones.cold (STB_LOCAL)
ffffffff81604250-ffffffff8160429b: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int blkdev_nr_zones(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:117
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
**Symbols:**

```
ffffffff81e8de80-ffffffff81e8deb9: blkdev_nr_zones.cold (STB_LOCAL)
ffffffff816b7940-ffffffff816b799b: blkdev_nr_zones (STB_GLOBAL)
```
</details>
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
unsigned int blkdev_nr_zones(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff80001061ffe0)
Location: block/blk-zoned.c:89
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffff80001061ffe0-ffff800010620058: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c7b50)
Location: block/blk-zoned.c:89
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
c07c7b50-c07c7bcc: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007bf700)
Location: block/blk-zoned.c:89
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
c0000000007bf700-c0000000007bf758: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe000452844)
Location: block/blk-zoned.c:89
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffe000452844-ffffffe0004528d2: blkdev_nr_zones (STB_GLOBAL)
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
unsigned int blkdev_nr_zones(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81510c60)
Location: block/blk-zoned.c:89
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffff81510c60-ffffffff81510caa: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81500f80)
Location: block/blk-zoned.c:89
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffff81500f80-ffffffff81500fca: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150ccf0)
Location: block/blk-zoned.c:89
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffff8150ccf0-ffffffff8150cd3a: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int blkdev_nr_zones(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815263d0)
Location: block/blk-zoned.c:89
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - block/blk-zoned.c:blkdev_report_zones_ioctl
```
**Symbols:**

```
ffffffff815263d0-ffffffff8152641a: blkdev_nr_zones (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
