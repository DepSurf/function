# Function: <code>extfrag_for_order</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int extfrag_for_order(struct zone *zone, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81280c10)
Location: mm/vmstat.c:1104
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:__compact_finished
```
**Symbols:**

```
ffffffff81280c10-ffffffff81280c87: extfrag_for_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int extfrag_for_order(struct zone *zone, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81285d10)
Location: mm/vmstat.c:1116
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:__compact_finished
```
**Symbols:**

```
ffffffff81285d10-ffffffff81285d83: extfrag_for_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int extfrag_for_order(struct zone *zone, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1122
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:__compact_finished
```
**Symbols:**

```
ffffffff81cbab59-ffffffff81cbab70: extfrag_for_order.cold (STB_LOCAL)
ffffffff812c4f70-ffffffff812c4ff6: extfrag_for_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int extfrag_for_order(struct zone *zone, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1128
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:__compact_finished
```
**Symbols:**

```
ffffffff81e6c474-ffffffff81e6c48a: extfrag_for_order.cold (STB_LOCAL)
ffffffff813224b0-ffffffff81322558: extfrag_for_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int extfrag_for_order(struct zone *zone, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1115
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:__compact_finished
```
**Symbols:**

```
ffffffff82062eb4-ffffffff82062eca: extfrag_for_order.cold (STB_LOCAL)
ffffffff813966b0-ffffffff81396758: extfrag_for_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int extfrag_for_order(struct zone *zone, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1116
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:__compact_finished
```
**Symbols:**

```
ffffffff820e2751-ffffffff820e2767: extfrag_for_order.cold (STB_LOCAL)
ffffffff813c95e0-ffffffff813c9688: extfrag_for_order (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int extfrag_for_order(struct zone *zone, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmstat.c (0)
Location: mm/vmstat.c:1119
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:kcompactd
  - mm/compaction.c:__compact_finished
```
**Symbols:**

```
ffffffff821bf142-ffffffff821bf158: extfrag_for_order.cold (STB_LOCAL)
ffffffff813f3f70-ffffffff813f4018: extfrag_for_order (STB_GLOBAL)
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
