# Function: <code>freelist_scan_limit</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812466f5)
Location: mm/compaction.c:1168
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81254bfb)
Location: mm/compaction.c:1169
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812804d5)
Location: mm/compaction.c:1174
Inline: True
Inline callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128a575)
Location: mm/compaction.c:1235
Inline: True
Inline callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128fbc5)
Location: mm/compaction.c:1271
Inline: True
Inline callers:
  - mm/compaction.c:fast_find_migrateblock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812cfe95)
Location: mm/compaction.c:1265
Inline: True
Inline callers:
  - mm/compaction.c:fast_find_migrateblock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132e935)
Location: mm/compaction.c:1298
Inline: True
Inline callers:
  - mm/compaction.c:fast_find_migrateblock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a5165)
Location: mm/compaction.c:1296
Inline: True
Inline callers:
  - mm/compaction.c:fast_find_migrateblock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813d8535)
Location: mm/compaction.c:1349
Inline: True
Inline callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff814022b5)
Location: mm/compaction.c:1389
Inline: True
Inline callers:
  - mm/compaction.c:fast_find_migrateblock
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102ec13c)
Location: mm/compaction.c:1169
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0510200)
Location: mm/compaction.c:1169
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003af938)
Location: mm/compaction.c:1169
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe000200ac6)
Location: mm/compaction.c:1169
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124d24b)
Location: mm/compaction.c:1169
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812401eb)
Location: mm/compaction.c:1169
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124afeb)
Location: mm/compaction.c:1169
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8125a87e)
Location: mm/compaction.c:1169
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:fast_isolate_freepages
```
</details>
</li>
</ul>

## Differences
