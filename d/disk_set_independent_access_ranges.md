# Function: <code>disk_set_independent_access_ranges</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void disk_set_independent_access_ranges(struct gendisk *disk, struct blk_independent_access_ranges *iars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ia-ranges.c (0)
Location: block/blk-ia-ranges.c:296
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
```
**Symbols:**

```
ffffffff81e8d6a2-ffffffff81e8d6bb: disk_set_independent_access_ranges.cold (STB_LOCAL)
ffffffff8169ff30-ffffffff816a0177: disk_set_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disk_set_independent_access_ranges(struct gendisk *disk, struct blk_independent_access_ranges *iars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ia-ranges.c (ffffffff8175e9d0)
Location: block/blk-ia-ranges.c:287
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
```
**Symbols:**

```
ffffffff8175e9d0-ffffffff8175ebdb: disk_set_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void disk_set_independent_access_ranges(struct gendisk *disk, struct blk_independent_access_ranges *iars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ia-ranges.c (ffffffff8179d8d0)
Location: block/blk-ia-ranges.c:287
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
```
**Symbols:**

```
ffffffff8179d8d0-ffffffff8179dade: disk_set_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disk_set_independent_access_ranges(struct gendisk *disk, struct blk_independent_access_ranges *iars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ia-ranges.c (ffffffff817e1320)
Location: block/blk-ia-ranges.c:287
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd.c:sd_read_cpr
```
**Symbols:**

```
ffffffff817e1320-ffffffff817e152b: disk_set_independent_access_ranges (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
