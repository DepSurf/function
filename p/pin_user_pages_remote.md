# Function: <code>pin_user_pages_remote</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int pin_user_pages_remote(struct task_struct *tsk, struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128a830)
Location: mm/gup.c:2994
Inline: False
Direct callers:
  - mm/process_vm_access.c:process_vm_rw_single_vec
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff8128a830-ffffffff8128a85f: pin_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int pin_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812944e0)
Location: mm/gup.c:2781
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn
```
**Symbols:**

```
ffffffff812944e0-ffffffff81294509: pin_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int pin_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81299f30)
Location: mm/gup.c:2847
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
**Symbols:**

```
ffffffff81299f30-ffffffff81299f59: pin_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int pin_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812da8a0)
Location: mm/gup.c:2942
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
**Symbols:**

```
ffffffff812da8a0-ffffffff812da8c9: pin_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int pin_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133a380)
Location: mm/gup.c:3097
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
**Symbols:**

```
ffffffff8133a380-ffffffff8133a3ee: pin_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int pin_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, struct vm_area_struct **vmas, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b1d50)
Location: mm/gup.c:3123
Inline: False
```
**Symbols:**

```
ffffffff813b1d50-ffffffff813b1dc6: pin_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int pin_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e6990)
Location: mm/gup.c:3330
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
**Symbols:**

```
ffffffff813e6990-ffffffff813e6a66: pin_user_pages_remote (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int pin_user_pages_remote(struct mm_struct *mm, long unsigned int start, long unsigned int nr_pages, unsigned int gup_flags, struct page **pages, int *locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81411630)
Location: mm/gup.c:3348
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
**Symbols:**

```
ffffffff81411630-ffffffff814116fe: pin_user_pages_remote (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, start, nr_pages, gup_flags, pages, vmas, locked</code> ➡️ <code>mm, start, nr_pages, gup_flags, pages, vmas, locked</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>struct vm_area_struct **vmas</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, start, nr_pages, gup_flags, pages, vmas, locked</code> ➡️ <code>mm, start, nr_pages, gup_flags, pages, locked</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
