# Function: <code>dm_blk_report_zones</code>

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
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81832bc0)
Location: drivers/md/dm.c:461
Inline: False
```
**Symbols:**

```
ffffffff81832bc0-ffffffff81832c80: dm_blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:443
Inline: False
```
**Symbols:**

```
ffffffff81877ba0-ffffffff81877c6a: dm_blk_report_zones (STB_LOCAL)
ffffffff8187960e-ffffffff81879627: dm_blk_report_zones.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a9400)
Location: drivers/md/dm.c:443
Inline: False
```
**Symbols:**

```
ffffffff818a9400-ffffffff818a94cf: dm_blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81978da0)
Location: drivers/md/dm.c:478
Inline: False
```
**Symbols:**

```
ffffffff81978da0-ffffffff81978eb8: dm_blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197df40)
Location: drivers/md/dm.c:473
Inline: False
```
**Symbols:**

```
ffffffff8197df40-ffffffff8197e064: dm_blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81961cf0)
Location: drivers/md/dm.c:478
Inline: False
```
**Symbols:**

```
ffffffff81961cf0-ffffffff81961e14: dm_blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81a05a60)
Location: drivers/md/dm-zone.c:55
Inline: False
```
**Symbols:**

```
ffffffff81a05a60-ffffffff81a05b12: dm_blk_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81b6d750)
Location: drivers/md/dm-zone.c:55
Inline: False
```
**Symbols:**

```
ffffffff81b6d750-ffffffff81b6d81a: dm_blk_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d09b10)
Location: drivers/md/dm-zone.c:55
Inline: False
```
**Symbols:**

```
ffffffff81d09b10-ffffffff81d09bda: dm_blk_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d72c60)
Location: drivers/md/dm-zone.c:56
Inline: False
```
**Symbols:**

```
ffffffff81d72c60-ffffffff81d72d2a: dm_blk_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81e29d40)
Location: drivers/md/dm-zone.c:56
Inline: False
```
**Symbols:**

```
ffffffff81e29d40-ffffffff81e29e0a: dm_blk_report_zones (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afd840)
Location: drivers/md/dm.c:443
Inline: False
```
**Symbols:**

```
ffff800010afd840-ffff800010afd918: dm_blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdf4f8)
Location: drivers/md/dm.c:443
Inline: False
```
**Symbols:**

```
c0bdf4f8-c0bdf614: dm_blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000beea50)
Location: drivers/md/dm.c:443
Inline: False
```
**Symbols:**

```
c000000000beea50-c000000000beeb98: dm_blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ef892)
Location: drivers/md/dm.c:443
Inline: False
```
**Symbols:**

```
ffffffe0006ef892-ffffffe0006ef938: dm_blk_report_zones (STB_LOCAL)
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
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184f280)
Location: drivers/md/dm.c:443
Inline: False
```
**Symbols:**

```
ffffffff8184f280-ffffffff8184f34f: dm_blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81816890)
Location: drivers/md/dm.c:443
Inline: False
```
**Symbols:**

```
ffffffff81816890-ffffffff8181695f: dm_blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189e8b0)
Location: drivers/md/dm.c:443
Inline: False
```
**Symbols:**

```
ffffffff8189e8b0-ffffffff8189e97f: dm_blk_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dm_blk_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bb1b0)
Location: drivers/md/dm.c:443
Inline: False
```
**Symbols:**

```
ffffffff818bb1b0-ffffffff818bb27f: dm_blk_report_zones (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>report_zones_cb cb</code>
</li>
<li>
<b>Param added. </b>
<code>void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_zone *zones</code>
</li>
<li>
<b>Param reordered. </b>
<code>disk, sector, zones, nr_zones</code> ➡️ <code>disk, sector, nr_zones, cb, data</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int *nr_zones</code> ➡️ <code>unsigned int nr_zones</code>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
