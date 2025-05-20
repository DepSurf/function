# Function: <code>disk_register_independent_access_ranges</code>

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
int disk_register_independent_access_ranges(struct gendisk *disk, struct blk_independent_access_ranges *new_iars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ia-ranges.c (0)
Location: block/blk-ia-ranges.c:112
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-ia-ranges.c:disk_set_independent_access_ranges
```
**Symbols:**

```
ffffffff81e8d68e-ffffffff81e8d6a2: disk_register_independent_access_ranges.cold (STB_LOCAL)
ffffffff8169fd90-ffffffff8169ff29: disk_register_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int disk_register_independent_access_ranges(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ia-ranges.c (0)
Location: block/blk-ia-ranges.c:108
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-ia-ranges.c:disk_set_independent_access_ranges
```
**Symbols:**

```
ffffffff82076c4c-ffffffff82076c60: disk_register_independent_access_ranges.cold (STB_LOCAL)
ffffffff8175e790-ffffffff8175e905: disk_register_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int disk_register_independent_access_ranges(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ia-ranges.c (0)
Location: block/blk-ia-ranges.c:108
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-ia-ranges.c:disk_set_independent_access_ranges
```
**Symbols:**

```
ffffffff820f6a70-ffffffff820f6a84: disk_register_independent_access_ranges.cold (STB_LOCAL)
ffffffff8179d690-ffffffff8179d805: disk_register_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int disk_register_independent_access_ranges(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ia-ranges.c (0)
Location: block/blk-ia-ranges.c:108
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-ia-ranges.c:disk_set_independent_access_ranges
```
**Symbols:**

```
ffffffff821d3ebe-ffffffff821d3ed2: disk_register_independent_access_ranges.cold (STB_LOCAL)
ffffffff817e10e0-ffffffff817e1255: disk_register_independent_access_ranges (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct blk_independent_access_ranges *new_iars</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
