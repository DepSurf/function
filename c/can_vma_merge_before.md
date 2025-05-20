# Function: <code>can_vma_merge_before</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c43c0)
Location: mm/mmap.c:975
Inline: True
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff811c43c0-ffffffff811c4444: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e02c0)
Location: mm/mmap.c:877
Inline: True
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff811e02c0-ffffffff811e0348: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f0210)
Location: mm/mmap.c:1006
Inline: True
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff811f0210-ffffffff811f0298: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff811fc11e)
Location: mm/mmap.c:1022
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff811fb0d0-ffffffff811fb120: can_vma_merge_before.part.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff8121465e)
Location: mm/mmap.c:1023
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff812135f0-ffffffff81213640: can_vma_merge_before.part.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812346b0)
Location: mm/mmap.c:1032
Inline: True
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff812346b0-ffffffff81234738: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff81248c97)
Location: mm/mmap.c:1056
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff81247e60-ffffffff81247eb7: can_vma_merge_before.part.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff8125af43)
Location: mm/mmap.c:1058
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff8125a080-ffffffff8125a0de: can_vma_merge_before.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff81269643)
Location: mm/mmap.c:1059
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff81268530-ffffffff8126858e: can_vma_merge_before.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81298ce0)
Location: mm/mmap.c:1037
Inline: True
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff81298ce0-ffffffff81298d68: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a3e60)
Location: mm/mmap.c:1078
Inline: True
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff812a3e60-ffffffff812a3ee8: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a95c0)
Location: mm/mmap.c:1082
Inline: True
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff812a95c0-ffffffff812a9656: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812eac00)
Location: mm/mmap.c:1079
Inline: True
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff812eac00-ffffffff812eac96: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134d8e0)
Location: mm/mmap.c:1088
Inline: False
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff8134d8e0-ffffffff8134d9fb: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c6bc0)
Location: mm/mmap.c:918
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff813c6bc0-ffffffff813c6ccc: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fb050)
Location: mm/mmap.c:781
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff813fb050-ffffffff813fb160: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool can_vma_merge_before(struct vm_area_struct *vma, long unsigned int vm_flags, struct anon_vma *anon_vma, struct file *file, long unsigned int vm_pgoff, struct vm_userfaultfd_ctx vm_userfaultfd_ctx, struct anon_vma_name *anon_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81426e30)
Location: mm/mmap.c:773
Inline: False
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff81426e30-ffffffff81426f40: can_vma_merge_before (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffff800010300b18)
Location: mm/mmap.c:1059
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffff8000102ff730-ffff8000102ff7ac: can_vma_merge_before.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (c051f694)
Location: mm/mmap.c:1059
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
c051e488-c051e4f8: can_vma_merge_before.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (c0000000003ccc58)
Location: mm/mmap.c:1059
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
c0000000003cb640-c0000000003cb6b8: can_vma_merge_before.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffe00020e1de)
Location: mm/mmap.c:1059
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffe00020d630-ffffffe00020d690: can_vma_merge_before.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff81261c93)
Location: mm/mmap.c:1059
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff81260b80-ffffffff81260bde: can_vma_merge_before.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff812540b3)
Location: mm/mmap.c:1059
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff81252fa0-ffffffff81252ffe: can_vma_merge_before.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff8125fa33)
Location: mm/mmap.c:1059
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff8125e920-ffffffff8125e97e: can_vma_merge_before.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff8126f403)
Location: mm/mmap.c:1059
Inline: True
Inline callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
```
**Symbols:**

```
ffffffff8126e2f0-ffffffff8126e34e: can_vma_merge_before.part.0 (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct anon_vma_name *anon_name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
