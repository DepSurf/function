# Function: <code>add_huge_page_size</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
void add_huge_page_size(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/hugetlbpage.c (ffff800011438734)
Location: arch/arm64/mm/hugetlbpage.c:444
Inline: False
Direct callers:
  - arch/arm64/mm/hugetlbpage.c:setup_hugepagesz
  - arch/arm64/mm/hugetlbpage.c:hugetlbpage_init
  - arch/arm64/mm/hugetlbpage.c:hugetlbpage_init
  - arch/arm64/mm/hugetlbpage.c:hugetlbpage_init
  - arch/arm64/mm/hugetlbpage.c:hugetlbpage_init
```
**Symbols:**

```
ffff800011438734-ffff800011438780: add_huge_page_size (STB_LOCAL)
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
int add_huge_page_size(long long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/hugetlbpage.c (c000000001357c7c)
Location: arch/powerpc/mm/hugetlbpage.c:561
Inline: False
Direct callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlbpage_init
  - arch/powerpc/mm/hugetlbpage.c:hugepage_setup_sz
```
**Symbols:**

```
c000000001357c7c-c000000001357da0: add_huge_page_size (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
