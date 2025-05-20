# Function: <code>disk_alloc_independent_access_ranges</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
struct blk_independent_access_ranges *disk_alloc_independent_access_ranges(struct gendisk *disk, int nr_ia_ranges);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ia-ranges.c (ffffffff8169fc90)
Location: block/blk-ia-ranges.c:273
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
```
**Symbols:**

```
ffffffff8169fc90-ffffffff8169fce3: disk_alloc_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct blk_independent_access_ranges *disk_alloc_independent_access_ranges(struct gendisk *disk, int nr_ia_ranges);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ia-ranges.c (ffffffff8175e720)
Location: block/blk-ia-ranges.c:264
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
```
**Symbols:**

```
ffffffff8175e720-ffffffff8175e773: disk_alloc_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct blk_independent_access_ranges *disk_alloc_independent_access_ranges(struct gendisk *disk, int nr_ia_ranges);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ia-ranges.c (ffffffff8179d620)
Location: block/blk-ia-ranges.c:264
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
```
**Symbols:**

```
ffffffff8179d620-ffffffff8179d67e: disk_alloc_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct blk_independent_access_ranges *disk_alloc_independent_access_ranges(struct gendisk *disk, int nr_ia_ranges);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ia-ranges.c (ffffffff817e1070)
Location: block/blk-ia-ranges.c:264
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
```
**Symbols:**

```
ffffffff817e1070-ffffffff817e10ce: disk_alloc_independent_access_ranges (STB_GLOBAL)
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
