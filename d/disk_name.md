# Function: <code>disk_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff813cd120)
Location: block/partition-generic.c:34
Inline: True
Direct callers:
  - fs/block_dev.c:flush_disk
  - fs/block_dev.c:check_disk_size_change
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff813cd120-ffffffff813cd1c1: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81411560)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff81411560-ffffffff81411601: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff8142c900)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff8142c900-ffffffff8142c9a0: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81439c10)
Location: block/partition-generic.c:34
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff81439c10-ffffffff81439cb0: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81465c30)
Location: block/partition-generic.c:35
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff81465c30-ffffffff81465cd0: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff81499600)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff81499600-ffffffff814996a0: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814b3860)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff814b3860-ffffffff814b3900: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e1df0)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff814e1df0-ffffffff814e1e8f: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814fb1b0)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff814fb1b0-ffffffff814fb24f: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff8155a033)
Location: block/genhd.c:77
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:bdevname
Direct callers:
  - block/bio.c:bio_devname
  - block/blk-settings.c:disk_stack_limits
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdevname
  - block/partitions/core.c:check_partition
```
**Symbols:**

```
ffffffff81559690-ffffffff81559702: disk_name.part.0 (STB_LOCAL)
ffffffff8155a780-ffffffff8155a7c1: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff815767f3)
Location: block/genhd.c:94
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:bdevname
Direct callers:
  - block/bio.c:bio_devname
  - block/blk-settings.c:disk_stack_limits
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdevname
  - block/partitions/core.c:check_partition
```
**Symbols:**

```
ffffffff81575f30-ffffffff81575fb7: disk_name.part.0 (STB_LOCAL)
ffffffff81bf286f-ffffffff81bf2887: disk_name.part.0.cold (STB_LOCAL)
ffffffff81576b90-ffffffff81576bd1: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff8157e56a)
Location: block/genhd.c:91
Inline: True
Inline callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:bdevname
Direct callers:
  - block/blk-settings.c:disk_stack_limits
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:bdevname
  - block/partitions/core.c:check_partition
```
**Symbols:**

```
ffffffff8157ddb0-ffffffff8157de37: disk_name.part.0 (STB_LOCAL)
ffffffff81be4835-ffffffff81be484d: disk_name.part.0.cold (STB_LOCAL)
ffffffff8157eb40-ffffffff8157eb81: disk_name (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffff8000105fd148)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffff8000105fd148-ffff8000105fd214: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c07a80ac)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
c07a80ac-c07a8148: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (c0000000007968e0)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
c0000000007968e0-c0000000007969f4: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffe000438dc0)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffe000438dc0-ffffffe000438e64: disk_name (STB_GLOBAL)
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
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814f3790)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff814f3790-ffffffff814f382f: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814e3ca0)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff814e3ca0-ffffffff814e3d3f: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff814ef820)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff814ef820-ffffffff814ef8bf: disk_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
char *disk_name(struct gendisk *hd, int partno, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/partition-generic.c (ffffffff815088b0)
Location: block/partition-generic.c:35
Inline: True
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/partition-generic.c:bio_devname
  - block/partition-generic.c:bdevname
  - block/partitions/check.c:check_partition
```
**Symbols:**

```
ffffffff815088b0-ffffffff8150894f: disk_name (STB_GLOBAL)
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
