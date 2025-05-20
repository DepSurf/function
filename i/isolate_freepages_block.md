# Function: <code>isolate_freepages_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811b5710)
Location: mm/compaction.c:394
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811b5710-ffffffff811b5ab7: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811cf500)
Location: mm/compaction.c:412
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811cf500-ffffffff811cf887: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811df540)
Location: mm/compaction.c:412
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811df540-ffffffff811df8c1: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811e9200)
Location: mm/compaction.c:407
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811e9200-ffffffff811e95ae: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811ff560)
Location: mm/compaction.c:433
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff811ff560-ffffffff811ff910: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81220980)
Location: mm/compaction.c:433
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff81220980-ffffffff81220d2c: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812339d0)
Location: mm/compaction.c:434
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff812339d0-ffffffff81233d80: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81244780)
Location: mm/compaction.c:534
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff81244780-ffffffff81244b0a: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81252c40)
Location: mm/compaction.c:535
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff81252c40-ffffffff81252fca: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812818e0)
Location: mm/compaction.c:536
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff812818e0-ffffffff81281c95: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128b9f0)
Location: mm/compaction.c:553
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff8128b9f0-ffffffff8128bdc2: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812906a0)
Location: mm/compaction.c:552
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff812906a0-ffffffff81290a68: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:550
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff812d0800-ffffffff812d0be5: isolate_freepages_block (STB_LOCAL)
ffffffff81cbb6c1-ffffffff81cbb794: isolate_freepages_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:546
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff8132ef00-ffffffff8132f399: isolate_freepages_block (STB_LOCAL)
ffffffff81e6d26c-ffffffff81e6d350: isolate_freepages_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:541
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff813a5db0-ffffffff813a624e: isolate_freepages_block (STB_LOCAL)
ffffffff82063614-ffffffff820636f8: isolate_freepages_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:559
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff813d92b0-ffffffff813d9721: isolate_freepages_block (STB_LOCAL)
ffffffff820e2cfb-ffffffff820e2d9e: isolate_freepages_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:583
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff81403030-ffffffff81403460: isolate_freepages_block (STB_LOCAL)
ffffffff821bf63e-ffffffff821bf7ab: isolate_freepages_block.cold (STB_LOCAL)
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
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102ea1b8)
Location: mm/compaction.c:535
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffff8000102ea1b8-ffff8000102ea518: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050d994)
Location: mm/compaction.c:535
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
c050d994-c050dd44: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003acdb0)
Location: mm/compaction.c:535
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
c0000000003acdb0-c0000000003ad1e0: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe0001fe9e2)
Location: mm/compaction.c:535
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffe0001fe9e2-ffffffe0001fec98: isolate_freepages_block (STB_LOCAL)
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
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124b290)
Location: mm/compaction.c:535
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff8124b290-ffffffff8124b61a: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123e230)
Location: mm/compaction.c:535
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff8123e230-ffffffff8123e5ba: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81249030)
Location: mm/compaction.c:535
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff81249030-ffffffff812493ba: isolate_freepages_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int isolate_freepages_block(struct compact_control *cc, long unsigned int *start_pfn, long unsigned int end_pfn, struct list_head *freelist, unsigned int stride, bool strict);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81258890)
Location: mm/compaction.c:535
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:isolate_freepages_range
```
**Symbols:**

```
ffffffff81258890-ffffffff81258c33: isolate_freepages_block (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int stride</code>
</li>
<li>
<b>Param reordered. </b>
<code>cc, start_pfn, end_pfn, freelist, strict</code> ➡️ <code>cc, start_pfn, end_pfn, freelist, stride, strict</code>
</li>
</ul>
</details>
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
