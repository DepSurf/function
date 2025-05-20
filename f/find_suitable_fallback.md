# Function: <code>find_suitable_fallback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81191e40)
Location: mm/page_alloc.c:1610
Inline: True
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81191e40-ffffffff81191eab: find_suitable_fallback.part.72 (STB_LOCAL)
ffffffff81192b60-ffffffff81192b84: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811a862e)
Location: mm/page_alloc.c:1969
Inline: True
Inline callers:
  - mm/page_alloc.c:__rmqueue
Direct callers:
  - mm/page_alloc.c:__rmqueue
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811a6900-ffffffff811a6975: find_suitable_fallback.part.78 (STB_LOCAL)
ffffffff811a89c0-ffffffff811a89e4: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811b8aee)
Location: mm/page_alloc.c:1988
Inline: True
Inline callers:
  - mm/page_alloc.c:__rmqueue
Direct callers:
  - mm/page_alloc.c:__rmqueue
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811b6c40-ffffffff811b6cb5: find_suitable_fallback.part.79 (STB_LOCAL)
ffffffff811b8f60-ffffffff811b8f84: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811c0914)
Location: mm/page_alloc.c:2058
Inline: True
Inline callers:
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:__rmqueue
Direct callers:
  - mm/page_alloc.c:__rmqueue
  - mm/page_alloc.c:__rmqueue
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811beb80-ffffffff811bebf8: find_suitable_fallback.part.84 (STB_LOCAL)
ffffffff811c0e50-ffffffff811c0e74: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5410)
Location: mm/page_alloc.c:2096
Inline: True
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811d5410-ffffffff811d548d: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f6880)
Location: mm/page_alloc.c:2205
Inline: True
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811f6880-ffffffff811f68fa: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81208bf0)
Location: mm/page_alloc.c:2284
Inline: True
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81208bf0-ffffffff81208c6a: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126f030)
Location: mm/page_alloc.c:2463
Inline: True
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff8126f030-ffffffff8126f0bc: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127de70)
Location: mm/page_alloc.c:2454
Inline: True
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff8127de70-ffffffff8127defc: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b0190)
Location: mm/page_alloc.c:2532
Inline: True
Direct callers:
  - mm/compaction.c:compact_finished
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812b0190-ffffffff812b0230: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bbe00)
Location: mm/page_alloc.c:2611
Inline: True
Direct callers:
  - mm/compaction.c:__compact_finished
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812bbe00-ffffffff812bbea4: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c0d50)
Location: mm/page_alloc.c:2660
Inline: True
Direct callers:
  - mm/compaction.c:__compact_finished
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812c0d50-ffffffff812c0df0: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81303d26)
Location: mm/page_alloc.c:2733
Inline: True
Direct callers:
  - mm/compaction.c:__compact_finished
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff81cbd537-ffffffff81cbd570: find_suitable_fallback.cold (STB_LOCAL)
ffffffff81303cf0-ffffffff81303ea6: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2758
Inline: False
Direct callers:
  - mm/compaction.c:__compact_finished
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff81e6f534-ffffffff81e6f56d: find_suitable_fallback.cold (STB_LOCAL)
ffffffff8136bdd0-ffffffff8136bfaa: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2837
Inline: False
Direct callers:
  - mm/compaction.c:__compact_finished
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff820652ef-ffffffff82065328: find_suitable_fallback.cold (STB_LOCAL)
ffffffff813e8130-ffffffff813e830a: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1883
Inline: False
Direct callers:
  - mm/compaction.c:__compact_finished
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff820e4aca-ffffffff820e4b03: find_suitable_fallback.cold (STB_LOCAL)
ffffffff8141d210-ffffffff8141d373: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1845
Inline: False
Direct callers:
  - mm/compaction.c:__compact_finished
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff821c1765-ffffffff821c179e: find_suitable_fallback.cold (STB_LOCAL)
ffffffff81449cb0-ffffffff81449e13: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010315870)
Location: mm/page_alloc.c:2454
Inline: True
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffff800010315870-ffff800010315940: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05300c8)
Location: mm/page_alloc.c:2454
Inline: True
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
c05300c8-c0530188: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e7840)
Location: mm/page_alloc.c:2454
Inline: True
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
c0000000003e7840-c0000000003e7938: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021c132)
Location: mm/page_alloc.c:2454
Inline: True
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffe00021c132-ffffffe00021c1d0: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812764c0)
Location: mm/page_alloc.c:2454
Inline: True
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812764c0-ffffffff8127654c: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81268410)
Location: mm/page_alloc.c:2454
Inline: True
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff81268410-ffffffff8126849c: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81274260)
Location: mm/page_alloc.c:2454
Inline: True
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff81274260-ffffffff812742ec: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int find_suitable_fallback(struct free_area *area, unsigned int order, int migratetype, bool only_stealable, bool *can_steal);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81283d60)
Location: mm/page_alloc.c:2454
Inline: True
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff81283d60-ffffffff81283dec: find_suitable_fallback (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
