# Function: <code>memmap_valid_within</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1213
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1285
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1263
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1309
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1322
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1328
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1328
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1336
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1336
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1439
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1439
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1433
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1433
Inline: True
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool memmap_valid_within(long unsigned int pfn, struct page *page, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmzone.c (c0500598)
Location: mm/mmzone.c:76
Inline: False
Direct callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
**Symbols:**

```
c0500598-c0500604: memmap_valid_within (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/linux/mmzone.h:1446
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
