# Function: <code>__page_set_anon_rmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811ca540)
Location: mm/rmap.c:1079
Inline: True
Direct callers:
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
**Symbols:**

```
ffffffff811ca540-ffffffff811ca59f: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e6a40)
Location: mm/rmap.c:1118
Inline: True
Direct callers:
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff811e6a40-ffffffff811e6aaf: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f7de0)
Location: mm/rmap.c:1117
Inline: True
Direct callers:
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff811f7de0-ffffffff811f7e4f: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81203370)
Location: mm/rmap.c:1020
Inline: True
Direct callers:
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff81203370-ffffffff812033e0: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121beb0)
Location: mm/rmap.c:1024
Inline: True
Direct callers:
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff8121beb0-ffffffff8121bf1e: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123dce0)
Location: mm/rmap.c:1025
Inline: True
Direct callers:
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff8123dce0-ffffffff8123dd50: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81252260)
Location: mm/rmap.c:1027
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff81252260-ffffffff812522d0: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81264400)
Location: mm/rmap.c:1028
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff81264400-ffffffff8126446d: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81272c70)
Location: mm/rmap.c:1026
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff81272c70-ffffffff81272cdd: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a6b3f)
Location: mm/rmap.c:1039
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
Direct callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff812a3a70-ffffffff812a3ae2: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b1fdf)
Location: mm/rmap.c:1039
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
Direct callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff812af320-ffffffff812af392: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b76af)
Location: mm/rmap.c:1043
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
Direct callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff812b4800-ffffffff812b4870: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f9dbf)
Location: mm/rmap.c:1044
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
Direct callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff812f63e0-ffffffff812f6450: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81360091)
Location: mm/rmap.c:1129
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
Direct callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff8135b3c0-ffffffff8135b47a: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813dafff)
Location: mm/rmap.c:1146
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
Direct callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff813d6290-ffffffff813d6344: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct folio *folio, struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140f757)
Location: mm/rmap.c:1144
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
Direct callers:
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff8140abb0-ffffffff8140ac3f: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff8000103087c0)
Location: mm/rmap.c:1026
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffff8000103087c0-ffff80001030885c: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c05259dc)
Location: mm/rmap.c:1026
Inline: True
Direct callers:
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
c05259dc-c0525a44: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003d77e0)
Location: mm/rmap.c:1026
Inline: False
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
c0000000003d77e0-c0000000003d78a4: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe000212fee)
Location: mm/rmap.c:1026
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffe000212fee-ffffffe000213076: __page_set_anon_rmap (STB_LOCAL)
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
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126b2c0)
Location: mm/rmap.c:1026
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff8126b2c0-ffffffff8126b32d: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125d3a0)
Location: mm/rmap.c:1026
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff8125d3a0-ffffffff8125d40d: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81269060)
Location: mm/rmap.c:1026
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff81269060-ffffffff812690cd: __page_set_anon_rmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __page_set_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81278ba0)
Location: mm/rmap.c:1026
Inline: True
Direct callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:hugepage_add_anon_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:do_page_add_anon_rmap
```
**Symbols:**

```
ffffffff81278ba0-ffffffff81278c0d: __page_set_anon_rmap (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, vma, address, exclusive</code> ➡️ <code>folio, page, vma, address, exclusive</code>
</li>
</ul>
</details>
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
