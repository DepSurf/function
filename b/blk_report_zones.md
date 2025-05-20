# Function: <code>blk_report_zones</code>

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
int blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814cb5e0)
Location: block/blk-zoned.c:118
Inline: False
Direct callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
```
**Symbols:**

```
ffffffff814cb5e0-ffffffff814cb6ed: blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:122
Inline: False
Direct callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
```
**Symbols:**

```
ffffffff814f9f50-ffffffff814fa050: blk_report_zones (STB_LOCAL)
ffffffff814faafe-ffffffff814fab11: blk_report_zones.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81517e20)
Location: block/blk-zoned.c:122
Inline: False
Direct callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
```
**Symbols:**

```
ffffffff81517e20-ffffffff81517f20: blk_report_zones (STB_LOCAL)
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
int blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff80001061f448)
Location: block/blk-zoned.c:122
Inline: False
Direct callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
```
**Symbols:**

```
ffff80001061f448-ffff80001061f558: blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c6e5c)
Location: block/blk-zoned.c:122
Inline: False
Direct callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
```
**Symbols:**

```
c07c6e5c-c07c6fb8: blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007beb80)
Location: block/blk-zoned.c:122
Inline: False
Direct callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
```
**Symbols:**

```
c0000000007beb80-c0000000007bed24: blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe000451fd4)
Location: block/blk-zoned.c:122
Inline: False
Direct callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
```
**Symbols:**

```
ffffffe000451fd4-ffffffe000452096: blk_report_zones (STB_LOCAL)
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
int blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81510400)
Location: block/blk-zoned.c:122
Inline: False
Direct callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
```
**Symbols:**

```
ffffffff81510400-ffffffff81510500: blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81500720)
Location: block/blk-zoned.c:122
Inline: False
Direct callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
```
**Symbols:**

```
ffffffff81500720-ffffffff81500820: blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150c490)
Location: block/blk-zoned.c:122
Inline: False
Direct callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
```
**Symbols:**

```
ffffffff8150c490-ffffffff8150c590: blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81525b70)
Location: block/blk-zoned.c:122
Inline: False
Direct callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
```
**Symbols:**

```
ffffffff81525b70-ffffffff81525c70: blk_report_zones (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
