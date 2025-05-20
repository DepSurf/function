# Function: <code>update_cached_migrate</code>

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
In mm/compaction.c (ffffffff81246842)
Location: mm/compaction.c:406
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
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
In mm/compaction.c (ffffffff81254d44)
Location: mm/compaction.c:407
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
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
In mm/compaction.c (ffffffff8128338f)
Location: mm/compaction.c:407
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
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
In mm/compaction.c (ffffffff8128d5e5)
Location: mm/compaction.c:424
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
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
In mm/compaction.c (ffffffff8129257b)
Location: mm/compaction.c:423
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void update_cached_migrate(struct compact_control *cc, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:421
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff812cfc50-ffffffff812cfcbf: update_cached_migrate (STB_LOCAL)
ffffffff81cbb608-ffffffff81cbb61d: update_cached_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void update_cached_migrate(struct compact_control *cc, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:420
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff8132e6b0-ffffffff8132e729: update_cached_migrate (STB_LOCAL)
ffffffff81e6d1c8-ffffffff81e6d1dd: update_cached_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void update_cached_migrate(struct compact_control *cc, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:415
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff813a4e80-ffffffff813a4ef9: update_cached_migrate (STB_LOCAL)
ffffffff82063520-ffffffff82063535: update_cached_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void update_cached_migrate(struct compact_control *cc, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:437
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff813d83f0-ffffffff813d8469: update_cached_migrate (STB_LOCAL)
ffffffff820e2c26-ffffffff820e2c3b: update_cached_migrate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void update_cached_migrate(struct compact_control *cc, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:461
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff814020d0-ffffffff81402149: update_cached_migrate (STB_LOCAL)
ffffffff821bf54e-ffffffff821bf563: update_cached_migrate.cold (STB_LOCAL)
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
In mm/compaction.c (ffff8000102ec20c)
Location: mm/compaction.c:407
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
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
In mm/compaction.c (c0510338)
Location: mm/compaction.c:407
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_cached_migrate(struct compact_control *cc, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003a9f00)
Location: mm/compaction.c:407
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
c0000000003a9f00-c0000000003a9f70: update_cached_migrate (STB_LOCAL)
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
In mm/compaction.c (ffffffe000200b9e)
Location: mm/compaction.c:407
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
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
In mm/compaction.c (ffffffff8124d394)
Location: mm/compaction.c:407
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
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
In mm/compaction.c (ffffffff81240334)
Location: mm/compaction.c:407
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
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
In mm/compaction.c (ffffffff8124b134)
Location: mm/compaction.c:407
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
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
In mm/compaction.c (ffffffff8125a9c7)
Location: mm/compaction.c:407
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:isolate_migratepages_block
```
</details>
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
<b>Arch</b>
<ul>
</ul>
