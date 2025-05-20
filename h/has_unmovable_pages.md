# Function: <code>has_unmovable_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81195250)
Location: mm/page_alloc.c:6504
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
Direct callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81195250-ffffffff81195376: has_unmovable_pages.part.83 (STB_LOCAL)
ffffffff811975c0-ffffffff811975f2: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811ac56c)
Location: mm/page_alloc.c:7035
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
Direct callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff811a7870-ffffffff811a79a4: has_unmovable_pages.part.88 (STB_LOCAL)
ffffffff811ac4d0-ffffffff811ac502: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811bcb49)
Location: mm/page_alloc.c:7087
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
Direct callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff811b7c60-ffffffff811b7d91: has_unmovable_pages.part.89 (STB_LOCAL)
ffffffff811bcab0-ffffffff811bcae2: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff811c4d19)
Location: mm/page_alloc.c:7414
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
Direct callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff811bfaa0-ffffffff811bfbe8: has_unmovable_pages.part.94 (STB_LOCAL)
ffffffff811c4c90-ffffffff811c4cbb: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d9930)
Location: mm/page_alloc.c:7429
Inline: True
Direct callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff811d9930-ffffffff811d9a97: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811fa270)
Location: mm/page_alloc.c:7611
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff811fa270-ffffffff811fa409: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120c950)
Location: mm/page_alloc.c:7932
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff8120c950-ffffffff8120cb74: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81272d00)
Location: mm/page_alloc.c:8139
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81272d00-ffffffff81272f5c: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81281b60)
Location: mm/page_alloc.c:8169
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81281b60-ffffffff81281dc1: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *has_unmovable_pages(struct zone *zone, struct page *page, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b3f50)
Location: mm/page_alloc.c:8196
Inline: False
Direct callers:
  - mm/page_isolation.c:set_migratetype_isolate
```
**Symbols:**

```
ffffffff812b3f50-ffffffff812b413c: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *has_unmovable_pages(struct zone *zone, struct page *page, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bf9d0)
Location: mm/page_alloc.c:8333
Inline: False
Direct callers:
  - mm/page_isolation.c:set_migratetype_isolate
```
**Symbols:**

```
ffffffff812bf9d0-ffffffff812bfbc0: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *has_unmovable_pages(struct zone *zone, struct page *page, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c5130)
Location: mm/page_alloc.c:8542
Inline: False
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff812c5130-ffffffff812c5320: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct page *has_unmovable_pages(struct zone *zone, struct page *page, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:8807
Inline: False
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81cbe4ba-ffffffff81cbe4fb: has_unmovable_pages.cold (STB_LOCAL)
ffffffff81309670-ffffffff81309876: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (0)
Location: mm/page_isolation.c:33
Inline: True
```
**Symbols:**

```
ffffffff813ddc50-ffffffff813ddfd4: has_unmovable_pages.constprop.0 (STB_LOCAL)
ffffffff81e759b0-ffffffff81e759f0: has_unmovable_pages.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (0)
Location: mm/page_isolation.c:33
Inline: True
```
**Symbols:**

```
ffffffff814648e0-ffffffff81464c50: has_unmovable_pages.constprop.0 (STB_LOCAL)
ffffffff820683ec-ffffffff8206842c: has_unmovable_pages.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (0)
Location: mm/page_isolation.c:33
Inline: True
```
**Symbols:**

```
ffffffff8149a3e0-ffffffff8149a720: has_unmovable_pages.isra.0 (STB_LOCAL)
ffffffff820e7cef-ffffffff820e7d2f: has_unmovable_pages.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (0)
Location: mm/page_isolation.c:33
Inline: True
```
**Symbols:**

```
ffffffff814c9b60-ffffffff814c9e03: has_unmovable_pages.isra.0 (STB_LOCAL)
ffffffff821c4a37-ffffffff821c4a75: has_unmovable_pages.isra.0.cold (STB_LOCAL)
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
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff80001031a290)
Location: mm/page_alloc.c:8169
Inline: False
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffff80001031a290-ffff80001031a50c: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05348b8)
Location: mm/page_alloc.c:8169
Inline: False
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
c05348b8-c0534ab8: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ed350)
Location: mm/page_alloc.c:8169
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
c0000000003ed350-c0000000003ed764: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021fb48)
Location: mm/page_alloc.c:8169
Inline: False
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffe00021fb48-ffffffe00021fd0a: has_unmovable_pages (STB_GLOBAL)
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
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127a1b0)
Location: mm/page_alloc.c:8169
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff8127a1b0-ffffffff8127a411: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126c0a0)
Location: mm/page_alloc.c:8169
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff8126c0a0-ffffffff8126c301: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277f50)
Location: mm/page_alloc.c:8169
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81277f50-ffffffff812781b1: has_unmovable_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool has_unmovable_pages(struct zone *zone, struct page *page, int count, int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81287b40)
Location: mm/page_alloc.c:8169
Inline: False
Direct callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81287b40-ffffffff81287da1: has_unmovable_pages (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int migratetype</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, page, count, skip_hwpoisoned_pages</code> ➡️ <code>zone, page, count, migratetype, skip_hwpoisoned_pages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool skip_hwpoisoned_pages</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>int count</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, page, count, migratetype, flags</code> ➡️ <code>zone, page, migratetype, flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>struct page *</code>
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
