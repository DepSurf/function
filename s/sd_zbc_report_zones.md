# Function: <code>sd_zbc_report_zones</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81647ff0)
Location: drivers/scsi/sd_zbc.c:87
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81647ff0-ffffffff816481a8: sd_zbc_report_zones.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8165ca90)
Location: drivers/scsi/sd_zbc.c:87
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff8165ca90-ffffffff8165cc1a: sd_zbc_report_zones.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff816c60f0)
Location: drivers/scsi/sd_zbc.c:73
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff816c60f0-ffffffff816c627a: sd_zbc_report_zones.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81702670)
Location: drivers/scsi/sd_zbc.c:73
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81702670-ffffffff817027fe: sd_zbc_report_zones.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81725430)
Location: drivers/scsi/sd_zbc.c:130
Inline: False
```
**Symbols:**

```
ffffffff81725430-ffffffff81725653: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81760a70)
Location: drivers/scsi/sd_zbc.c:163
Inline: False
```
**Symbols:**

```
ffffffff81760a70-ffffffff81760cbe: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81784a10)
Location: drivers/scsi/sd_zbc.c:163
Inline: False
```
**Symbols:**

```
ffffffff81784a10-ffffffff81784c5e: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81848ff0)
Location: drivers/scsi/sd_zbc.c:192
Inline: False
```
**Symbols:**

```
ffffffff81848ff0-ffffffff81849232: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81859280)
Location: drivers/scsi/sd_zbc.c:193
Inline: False
```
**Symbols:**

```
ffffffff81859280-ffffffff818594d7: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8183bf60)
Location: drivers/scsi/sd_zbc.c:193
Inline: False
```
**Symbols:**

```
ffffffff8183bf60-ffffffff8183c1b2: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:192
Inline: False
```
**Symbols:**

```
ffffffff81d0d12c-ffffffff81d0d193: sd_zbc_report_zones.cold (STB_LOCAL)
ffffffff818c8800-ffffffff818c8a98: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:251
Inline: False
```
**Symbols:**

```
ffffffff81ed60b3-ffffffff81ed60d5: sd_zbc_report_zones.cold (STB_LOCAL)
ffffffff81a15c50-ffffffff81a15ff7: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:254
Inline: False
```
**Symbols:**

```
ffffffff8209c228-ffffffff8209c24a: sd_zbc_report_zones.cold (STB_LOCAL)
ffffffff81b96990-ffffffff81b96d37: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:256
Inline: False
```
**Symbols:**

```
ffffffff8211d174-ffffffff8211d18e: sd_zbc_report_zones.cold (STB_LOCAL)
ffffffff81becf30-ffffffff81bed2da: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, unsigned int nr_zones, report_zones_cb cb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (0)
Location: drivers/scsi/sd_zbc.c:256
Inline: False
```
**Symbols:**

```
ffffffff821fb0b9-ffffffff821fb0d3: sd_zbc_report_zones.cold (STB_LOCAL)
ffffffff81c42600-ffffffff81c429aa: sd_zbc_report_zones (STB_GLOBAL)
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
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffff80001098b600)
Location: drivers/scsi/sd_zbc.c:163
Inline: False
```
**Symbols:**

```
ffff80001098b600-ffff80001098b870: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c0a5d8dc)
Location: drivers/scsi/sd_zbc.c:163
Inline: False
```
**Symbols:**

```
c0a5d8dc-c0a5dbc4: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c000000000a4c250)
Location: drivers/scsi/sd_zbc.c:163
Inline: False
```
**Symbols:**

```
c000000000a4c250-c000000000a4c578: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffe0005ef9f2)
Location: drivers/scsi/sd_zbc.c:163
Inline: False
```
**Symbols:**

```
ffffffe0005ef9f2-ffffffe0005efe56: sd_zbc_report_zones (STB_GLOBAL)
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
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81739100)
Location: drivers/scsi/sd_zbc.c:163
Inline: False
```
**Symbols:**

```
ffffffff81739100-ffffffff8173934e: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8171ada0)
Location: drivers/scsi/sd_zbc.c:163
Inline: False
```
**Symbols:**

```
ffffffff8171ada0-ffffffff8171afee: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81779890)
Location: drivers/scsi/sd_zbc.c:163
Inline: False
```
**Symbols:**

```
ffffffff81779890-ffffffff81779ade: sd_zbc_report_zones (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sd_zbc_report_zones(struct gendisk *disk, sector_t sector, struct blk_zone *zones, unsigned int *nr_zones);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff817936c0)
Location: drivers/scsi/sd_zbc.c:163
Inline: False
```
**Symbols:**

```
ffffffff817936c0-ffffffff8179390e: sd_zbc_report_zones (STB_GLOBAL)
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
