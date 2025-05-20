# Function: <code>vma_adjust</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c4c80)
Location: mm/mmap.c:727
Inline: False
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:SyS_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811c4c80-ffffffff811c5413: vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e0aa0)
Location: mm/mmap.c:619
Inline: False
Direct callers:
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:SyS_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff811e0aa0-ffffffff811e128a: vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f1365)
Location: include/linux/mm.h:1983
Inline: True
```
```
In mm/mremap.c (ffffffff811f6899)
Location: include/linux/mm.h:1983
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
```
In fs/exec.c (ffffffff8124ba27)
Location: include/linux/mm.h:1983
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fcd47)
Location: include/linux/mm.h:2054
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff81201656)
Location: include/linux/mm.h:2054
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
```
In fs/exec.c (ffffffff81257b71)
Location: include/linux/mm.h:2054
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812152d4)
Location: include/linux/mm.h:2163
Inline: True
```
```
In mm/mremap.c (ffffffff8121a016)
Location: include/linux/mm.h:2163
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
```
In fs/exec.c (ffffffff81279e41)
Location: include/linux/mm.h:2163
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8123611f)
Location: include/linux/mm.h:2252
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff8123b988)
Location: include/linux/mm.h:2252
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In fs/exec.c (ffffffff812a0a21)
Location: include/linux/mm.h:2252
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124993f)
Location: include/linux/mm.h:2323
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff8124fd85)
Location: include/linux/mm.h:2323
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In fs/exec.c (ffffffff812b5a21)
Location: include/linux/mm.h:2323
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125bc6a)
Location: include/linux/mm.h:2318
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff81262107)
Location: include/linux/mm.h:2318
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In fs/exec.c (ffffffff812d27a7)
Location: include/linux/mm.h:2318
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126a35a)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff812708d7)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In fs/exec.c (ffffffff812e42b7)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129adaa)
Location: include/linux/mm.h:2537
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff812a133b)
Location: include/linux/mm.h:2537
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In fs/exec.c (ffffffff8131b505)
Location: include/linux/mm.h:2537
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a5f6a)
Location: include/linux/mm.h:2547
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff812acb8b)
Location: include/linux/mm.h:2547
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In fs/exec.c (ffffffff81326b35)
Location: include/linux/mm.h:2547
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ab2cd)
Location: include/linux/mm.h:2543
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff812b1e7f)
Location: include/linux/mm.h:2543
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In fs/exec.c (ffffffff8132cbd5)
Location: include/linux/mm.h:2543
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ec9aa)
Location: include/linux/mm.h:2572
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff812f3a65)
Location: include/linux/mm.h:2572
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In fs/exec.c (ffffffff8137a375)
Location: include/linux/mm.h:2572
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134fc9c)
Location: include/linux/mm.h:2650
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff81357817)
Location: include/linux/mm.h:2650
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In fs/exec.c (ffffffff813f9b96)
Location: include/linux/mm.h:2650
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c938f)
Location: include/linux/mm.h:2818
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff813d1f23)
Location: include/linux/mm.h:2818
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In fs/exec.c (ffffffff81483454)
Location: include/linux/mm.h:2818
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010301a80)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffff800010306b0c)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mremap.c:__arm64_sys_mremap
```
```
In fs/exec.c (ffff80001038bc44)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c052021c)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (c052470c)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
```
In fs/exec.c (c0573c7c)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:setup_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cdc88)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (c0000000003d4ca0)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
```
In fs/exec.c (c0000000004834fc)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020ec5c)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffe000212320)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
```
In fs/exec.c (ffffffe00025d21e)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812629aa)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff81268f27)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In fs/exec.c (ffffffff812dc897)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81254dca)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff8125b217)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In fs/exec.c (ffffffff812cd517)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126074a)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff81266cc7)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In fs/exec.c (ffffffff812da6a7)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8127011a)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
```
```
In mm/mremap.c (ffffffff81276667)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In fs/exec.c (ffffffff812eb557)
Location: include/linux/mm.h:2290
Inline: True
Inline callers:
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
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
</ul>
