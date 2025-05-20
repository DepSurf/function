# Function: <code>hugetlb_acct_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811db370)
Location: mm/hugetlb.c:2920
Inline: False
Direct callers:
  - mm/hugetlb.c:hugepage_subpool_put_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugepage_new_subpool
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_unreserve_pages
```
**Symbols:**

```
ffffffff811db370-ffffffff811db6a0: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f95c0)
Location: mm/hugetlb.c:2947
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_subpool_put_pages
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff811f95c0-ffffffff811f9942: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81209ed0)
Location: mm/hugetlb.c:3053
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_subpool_put_pages
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff81209ed0-ffffffff8120a220: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812153f0)
Location: mm/hugetlb.c:3036
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff812153f0-ffffffff8121571c: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8122ffc0)
Location: mm/hugetlb.c:3044
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff8122ffc0-ffffffff8123032e: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812533d0)
Location: mm/hugetlb.c:3059
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff812533d0-ffffffff8125373e: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81267310)
Location: mm/hugetlb.c:3053
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff81267310-ffffffff8126767e: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81282d70)
Location: mm/hugetlb.c:3121
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff81282d70-ffffffff812830e8: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81292890)
Location: mm/hugetlb.c:3238
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff81292890-ffffffff81292c08: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c5e30)
Location: mm/hugetlb.c:3649
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff812c5e30-ffffffff812c5f30: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d1a80)
Location: mm/hugetlb.c:3613
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff812d1a80-ffffffff812d1b09: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812dab5a)
Location: mm/hugetlb.c:3781
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff812d8550-ffffffff812d86b7: hugetlb_acct_memory.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81321b69)
Location: mm/hugetlb.c:4067
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff8131f300-ffffffff8131f46a: hugetlb_acct_memory.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8138ec67)
Location: mm/hugetlb.c:4519
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff8138bd30-ffffffff8138bea1: hugetlb_acct_memory.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8140d737)
Location: mm/hugetlb.c:4716
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff81409590-ffffffff81409735: hugetlb_acct_memory.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff81440ae7)
Location: mm/hugetlb.c:4791
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff8143cbf0-ffffffff8143cd95: hugetlb_acct_memory.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8147ac17)
Location: mm/hugetlb.c:5049
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff81477370-ffffffff81477515: hugetlb_acct_memory.part.0 (STB_LOCAL)
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
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010330190)
Location: mm/hugetlb.c:3238
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffff800010330190-ffff800010330618: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000408cc0)
Location: mm/hugetlb.c:3238
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
c000000000408cc0-c000000000409338: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022d662)
Location: mm/hugetlb.c:3238
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffe00022d662-ffffffe00022d980: hugetlb_acct_memory (STB_LOCAL)
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
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128ae70)
Location: mm/hugetlb.c:3238
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff8128ae70-ffffffff8128b1e8: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127cca0)
Location: mm/hugetlb.c:3238
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff8127cca0-ffffffff8127d018: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81288c80)
Location: mm/hugetlb.c:3238
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff81288c80-ffffffff81288ff8: hugetlb_acct_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hugetlb_acct_memory(struct hstate *h, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81298a30)
Location: mm/hugetlb.c:3238
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_fix_reserve_counts
  - mm/hugetlb.c:hugepage_put_subpool
  - mm/hugetlb.c:hugepage_new_subpool
```
**Symbols:**

```
ffffffff81298a30-ffffffff81298dc9: hugetlb_acct_memory (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
