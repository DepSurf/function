# Function: <code>split_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81191710)
Location: mm/page_alloc.c:2092
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:split_free_page
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff81191710-ffffffff8119174b: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a9019)
Location: mm/page_alloc.c:2458
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:map_pages
```
**Symbols:**

```
ffffffff811a5f30-ffffffff811a5f6b: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b95b5)
Location: mm/page_alloc.c:2511
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:map_pages
```
**Symbols:**

```
ffffffff811b62b0-ffffffff811b62eb: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c1625)
Location: mm/page_alloc.c:2664
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:map_pages
```
**Symbols:**

```
ffffffff811be180-ffffffff811be1bc: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5a45)
Location: mm/page_alloc.c:2731
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:map_pages
```
**Symbols:**

```
ffffffff811d2ea0-ffffffff811d2edc: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f6e6d)
Location: mm/page_alloc.c:2835
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:map_pages
```
**Symbols:**

```
ffffffff811f4240-ffffffff811f427c: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120920d)
Location: mm/page_alloc.c:2934
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:map_pages
```
**Symbols:**

```
ffffffff812065e0-ffffffff8120661c: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127062b)
Location: mm/page_alloc.c:3110
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff8126c590-ffffffff8126c5cc: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127f46b)
Location: mm/page_alloc.c:3101
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff8127b3a0-ffffffff8127b3dc: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b1b43)
Location: mm/page_alloc.c:3193
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff812ad540-ffffffff812ad57c: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bd4c1)
Location: mm/page_alloc.c:3293
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff812b9700-ffffffff812b9743: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c2452)
Location: mm/page_alloc.c:3342
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff812bead0-ffffffff812beb13: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3489
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
  - mm/page_alloc.c:make_alloc_exact
```
**Symbols:**

```
ffffffff81cbd10e-ffffffff81cbd15d: split_page.cold (STB_LOCAL)
ffffffff81301330-ffffffff813013a4: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3522
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
  - mm/vmalloc.c:vm_area_alloc_pages
  - mm/page_alloc.c:make_alloc_exact
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
```
**Symbols:**

```
ffffffff81e6ef7b-ffffffff81e6efc8: split_page.cold (STB_LOCAL)
ffffffff81368b50-ffffffff81368bc8: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3588
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
**Symbols:**

```
ffffffff82064d22-ffffffff82064d6f: split_page.cold (STB_LOCAL)
ffffffff813e42e0-ffffffff813e4358: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2567
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
**Symbols:**

```
ffffffff820e44b7-ffffffff820e4504: split_page.cold (STB_LOCAL)
ffffffff81418f70-ffffffff81418fe8: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2610
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
**Symbols:**

```
ffffffff821c1122-ffffffff821c116f: split_page.cold (STB_LOCAL)
ffffffff81445b40-ffffffff81445bb8: split_page (STB_GLOBAL)
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
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010317018)
Location: mm/page_alloc.c:3101
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
**Symbols:**

```
ffff8000103128f8-ffff800010312954: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0531800)
Location: mm/page_alloc.c:3101
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
c052d568-c052d5ac: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e9340)
Location: mm/page_alloc.c:3101
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
c0000000003e38f0-c0000000003e3944: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021d338)
Location: mm/page_alloc.c:3101
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffe000219d24-ffffffe000219d74: split_page (STB_GLOBAL)
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
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277abb)
Location: mm/page_alloc.c:3101
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff812739f0-ffffffff81273a2c: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812699cb)
Location: mm/page_alloc.c:3101
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff81265960-ffffffff8126599c: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127585b)
Location: mm/page_alloc.c:3101
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff81271790-ffffffff812717cc: split_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void split_page(struct page *page, unsigned int order);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8128541b)
Location: mm/page_alloc.c:3101
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/compaction.c:split_map_pages
```
**Symbols:**

```
ffffffff812811f0-ffffffff8128122c: split_page (STB_GLOBAL)
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
