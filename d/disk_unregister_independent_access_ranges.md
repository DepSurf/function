# Function: <code>disk_unregister_independent_access_ranges</code>

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
void disk_unregister_independent_access_ranges(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ia-ranges.c (0)
Location: block/blk-ia-ranges.c:164
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
```
**Symbols:**

```
ffffffff81e8d67a-ffffffff81e8d68e: disk_unregister_independent_access_ranges.cold (STB_LOCAL)
ffffffff8169fcf0-ffffffff8169fd82: disk_unregister_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void disk_unregister_independent_access_ranges(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ia-ranges.c (0)
Location: block/blk-ia-ranges.c:152
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-ia-ranges.c:disk_set_independent_access_ranges
```
**Symbols:**

```
ffffffff82076c60-ffffffff82076c74: disk_unregister_independent_access_ranges.cold (STB_LOCAL)
ffffffff8175e920-ffffffff8175e9b1: disk_unregister_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void disk_unregister_independent_access_ranges(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ia-ranges.c (0)
Location: block/blk-ia-ranges.c:152
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-ia-ranges.c:disk_set_independent_access_ranges
```
**Symbols:**

```
ffffffff820f6a84-ffffffff820f6a98: disk_unregister_independent_access_ranges.cold (STB_LOCAL)
ffffffff8179d820-ffffffff8179d8b1: disk_unregister_independent_access_ranges (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void disk_unregister_independent_access_ranges(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ia-ranges.c (0)
Location: block/blk-ia-ranges.c:152
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-ia-ranges.c:disk_set_independent_access_ranges
```
**Symbols:**

```
ffffffff821d3ed2-ffffffff821d3ee6: disk_unregister_independent_access_ranges.cold (STB_LOCAL)
ffffffff817e1270-ffffffff817e1301: disk_unregister_independent_access_ranges (STB_GLOBAL)
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
