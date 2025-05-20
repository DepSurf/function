# Function: <code>faultin_vma_page_range</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int faultin_vma_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, bool write, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812db8d0)
Location: mm/gup.c:1542
Inline: False
```
**Symbols:**

```
ffffffff812db8d0-ffffffff812db93d: faultin_vma_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int faultin_vma_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, bool write, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133b680)
Location: mm/gup.c:1574
Inline: False
Direct callers:
  - mm/madvise.c:madvise_populate
```
**Symbols:**

```
ffffffff8133b680-ffffffff8133b709: faultin_vma_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int faultin_vma_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, bool write, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b3230)
Location: mm/gup.c:1555
Inline: False
Direct callers:
  - mm/madvise.c:madvise_populate
```
**Symbols:**

```
ffffffff813b3230-ffffffff813b32b9: faultin_vma_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int faultin_vma_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, bool write, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e8020)
Location: mm/gup.c:1677
Inline: False
Direct callers:
  - mm/madvise.c:madvise_populate
```
**Symbols:**

```
ffffffff813e8020-ffffffff813e80a2: faultin_vma_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int faultin_vma_page_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, bool write, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81412c90)
Location: mm/gup.c:1703
Inline: False
Direct callers:
  - mm/madvise.c:madvise_populate
```
**Symbols:**

```
ffffffff81412c90-ffffffff81412d12: faultin_vma_page_range (STB_GLOBAL)
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
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
