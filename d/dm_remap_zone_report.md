# Function: <code>dm_remap_zone_report</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, struct bio *bio, sector_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174c190)
Location: drivers/md/dm.c:1056
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_end_io
```
**Symbols:**

```
ffffffff8174c190-ffffffff8174c3cf: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, struct bio *bio, sector_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817be560)
Location: drivers/md/dm.c:1047
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_end_io
```
**Symbols:**

```
ffffffff817be560-ffffffff817be798: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, struct bio *bio, sector_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81806850)
Location: drivers/md/dm.c:1163
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_end_io
```
**Symbols:**

```
ffffffff81806850-ffffffff81806ade: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, sector_t start, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81832980)
Location: drivers/md/dm.c:1218
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81832980-ffffffff81832a4e: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, sector_t start, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81875160)
Location: drivers/md/dm.c:1223
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff81875160-ffffffff81875214: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, sector_t start, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a6f30)
Location: drivers/md/dm.c:1223
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff818a6f30-ffffffff818a6fe4: dm_remap_zone_report (STB_GLOBAL)
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
void dm_remap_zone_report(struct dm_target *ti, sector_t start, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afc198)
Location: drivers/md/dm.c:1223
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffff800010afc198-ffff800010afc2b4: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, sector_t start, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdc748)
Location: drivers/md/dm.c:1223
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
c0bdc748-c0bdc85c: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, sector_t start, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bea510)
Location: drivers/md/dm.c:1223
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
c000000000bea510-c000000000bea640: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, sector_t start, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ed498)
Location: drivers/md/dm.c:1223
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffe0006ed498-ffffffe0006ed552: dm_remap_zone_report (STB_GLOBAL)
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
void dm_remap_zone_report(struct dm_target *ti, sector_t start, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184cdb0)
Location: drivers/md/dm.c:1223
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff8184cdb0-ffffffff8184ce64: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, sector_t start, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818143d0)
Location: drivers/md/dm.c:1223
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff818143d0-ffffffff81814484: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, sector_t start, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189c3e0)
Location: drivers/md/dm.c:1223
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff8189c3e0-ffffffff8189c494: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dm_remap_zone_report(struct dm_target *ti, sector_t start, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b85a0)
Location: drivers/md/dm.c:1223
Inline: False
Direct callers:
  - drivers/md/dm-linear.c:linear_report_zones
```
**Symbols:**

```
ffffffff818b85a0-ffffffff818b8654: dm_remap_zone_report (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_zone *zones</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int *nr_zones</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bio *bio</code>
</li>
<li>
<b>Param reordered. </b>
<code>ti, bio, start</code> ➡️ <code>ti, start, zones, nr_zones</code>
</li>
</ul>
</details>
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
