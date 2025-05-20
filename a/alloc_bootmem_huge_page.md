# Function: <code>alloc_bootmem_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int alloc_bootmem_huge_page(struct hstate *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81f8bb4e)
Location: mm/hugetlb.c:1953
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff81f8bb4e-ffffffff81f8bc0f: alloc_bootmem_huge_page (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int alloc_bootmem_huge_page(struct hstate *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81fb5817)
Location: mm/hugetlb.c:2000
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff81fb5817-ffffffff81fb58da: alloc_bootmem_huge_page (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int alloc_bootmem_huge_page(struct hstate *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81ff2190)
Location: mm/hugetlb.c:2106
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff81ff2190-ffffffff81ff2258: alloc_bootmem_huge_page (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int alloc_bootmem_huge_page(struct hstate *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff820d47ef)
Location: mm/hugetlb.c:2086
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
**Symbols:**

```
ffffffff820d47ef-ffffffff820d48bc: alloc_bootmem_huge_page (STB_WEAK)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int alloc_bootmem_huge_page(struct hstate *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/hugetlbpage.c (c000000001358098)
Location: arch/powerpc/mm/hugetlbpage.c:239
Inline: False
```
**Symbols:**

```
c000000001358098-c0000000013580ec: alloc_bootmem_huge_page (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
