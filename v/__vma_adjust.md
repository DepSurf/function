# Function: <code>__vma_adjust</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f09d0)
Location: mm/mmap.c:664
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
ffffffff811f09d0-ffffffff811f1242: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fb850)
Location: mm/mmap.c:680
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
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
ffffffff811fb850-ffffffff811fc081: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81213d90)
Location: mm/mmap.c:681
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
ffffffff81213d90-ffffffff812145c1: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81234cb0)
Location: mm/mmap.c:690
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81234cb0-ffffffff81235479: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81248430)
Location: mm/mmap.c:714
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81248430-ffffffff81248bf9: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125a680)
Location: mm/mmap.c:716
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8125a680-ffffffff8125ae91: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81268c60)
Location: mm/mmap.c:717
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81268c60-ffffffff8126959a: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81299400)
Location: mm/mmap.c:697
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__do_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff81299400-ffffffff81299e3a: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a45c0)
Location: mm/mmap.c:739
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__do_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812a45c0-ffffffff812a5075: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a9d30)
Location: mm/mmap.c:743
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__do_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812a9d30-ffffffff812aa7dd: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812eb330)
Location: mm/mmap.c:740
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__do_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812eb330-ffffffff812ebdfb: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134e100)
Location: mm/mmap.c:746
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__do_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8134e100-ffffffff8134ec4e: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c75d0)
Location: mm/mmap.c:615
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__do_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff813c75d0-ffffffff813c815a: __vma_adjust (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010300218)
Location: mm/mmap.c:717
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__arm64_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffff800010300218-ffff800010300a64: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c051ec80)
Location: mm/mmap.c:717
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__se_sys_mremap
  - fs/exec.c:setup_arg_pages
  - fs/exec.c:setup_arg_pages
```
**Symbols:**

```
c051ec80-c051f614: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cc0b0)
Location: mm/mmap.c:717
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__se_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
c0000000003cc0b0-c0000000003ccb6c: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020dba6)
Location: mm/mmap.c:717
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__se_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffe00020dba6-ffffffe00020e170: __vma_adjust (STB_GLOBAL)
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
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812612b0)
Location: mm/mmap.c:717
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812612b0-ffffffff81261bea: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812536d0)
Location: mm/mmap.c:717
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff812536d0-ffffffff8125400a: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125f050)
Location: mm/mmap.c:717
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8125f050-ffffffff8125f98a: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __vma_adjust(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, long unsigned int pgoff, struct vm_area_struct *insert, struct vm_area_struct *expand);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126ea20)
Location: mm/mmap.c:717
Inline: False
Direct callers:
  - mm/mmap.c:__split_vma
  - mm/mmap.c:__split_vma
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - fs/exec.c:shift_arg_pages
  - fs/exec.c:shift_arg_pages
```
**Symbols:**

```
ffffffff8126ea20-ffffffff8126f35a: __vma_adjust (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
