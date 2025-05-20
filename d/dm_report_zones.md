# Function: <code>dm_report_zones</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_report_zones(struct block_device *bdev, sector_t start, sector_t sector, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81a05480)
Location: drivers/md/dm-zone.c:110
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81a05480-ffffffff81a054a7: dm_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_report_zones(struct block_device *bdev, sector_t start, sector_t sector, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81b6d220)
Location: drivers/md/dm-zone.c:110
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81b6d220-ffffffff81b6d256: dm_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_report_zones(struct block_device *bdev, sector_t start, sector_t sector, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d09530)
Location: drivers/md/dm-zone.c:110
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81d09530-ffffffff81d09566: dm_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_report_zones(struct block_device *bdev, sector_t start, sector_t sector, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d726a0)
Location: drivers/md/dm-zone.c:111
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81d726a0-ffffffff81d726d6: dm_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_report_zones(struct block_device *bdev, sector_t start, sector_t sector, struct dm_report_zones_args *args, unsigned int nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81e29730)
Location: drivers/md/dm-zone.c:111
Inline: False
Direct callers:
  - drivers/md/dm-target.c:io_err_report_zones
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81e29730-ffffffff81e29766: dm_report_zones (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
