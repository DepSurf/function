# Function: <code>do_page_add_anon_rmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811cae30)
Location: mm/rmap.c:1151
Inline: False
Direct callers:
  - mm/memory.c:handle_mm_fault
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff811cae30-ffffffff811caee7: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e7c60)
Location: mm/rmap.c:1191
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff811e7c60-ffffffff811e7d37: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f8fe0)
Location: mm/rmap.c:1190
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff811f8fe0-ffffffff811f90b7: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81203b90)
Location: mm/rmap.c:1093
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff81203b90-ffffffff81203c67: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121c900)
Location: mm/rmap.c:1097
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff8121c900-ffffffff8121c9d7: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123e690)
Location: mm/rmap.c:1098
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff8123e690-ffffffff8123e76f: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81252c20)
Location: mm/rmap.c:1100
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff81252c20-ffffffff81252cff: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81264fa0)
Location: mm/rmap.c:1101
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff81264fa0-ffffffff81265093: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81273830)
Location: mm/rmap.c:1099
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff81273830-ffffffff81273923: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a4a00)
Location: mm/rmap.c:1111
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff812a4a00-ffffffff812a4bfb: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b0190)
Location: mm/rmap.c:1117
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff812b0190-ffffffff812b02a5: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b5790)
Location: mm/rmap.c:1120
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff812b5790-ffffffff812b58a3: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f7420)
Location: mm/rmap.c:1121
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff812f7420-ffffffff812f7533: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff800010309370)
Location: mm/rmap.c:1099
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffff800010309370-ffff800010309498: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0526000)
Location: mm/rmap.c:1099
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
c0526000-c0526108: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003d88c0)
Location: mm/rmap.c:1099
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
c0000000003d88c0-c0000000003d8a78: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe0002137e4)
Location: mm/rmap.c:1099
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffe0002137e4-ffffffe0002138c4: do_page_add_anon_rmap (STB_GLOBAL)
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
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126be80)
Location: mm/rmap.c:1099
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff8126be80-ffffffff8126bf73: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125def0)
Location: mm/rmap.c:1099
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff8125def0-ffffffff8125dfe3: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81269c20)
Location: mm/rmap.c:1099
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff81269c20-ffffffff81269d13: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81279590)
Location: mm/rmap.c:1099
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/rmap.c:page_add_anon_rmap
```
**Symbols:**

```
ffffffff81279590-ffffffff81279683: do_page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int exclusive</code>
</li>
</ul>
</details>
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
