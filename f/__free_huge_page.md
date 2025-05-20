# Function: <code>__free_huge_page</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __free_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81292cc0)
Location: mm/hugetlb.c:1259
Inline: False
Direct callers:
  - mm/hugetlb.c:free_hpage_workfn
```
**Symbols:**

```
ffffffff81292cc0-ffffffff81292ee0: __free_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __free_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c5fe0)
Location: mm/hugetlb.c:1398
Inline: False
Direct callers:
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
**Symbols:**

```
ffffffff812c5fe0-ffffffff812c6242: __free_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __free_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d1bc0)
Location: mm/hugetlb.c:1425
Inline: False
Direct callers:
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
```
**Symbols:**

```
ffffffff812d1bc0-ffffffff812d1e35: __free_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
void __free_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010330730)
Location: mm/hugetlb.c:1259
Inline: False
Direct callers:
  - mm/hugetlb.c:free_hpage_workfn
```
**Symbols:**

```
ffff800010330730-ffff800010330a40: __free_huge_page (STB_LOCAL)
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
void __free_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c000000000409490)
Location: mm/hugetlb.c:1259
Inline: False
Direct callers:
  - mm/hugetlb.c:free_hpage_workfn
```
**Symbols:**

```
c000000000409490-c000000000409858: __free_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __free_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022da62)
Location: mm/hugetlb.c:1259
Inline: False
Direct callers:
  - mm/hugetlb.c:free_hpage_workfn
```
**Symbols:**

```
ffffffe00022da62-ffffffe00022dc66: __free_huge_page (STB_LOCAL)
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
void __free_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128b2a0)
Location: mm/hugetlb.c:1259
Inline: False
Direct callers:
  - mm/hugetlb.c:free_hpage_workfn
```
**Symbols:**

```
ffffffff8128b2a0-ffffffff8128b4c0: __free_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __free_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127d0d0)
Location: mm/hugetlb.c:1259
Inline: False
Direct callers:
  - mm/hugetlb.c:free_hpage_workfn
```
**Symbols:**

```
ffffffff8127d0d0-ffffffff8127d2f0: __free_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __free_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812890b0)
Location: mm/hugetlb.c:1259
Inline: False
Direct callers:
  - mm/hugetlb.c:free_hpage_workfn
```
**Symbols:**

```
ffffffff812890b0-ffffffff812892d0: __free_huge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __free_huge_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81298e90)
Location: mm/hugetlb.c:1259
Inline: False
Direct callers:
  - mm/hugetlb.c:free_hpage_workfn
```
**Symbols:**

```
ffffffff81298e90-ffffffff812990ae: __free_huge_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
