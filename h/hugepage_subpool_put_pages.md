# Function: <code>hugepage_subpool_put_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int hugepage_subpool_put_pages(struct hugepage_subpool *spool, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811db6a0)
Location: mm/hugetlb.c:173
Inline: False
Direct callers:
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_unreserve_pages
```
**Symbols:**

```
ffffffff811db6a0-ffffffff811db73a: hugepage_subpool_put_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int hugepage_subpool_put_pages(struct hugepage_subpool *spool, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f9950)
Location: mm/hugetlb.c:174
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff811f9950-ffffffff811f99ef: hugepage_subpool_put_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int hugepage_subpool_put_pages(struct hugepage_subpool *spool, long int delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120a220)
Location: mm/hugetlb.c:174
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff8120a220-ffffffff8120a2bf: hugepage_subpool_put_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81217c52)
Location: mm/hugetlb.c:176
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff81215720-ffffffff812157b6: hugepage_subpool_put_pages.part.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812329b2)
Location: mm/hugetlb.c:177
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff81230330-ffffffff812303c6: hugepage_subpool_put_pages.part.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81255a25)
Location: mm/hugetlb.c:176
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff81253740-ffffffff812537de: hugepage_subpool_put_pages.part.69 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81269e05)
Location: mm/hugetlb.c:176
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff81267680-ffffffff8126771e: hugepage_subpool_put_pages.part.69 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81284f36)
Location: mm/hugetlb.c:178
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff812830f0-ffffffff81283193: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff81294ad6)
Location: mm/hugetlb.c:179
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
ffffffff81292c10-ffffffff81292cb3: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812c80a6)
Location: mm/hugetlb.c:185
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
ffffffff812c5f30-ffffffff812c5fd3: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff812d3c66)
Location: mm/hugetlb.c:202
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
ffffffff812d1b10-ffffffff812d1bb3: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff812dab47)
Location: mm/hugetlb.c:199
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff812d86c0-ffffffff812d878d: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff81321b56)
Location: mm/hugetlb.c:201
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff8131f500-ffffffff8131f5cd: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8138ec57)
Location: mm/hugetlb.c:215
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff8138bf50-ffffffff8138c011: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8140d727)
Location: mm/hugetlb.c:215
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff81409800-ffffffff814098c1: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff81440ad7)
Location: mm/hugetlb.c:215
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:free_huge_page
```
**Symbols:**

```
ffffffff8143ce60-ffffffff8143cf21: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
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
In mm/hugetlb.c (ffffffff8147ac07)
Location: mm/hugetlb.c:217
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:free_huge_folio
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:free_huge_folio
```
**Symbols:**

```
ffffffff81477610-ffffffff814776d1: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffff80001033344c)
Location: mm/hugetlb.c:179
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
ffff800010330618-ffff80001033072c: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (c0000000004102ec)
Location: mm/hugetlb.c:179
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
c000000000409340-c000000000409490: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffe00022f9e4)
Location: mm/hugetlb.c:179
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
ffffffe00022d980-ffffffe00022da62: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8128d0b6)
Location: mm/hugetlb.c:179
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
ffffffff8128b1f0-ffffffff8128b293: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8127eec6)
Location: mm/hugetlb.c:179
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
ffffffff8127d020-ffffffff8127d0c3: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8128aec6)
Location: mm/hugetlb.c:179
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
ffffffff81289000-ffffffff812890a3: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffff8129ace4)
Location: mm/hugetlb.c:179
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
Direct callers:
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__free_huge_page
```
**Symbols:**

```
ffffffff81298dd0-ffffffff81298e81: hugepage_subpool_put_pages.part.0 (STB_LOCAL)
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
</ul>
