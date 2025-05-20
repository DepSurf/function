# Function: <code>__vm_map_pages</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256100)
Location: mm/memory.c:1507
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff81256100-ffffffff8125619b: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264690)
Location: mm/memory.c:1512
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff81264690-ffffffff8126472b: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81293160)
Location: mm/memory.c:1675
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff81293160-ffffffff812931fb: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129da30)
Location: mm/memory.c:1849
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff8129da30-ffffffff8129dacb: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a3000)
Location: mm/memory.c:1867
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff812a3000-ffffffff812a309b: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e6350)
Location: mm/memory.c:1962
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff812e6350-ffffffff812e63eb: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813452f0)
Location: mm/memory.c:2055
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff813452f0-ffffffff813453a3: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bd560)
Location: mm/memory.c:2026
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff813bd560-ffffffff813bd613: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2230)
Location: mm/memory.c:2046
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff813f2230-ffffffff813f22e3: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141cec0)
Location: mm/memory.c:2069
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff8141cec0-ffffffff8141cf73: __vm_map_pages (STB_LOCAL)
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
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fb3b8)
Location: mm/memory.c:1512
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffff8000102fb3b8-ffff8000102fb474: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519c6c)
Location: mm/memory.c:1512
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
c0519c6c-c0519ce8: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c6270)
Location: mm/memory.c:1512
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
c0000000003c6270-c0000000003c6390: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020ab1e)
Location: mm/memory.c:1512
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffe00020ab1e-ffffffe00020abaa: __vm_map_pages (STB_LOCAL)
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
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125cce0)
Location: mm/memory.c:1512
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff8125cce0-ffffffff8125cd7b: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f1a0)
Location: mm/memory.c:1512
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff8124f1a0-ffffffff8124f23b: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125aa80)
Location: mm/memory.c:1512
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff8125aa80-ffffffff8125ab1b: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __vm_map_pages(struct vm_area_struct *vma, struct page **pages, long unsigned int num, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126a450)
Location: mm/memory.c:1512
Inline: False
Direct callers:
  - mm/memory.c:vm_map_pages_zero
  - mm/memory.c:vm_map_pages
```
**Symbols:**

```
ffffffff8126a450-ffffffff8126a4eb: __vm_map_pages (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
