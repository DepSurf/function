# Function: <code>uffd_wp_range</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void uffd_wp_range(struct mm_struct *dst_mm, struct vm_area_struct *dst_vma, long unsigned int start, long unsigned int len, bool enable_wp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff813e6050)
Location: mm/userfaultfd.c:706
Inline: False
Direct callers:
  - mm/userfaultfd.c:mwriteprotect_range
```
**Symbols:**

```
ffffffff813e6050-ffffffff813e6141: uffd_wp_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uffd_wp_range(struct mm_struct *dst_mm, struct vm_area_struct *dst_vma, long unsigned int start, long unsigned int len, bool enable_wp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff8146db00)
Location: mm/userfaultfd.c:727
Inline: False
Direct callers:
  - mm/userfaultfd.c:mwriteprotect_range
```
**Symbols:**

```
ffffffff8146db00-ffffffff8146dbf1: uffd_wp_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int uffd_wp_range(struct vm_area_struct *dst_vma, long unsigned int start, long unsigned int len, bool enable_wp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff814a2520)
Location: mm/userfaultfd.c:705
Inline: False
Direct callers:
  - mm/userfaultfd.c:mwriteprotect_range
```
**Symbols:**

```
ffffffff814a2520-ffffffff814a2600: uffd_wp_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int uffd_wp_range(struct vm_area_struct *dst_vma, long unsigned int start, long unsigned int len, bool enable_wp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff814d25e0)
Location: mm/userfaultfd.c:767
Inline: False
Direct callers:
  - mm/userfaultfd.c:mwriteprotect_range
  - fs/userfaultfd.c:userfaultfd_unregister
  - fs/proc/task_mmu.c:pagemap_scan_pte_hole
```
**Symbols:**

```
ffffffff814d25e0-ffffffff814d26c0: uffd_wp_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mm_struct *dst_mm</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_mm, dst_vma, start, len, enable_wp</code> ➡️ <code>dst_vma, start, len, enable_wp</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
