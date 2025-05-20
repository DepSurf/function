# Function: <code>__compaction_suitable</code>

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
In mm/compaction.c (ffffffff811b73dc)
Location: mm/compaction.c:1281
Inline: True
Inline callers:
  - mm/compaction.c:compaction_suitable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff811d2008)
Location: mm/compaction.c:1373
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff811cf240-ffffffff811cf2db: __compaction_suitable.part.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff811e1f3c)
Location: mm/compaction.c:1365
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff811df430-ffffffff811df4b9: __compaction_suitable.part.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff811ebd57)
Location: mm/compaction.c:1399
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff811e90f0-ffffffff811e916e: __compaction_suitable.part.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff812020c8)
Location: mm/compaction.c:1423
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff811ff450-ffffffff811ff4ce: __compaction_suitable.part.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812206e0)
Location: mm/compaction.c:1423
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff812206e0-ffffffff8122076e: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81233720)
Location: mm/compaction.c:1424
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff81233720-ffffffff812337be: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81243ad0)
Location: mm/compaction.c:1958
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff81243ad0-ffffffff81243b78: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81251f90)
Location: mm/compaction.c:1958
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff81251f90-ffffffff81252038: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812809a0)
Location: mm/compaction.c:1969
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff812809a0-ffffffff81280a48: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128aa70)
Location: mm/compaction.c:2117
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff8128aa70-ffffffff8128ab18: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812900d0)
Location: mm/compaction.c:2156
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff812900d0-ffffffff81290175: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2148
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff812cfb60-ffffffff812cfc4b: __compaction_suitable (STB_LOCAL)
ffffffff81cbb5ef-ffffffff81cbb608: __compaction_suitable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2170
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff8132e5c0-ffffffff8132e6ae: __compaction_suitable (STB_LOCAL)
ffffffff81e6d1af-ffffffff81e6d1c8: __compaction_suitable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2169
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff813a4d80-ffffffff813a4e6e: __compaction_suitable (STB_LOCAL)
ffffffff82063507-ffffffff82063520: __compaction_suitable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool __compaction_suitable(struct zone *zone, int order, int highest_zoneidx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2250
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff813d8330-ffffffff813d83a9: __compaction_suitable (STB_LOCAL)
ffffffff820e2c06-ffffffff820e2c26: __compaction_suitable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool __compaction_suitable(struct zone *zone, int order, int highest_zoneidx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2301
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff81402010-ffffffff81402089: __compaction_suitable (STB_LOCAL)
ffffffff821bf52e-ffffffff821bf54e: __compaction_suitable.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102e8a70)
Location: mm/compaction.c:1958
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffff8000102e8a70-ffff8000102e8b44: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050d7bc)
Location: mm/compaction.c:1958
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
c050d7bc-c050d860: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003abd50)
Location: mm/compaction.c:1958
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
c0000000003abd50-c0000000003abe5c: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe0001fe7b2)
Location: mm/compaction.c:1958
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffe0001fe7b2-ffffffe0001fe850: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124a5e0)
Location: mm/compaction.c:1958
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff8124a5e0-ffffffff8124a688: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123d590)
Location: mm/compaction.c:1958
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff8123d590-ffffffff8123d638: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81248380)
Location: mm/compaction.c:1958
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff81248380-ffffffff81248428: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum compact_result __compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx, long unsigned int wmark_target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81257bb0)
Location: mm/compaction.c:1958
Inline: False
Direct callers:
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/compaction.c:compaction_suitable
```
**Symbols:**

```
ffffffff81257bb0-ffffffff81257c58: __compaction_suitable (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>int classzone_idx</code>
</li>
</ul>
</details>
</li>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int alloc_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, order, alloc_flags, highest_zoneidx, wmark_target</code> ➡️ <code>zone, order, highest_zoneidx, wmark_target</code>
</li>
<li>
<b>Return type changed. </b>
<code>enum compact_result</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
