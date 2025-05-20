# Function: <code>flush_tlb_batched_pending</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81203930)
Location: mm/rmap.c:657
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff81203930-ffffffff81203962: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121c630)
Location: mm/rmap.c:658
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff8121c630-ffffffff8121c662: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123e420)
Location: mm/rmap.c:659
Inline: False
Direct callers:
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff8123e420-ffffffff8123e451: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812529b0)
Location: mm/rmap.c:659
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff812529b0-ffffffff812529e7: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81264d30)
Location: mm/rmap.c:659
Inline: False
Direct callers:
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff81264d30-ffffffff81264d67: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812735c0)
Location: mm/rmap.c:660
Inline: False
Direct callers:
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff812735c0-ffffffff812735f7: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a4740)
Location: mm/rmap.c:673
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff812a4740-ffffffff812a477a: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812afed0)
Location: mm/rmap.c:673
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff812afed0-ffffffff812aff0a: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b54b0)
Location: mm/rmap.c:680
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff812b54b0-ffffffff812b54ea: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:681
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff81cbcd50-ffffffff81cbcd65: flush_tlb_batched_pending.cold (STB_LOCAL)
ffffffff812f7120-ffffffff812f7171: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135c610)
Location: mm/rmap.c:721
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff8135c610-ffffffff8135c67f: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d6ce0)
Location: mm/rmap.c:716
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff813d6ce0-ffffffff813d6d4f: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140bd30)
Location: mm/rmap.c:719
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff8140bd30-ffffffff8140bd9f: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff814385e0)
Location: mm/rmap.c:743
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff814385e0-ffffffff8143864f: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/internal.h:554
Inline: True
```
```
In mm/mprotect.c (0)
Location: mm/internal.h:554
Inline: True
```
```
In mm/mremap.c (0)
Location: mm/internal.h:554
Inline: True
```
```
In mm/madvise.c (0)
Location: mm/internal.h:554
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/internal.h:554
Inline: True
```
```
In mm/mprotect.c (c0523358)
Location: mm/internal.h:554
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (0)
Location: mm/internal.h:554
Inline: True
```
```
In mm/madvise.c (0)
Location: mm/internal.h:554
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/internal.h:554
Inline: True
```
```
In mm/mprotect.c (0)
Location: mm/internal.h:554
Inline: True
```
```
In mm/mremap.c (0)
Location: mm/internal.h:554
Inline: True
```
```
In mm/madvise.c (0)
Location: mm/internal.h:554
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: mm/internal.h:554
Inline: True
```
```
In mm/mprotect.c (0)
Location: mm/internal.h:554
Inline: True
```
```
In mm/mremap.c (0)
Location: mm/internal.h:554
Inline: True
```
```
In mm/madvise.c (0)
Location: mm/internal.h:554
Inline: True
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
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126bc10)
Location: mm/rmap.c:660
Inline: False
Direct callers:
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff8126bc10-ffffffff8126bc47: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125dcb0)
Location: mm/rmap.c:660
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff8125dcb0-ffffffff8125dce7: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812699b0)
Location: mm/rmap.c:660
Inline: False
Direct callers:
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff812699b0-ffffffff812699e7: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flush_tlb_batched_pending(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81279320)
Location: mm/rmap.c:660
Inline: False
Direct callers:
  - mm/mprotect.c:change_pte_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff81279320-ffffffff81279357: flush_tlb_batched_pending (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
