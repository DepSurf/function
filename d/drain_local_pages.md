# Function: <code>drain_local_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81194b20)
Location: mm/page_alloc.c:1919
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81194b20-ffffffff81194b46: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a7f80)
Location: mm/page_alloc.c:2281
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811a7f80-ffffffff811a7fa6: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b8350)
Location: mm/page_alloc.c:2334
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811b8350-ffffffff811b8376: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c01c9)
Location: mm/page_alloc.c:2432
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_local_pages_wq
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811c0ee0-ffffffff811c0f06: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d4ba9)
Location: mm/page_alloc.c:2467
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_local_pages_wq
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811d54f0-ffffffff811d5516: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f5869)
Location: mm/page_alloc.c:2572
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_local_pages_wq
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811f6940-ffffffff811f6966: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81208cb0)
Location: mm/page_alloc.c:2665
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81208cb0-ffffffff81208cd6: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81270000)
Location: mm/page_alloc.c:2841
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
ffffffff81270000-ffffffff81270026: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127ee40)
Location: mm/page_alloc.c:2832
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
ffffffff8127ee40-ffffffff8127ee66: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812af54e)
Location: mm/page_alloc.c:2924
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_local_pages_wq
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/swap.c:lru_add_drain_cpu_zone
```
**Symbols:**

```
ffffffff812b0ff0-ffffffff812b1052: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bb19e)
Location: mm/page_alloc.c:3004
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_local_pages_wq
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/swap.c:lru_add_drain_cpu_zone
```
**Symbols:**

```
ffffffff812bcbc0-ffffffff812bcc22: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c01a1)
Location: mm/page_alloc.c:3053
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_local_pages_wq
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/swap.c:lru_add_drain_cpu_zone
```
**Symbols:**

```
ffffffff812c1af0-ffffffff812c1b52: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81302e51)
Location: mm/page_alloc.c:3129
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_local_pages_wq
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/swap.c:lru_add_drain_cpu_zone
```
**Symbols:**

```
ffffffff81305230-ffffffff81305292: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81369b58)
Location: mm/page_alloc.c:3151
Inline: True
Inline callers:
  - mm/page_alloc.c:drain_local_pages_wq
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/swap.c:lru_add_drain_cpu_zone
```
**Symbols:**

```
ffffffff8136d420-ffffffff8136d489: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e97b0)
Location: mm/page_alloc.c:3211
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/swap.c:lru_add_drain_cpu_zone
```
**Symbols:**

```
ffffffff813e97b0-ffffffff813e9819: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141ec40)
Location: mm/page_alloc.c:2245
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/swap.c:lru_add_drain_cpu_zone
```
**Symbols:**

```
ffffffff8141ec40-ffffffff8141eca9: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144b8d0)
Location: mm/page_alloc.c:2243
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/swap.c:lru_add_drain_cpu_zone
```
**Symbols:**

```
ffffffff8144b8d0-ffffffff8144b939: drain_local_pages (STB_GLOBAL)
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
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010316a40)
Location: mm/page_alloc.c:2832
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
ffff800010316a40-ffff800010316a90: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05310f4)
Location: mm/page_alloc.c:2832
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
c05310f4-c0531130: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e8cc0)
Location: mm/page_alloc.c:2832
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
c0000000003e8cc0-c0000000003e8cf4: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021ce32)
Location: mm/page_alloc.c:2832
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
ffffffe00021ce32-ffffffe00021ce74: drain_local_pages (STB_GLOBAL)
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
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277490)
Location: mm/page_alloc.c:2832
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
ffffffff81277490-ffffffff812774b6: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812693b0)
Location: mm/page_alloc.c:2832
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
ffffffff812693b0-ffffffff812693d6: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275230)
Location: mm/page_alloc.c:2832
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
ffffffff81275230-ffffffff81275256: drain_local_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void drain_local_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81284de0)
Location: mm/page_alloc.c:2832
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - mm/compaction.c:compact_zone
  - mm/page_alloc.c:drain_local_pages_wq
```
**Symbols:**

```
ffffffff81284de0-ffffffff81284e06: drain_local_pages (STB_GLOBAL)
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
