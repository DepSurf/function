# Function: <code>fast_find_migrateblock</code>

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
Location: mm/compaction.c:1623
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
Location: mm/compaction.c:1624
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int fast_find_migrateblock(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812804d0)
Location: mm/compaction.c:1635
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
```
**Symbols:**

```
ffffffff812804d0-ffffffff812807a7: fast_find_migrateblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int fast_find_migrateblock(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128a570)
Location: mm/compaction.c:1703
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
```
**Symbols:**

```
ffffffff8128a570-ffffffff8128a87d: fast_find_migrateblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int fast_find_migrateblock(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128fbc0)
Location: mm/compaction.c:1739
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
```
**Symbols:**

```
ffffffff8128fbc0-ffffffff8128fec7: fast_find_migrateblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int fast_find_migrateblock(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1731
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
```
**Symbols:**

```
ffffffff812cfe90-ffffffff812d01c7: fast_find_migrateblock (STB_LOCAL)
ffffffff81cbb664-ffffffff81cbb68e: fast_find_migrateblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int fast_find_migrateblock(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1764
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
```
**Symbols:**

```
ffffffff8132e930-ffffffff8132ec59: fast_find_migrateblock (STB_LOCAL)
ffffffff81e6d224-ffffffff81e6d24e: fast_find_migrateblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int fast_find_migrateblock(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1751
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
```
**Symbols:**

```
ffffffff813a5160-ffffffff813a5489: fast_find_migrateblock (STB_LOCAL)
ffffffff8206357c-ffffffff820635a6: fast_find_migrateblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int fast_find_migrateblock(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1817
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
```
**Symbols:**

```
ffffffff813d8530-ffffffff813d88b8: fast_find_migrateblock (STB_LOCAL)
ffffffff820e2c50-ffffffff820e2c8f: fast_find_migrateblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int fast_find_migrateblock(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1866
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages
```
**Symbols:**

```
ffffffff814022b0-ffffffff81402638: fast_find_migrateblock (STB_LOCAL)
ffffffff821bf593-ffffffff821bf5d2: fast_find_migrateblock.cold (STB_LOCAL)
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
Location: mm/compaction.c:1624
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
Location: mm/compaction.c:1624
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
Location: mm/compaction.c:1624
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffe000200a02)
Location: mm/compaction.c:1624
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
Location: mm/compaction.c:1624
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
Location: mm/compaction.c:1624
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
Location: mm/compaction.c:1624
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
Location: mm/compaction.c:1624
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
