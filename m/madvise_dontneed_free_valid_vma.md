# Function: <code>madvise_dontneed_free_valid_vma</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool madvise_dontneed_free_valid_vma(struct vm_area_struct *vma, long unsigned int start, long unsigned int *end, int behavior);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff81375459)
Location: mm/madvise.c:792
Inline: True
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81375420-ffffffff813754e1: madvise_dontneed_free_valid_vma (STB_LOCAL)
ffffffff81e70760-ffffffff81e707c2: madvise_dontneed_free_valid_vma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool madvise_dontneed_free_valid_vma(struct vm_area_struct *vma, long unsigned int start, long unsigned int *end, int behavior);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff813f338c)
Location: mm/madvise.c:812
Inline: True
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff813f3350-ffffffff813f3418: madvise_dontneed_free_valid_vma (STB_LOCAL)
ffffffff820657d2-ffffffff8206589c: madvise_dontneed_free_valid_vma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool madvise_dontneed_free_valid_vma(struct vm_area_struct *vma, long unsigned int start, long unsigned int *end, int behavior);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff81426ddf)
Location: mm/madvise.c:826
Inline: True
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81426da0-ffffffff81426e6e: madvise_dontneed_free_valid_vma (STB_LOCAL)
ffffffff820e4fc3-ffffffff820e5099: madvise_dontneed_free_valid_vma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool madvise_dontneed_free_valid_vma(struct vm_area_struct *vma, long unsigned int start, long unsigned int *end, int behavior);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/madvise.c (ffffffff814600af)
Location: mm/madvise.c:820
Inline: True
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81460070-ffffffff8146013e: madvise_dontneed_free_valid_vma (STB_LOCAL)
ffffffff821c21a0-ffffffff821c2276: madvise_dontneed_free_valid_vma.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
