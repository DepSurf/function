# Function: <code>__isolate_free_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81195450)
Location: mm/page_alloc.c:2118
Inline: False
Direct callers:
  - mm/page_alloc.c:split_free_page
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81195450-ffffffff81195648: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a9480)
Location: mm/page_alloc.c:2480
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811a9480-ffffffff811a9684: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b9a00)
Location: mm/page_alloc.c:2533
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811b9a00-ffffffff811b9be5: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c1a40)
Location: mm/page_alloc.c:2686
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811c1a40-ffffffff811c1c1a: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5f70)
Location: mm/page_alloc.c:2744
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811d5f70-ffffffff811d614a: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f73a0)
Location: mm/page_alloc.c:2848
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff811f73a0-ffffffff811f757c: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812097c0)
Location: mm/page_alloc.c:2947
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff812097c0-ffffffff812099a0: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81270ad0)
Location: mm/page_alloc.c:3123
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81270ad0-ffffffff81270c97: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127f910)
Location: mm/page_alloc.c:3114
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff8127f910-ffffffff8127fad2: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b1e60)
Location: mm/page_alloc.c:3206
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_reporting.c:page_reporting_cycle
```
**Symbols:**

```
ffffffff812b1e60-ffffffff812b201a: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bd830)
Location: mm/page_alloc.c:3307
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_reporting.c:page_reporting_cycle
```
**Symbols:**

```
ffffffff812bd830-ffffffff812bd9da: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c27e0)
Location: mm/page_alloc.c:3356
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_reporting.c:page_reporting_cycle
```
**Symbols:**

```
ffffffff812c27e0-ffffffff812c2987: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3503
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_reporting.c:page_reporting_cycle
```
**Symbols:**

```
ffffffff81cbd81d-ffffffff81cbd8bb: __isolate_free_page.cold (STB_LOCAL)
ffffffff813062b0-ffffffff81306503: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3536
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_reporting.c:page_reporting_cycle
```
**Symbols:**

```
ffffffff81e6f737-ffffffff81e6f7dd: __isolate_free_page.cold (STB_LOCAL)
ffffffff8136e380-ffffffff8136e6d5: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3602
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_reporting.c:page_reporting_cycle
```
**Symbols:**

```
ffffffff820654e1-ffffffff82065587: __isolate_free_page.cold (STB_LOCAL)
ffffffff813ea870-ffffffff813eabc0: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2581
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_reporting.c:page_reporting_cycle
```
**Symbols:**

```
ffffffff820e4ccc-ffffffff820e4d87: __isolate_free_page.cold (STB_LOCAL)
ffffffff8141f7b0-ffffffff8141fb11: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2624
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
  - mm/page_reporting.c:page_reporting_cycle
```
**Symbols:**

```
ffffffff821c19a0-ffffffff821c1a56: __isolate_free_page.cold (STB_LOCAL)
ffffffff8144c4c0-ffffffff8144c73e: __isolate_free_page (STB_GLOBAL)
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
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010317660)
Location: mm/page_alloc.c:3114
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffff800010317660-ffff800010317864: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0532180)
Location: mm/page_alloc.c:3114
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
c0532180-c05323c0: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e9a60)
Location: mm/page_alloc.c:3114
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
c0000000003e9a60-c0000000003e9d18: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021db74)
Location: mm/page_alloc.c:3114
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffe00021db74-ffffffe00021dcf6: __isolate_free_page (STB_GLOBAL)
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
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277f60)
Location: mm/page_alloc.c:3114
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81277f60-ffffffff81278122: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81269e50)
Location: mm/page_alloc.c:3114
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81269e50-ffffffff8126a012: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275d00)
Location: mm/page_alloc.c:3114
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff81275d00-ffffffff81275ec2: __isolate_free_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __isolate_free_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812858e0)
Location: mm/page_alloc.c:3114
Inline: False
Direct callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_block
  - mm/page_isolation.c:unset_migratetype_isolate
```
**Symbols:**

```
ffffffff812858e0-ffffffff81285aa2: __isolate_free_page (STB_GLOBAL)
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
