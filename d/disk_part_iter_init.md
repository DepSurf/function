# Function: <code>disk_part_iter_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813c9810)
Location: block/genhd.c:95
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:add_disk
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff813c9810-ffffffff813c984b: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140dfd9)
Location: block/genhd.c:96
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff8140da90-ffffffff8140dacb: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81429369)
Location: block/genhd.c:96
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff81428e20-ffffffff81428e5b: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8143764c)
Location: block/genhd.c:96
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff81437130-ffffffff8143716b: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8146342c)
Location: block/genhd.c:133
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff81462ef0-ffffffff81462f2b: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81496d4c)
Location: block/genhd.c:145
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff81496830-ffffffff8149686b: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b0c6c)
Location: block/genhd.c:158
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff814b0750-ffffffff814b078b: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814df09c)
Location: block/genhd.c:159
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff814deb70-ffffffff814debab: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f84cc)
Location: block/genhd.c:159
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff814f7fb0-ffffffff814f7feb: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81558d4c)
Location: block/genhd.c:195
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:register_disk
Direct callers:
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:partition_overlaps
```
**Symbols:**

```
ffffffff81558ad0-ffffffff81558b0b: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81576330)
Location: block/genhd.c:185
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:register_disk
Direct callers:
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:partition_overlaps
```
**Symbols:**

```
ffffffff815751b0-ffffffff815751f5: disk_part_iter_init (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105f985c)
Location: block/genhd.c:159
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffff8000105f90c0-ffff8000105f9130: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a5894)
Location: block/genhd.c:159
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
c07a4438-c07a448c: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000792144)
Location: block/genhd.c:159
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
c000000000791710-c00000000079177c: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000435f36)
Location: block/genhd.c:159
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffe00043590a-ffffffe000435984: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f0aac)
Location: block/genhd.c:159
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff814f0590-ffffffff814f05cb: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e0fec)
Location: block/genhd.c:159
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff814e0ad0-ffffffff814e0b0b: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ecb3c)
Location: block/genhd.c:159
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff814ec620-ffffffff814ec65b: disk_part_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void disk_part_iter_init(struct disk_part_iter *piter, struct gendisk *disk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81505b9c)
Location: block/genhd.c:159
Inline: True
Inline callers:
  - block/genhd.c:set_disk_ro
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:__device_add_disk
Direct callers:
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
```
**Symbols:**

```
ffffffff81505750-ffffffff815057b6: disk_part_iter_init (STB_GLOBAL)
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
