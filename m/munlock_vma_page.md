# Function: <code>munlock_vma_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811c3190)
Location: mm/mlock.c:173
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff811c3190-ffffffff811c32b5: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811deee0)
Location: mm/mlock.c:176
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff811deee0-ffffffff811deffe: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811eed00)
Location: mm/mlock.c:176
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff811eed00-ffffffff811eee1c: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811f9cb0)
Location: mm/mlock.c:175
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff811f9cb0-ffffffff811f9dcc: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81212100)
Location: mm/mlock.c:176
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81212100-ffffffff8121221c: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81232e40)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81232e40-ffffffff81232f5d: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81246610)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81246610-ffffffff8124672d: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81258870)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81258870-ffffffff8125898f: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81266d40)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81266d40-ffffffff81266e5f: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81296f80)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff81296f80-ffffffff812970d7: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a1fc0)
Location: mm/mlock.c:167
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812a1fc0-ffffffff812a208f: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a7850)
Location: mm/mlock.c:167
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812a7850-ffffffff812a791f: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812e8e30)
Location: mm/mlock.c:168
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812e8e30-ffffffff812e8f3e: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135d48a)
Location: mm/internal.h:534
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
```
```
In mm/huge_memory.c (ffffffff813bbb17)
Location: mm/internal.h:534
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d8082)
Location: mm/internal.h:532
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffff8000102fdf20)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffff8000102fdf20-ffff8000102fe0d8: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c051d150)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
c051d150-c051d24c: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c0000000003c9590)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
c0000000003c9590-c0000000003c97c0: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffe00020c5d6)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffe00020c5d6-ffffffe00020c72e: munlock_vma_page (STB_GLOBAL)
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
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125f390)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8125f390-ffffffff8125f4af: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812517b0)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff812517b0-ffffffff812518c3: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125d130)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8125d130-ffffffff8125d24f: munlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int munlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8126cb30)
Location: mm/mlock.c:182
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff8126cb30-ffffffff8126cc3c: munlock_vma_page (STB_GLOBAL)
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
