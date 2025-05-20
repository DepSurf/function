# Function: <code>wake_throttle_isolated</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81311388)
Location: mm/internal.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff8133074b)
Location: mm/internal.h:73
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813848b0)
Location: mm/internal.h:73
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff813a7354)
Location: mm/internal.h:73
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b634f)
Location: mm/internal.h:91
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff813dab3b)
Location: mm/internal.h:91
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813df20c)
Location: mm/internal.h:97
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_inactive_list
```
```
In mm/compaction.c (ffffffff81404a2b)
Location: mm/internal.h:97
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
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
