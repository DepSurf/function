# Function: <code>drain_all_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81192b90)
Location: mm/page_alloc.c:1940
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81192b90-ffffffff81192c6a: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a8a50)
Location: mm/page_alloc.c:2302
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memory-failure.c:shake_page
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff811a8a50-ffffffff811a8b27: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b8ff0)
Location: mm/page_alloc.c:2355
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memory-failure.c:shake_page
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff811b8ff0-ffffffff811b90c9: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c0f10)
Location: mm/page_alloc.c:2463
Inline: True
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/madvise.c:SyS_madvise
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff811c0f10-ffffffff811c10de: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5520)
Location: mm/page_alloc.c:2498
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/madvise.c:SyS_madvise
  - mm/memory_hotplug.c:__offline_pages
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff811d5520-ffffffff811d56b8: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f6970)
Location: mm/page_alloc.c:2603
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/compaction.c:kcompactd_do_work
  - mm/madvise.c:madvise_inject_error
  - mm/memory_hotplug.c:__offline_pages
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff811f6970-ffffffff811f6b01: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81208d00)
Location: mm/page_alloc.c:2700
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/compaction.c:kcompactd_do_work
  - mm/madvise.c:madvise_inject_error
  - mm/memory_hotplug.c:__offline_pages
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81208d00-ffffffff81208eaa: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81270050)
Location: mm/page_alloc.c:2876
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/madvise.c:__do_sys_madvise
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81270050-ffffffff812701f5: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127ee90)
Location: mm/page_alloc.c:2867
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/madvise.c:__do_sys_madvise
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff8127ee90-ffffffff8127f035: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b1060)
Location: mm/page_alloc.c:2959
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/madvise.c:madvise_inject_error
  - mm/memory_hotplug.c:__offline_pages
  - mm/page_isolation.c:set_migratetype_isolate
```
**Symbols:**

```
ffffffff812b1060-ffffffff812b1205: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bd201)
Location: mm/page_alloc.c:3127
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
Direct callers:
  - mm/compaction.c:kcompactd_do_work
```
**Symbols:**

```
ffffffff812bcc30-ffffffff812bcc42: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c20d3)
Location: mm/page_alloc.c:3176
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
Direct callers:
  - mm/compaction.c:kcompactd_do_work
```
**Symbols:**

```
ffffffff812c1b60-ffffffff812c1b72: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81305a48)
Location: mm/page_alloc.c:3252
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
Direct callers:
  - mm/compaction.c:kcompactd_do_work
```
**Symbols:**

```
ffffffff813052a0-ffffffff813052b2: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81371f59)
Location: mm/page_alloc.c:3274
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
Direct callers:
  - mm/compaction.c:kcompactd_do_work
```
**Symbols:**

```
ffffffff8136d490-ffffffff8136d4aa: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ef779)
Location: mm/page_alloc.c:3304
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
Direct callers:
  - mm/compaction.c:kcompactd_do_work
```
**Symbols:**

```
ffffffff813e9830-ffffffff813e984a: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff814232f7)
Location: mm/page_alloc.c:2338
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
Direct callers:
  - mm/compaction.c:kcompactd_do_work
```
**Symbols:**

```
ffffffff8141ecc0-ffffffff8141ecda: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81450227)
Location: mm/page_alloc.c:2336
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
Direct callers:
  - mm/compaction.c:kcompactd_do_work
```
**Symbols:**

```
ffffffff8144b950-ffffffff8144b96a: drain_all_pages (STB_GLOBAL)
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
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010316ac0)
Location: mm/page_alloc.c:2867
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/madvise.c:__arm64_sys_madvise
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffff800010316ac0-ffff800010316d20: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0531150)
Location: mm/page_alloc.c:2867
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
c0531150-c0531360: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e8d40)
Location: mm/page_alloc.c:2867
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/madvise.c:__se_sys_madvise
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
c0000000003e8d40-c0000000003e9094: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021cea0)
Location: mm/page_alloc.c:2867
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffe00021cea0-ffffffe00021d0d6: drain_all_pages (STB_GLOBAL)
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
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812774e0)
Location: mm/page_alloc.c:2867
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/madvise.c:__do_sys_madvise
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff812774e0-ffffffff81277685: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81269400)
Location: mm/page_alloc.c:2867
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/madvise.c:__do_sys_madvise
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81269400-ffffffff812695a5: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275280)
Location: mm/page_alloc.c:2867
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/madvise.c:__do_sys_madvise
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81275280-ffffffff81275425: drain_all_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void drain_all_pages(struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81284e40)
Location: mm/page_alloc.c:2867
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/madvise.c:__do_sys_madvise
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81284e40-ffffffff81284fe5: drain_all_pages (STB_GLOBAL)
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
