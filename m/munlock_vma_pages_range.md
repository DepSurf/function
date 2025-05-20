# Function: <code>munlock_vma_pages_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811c32c0)
Location: mm/mlock.c:422
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:do_munmap
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:exit_mmap
```
**Symbols:**

```
ffffffff811c32c0-ffffffff811c3590: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811df000)
Location: mm/mlock.c:434
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:do_munmap
```
**Symbols:**

```
ffffffff811df000-ffffffff811df368: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811eee20)
Location: mm/mlock.c:437
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:do_munmap
```
**Symbols:**

```
ffffffff811eee20-ffffffff811ef1d5: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811f9dd0)
Location: mm/mlock.c:438
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:do_munmap
```
**Symbols:**

```
ffffffff811f9dd0-ffffffff811fa0f6: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81212220)
Location: mm/mlock.c:439
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:do_munmap
```
**Symbols:**

```
ffffffff81212220-ffffffff81212625: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81232f60)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:do_munmap
```
**Symbols:**

```
ffffffff81232f60-ffffffff81233345: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81246730)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff81246730-ffffffff81246b16: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81258990)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff81258990-ffffffff81258d25: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81266e60)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff81266e60-ffffffff812671f5: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812970e0)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff812970e0-ffffffff8129732f: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a2090)
Location: mm/mlock.c:421
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff812a2090-ffffffff812a22de: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a7920)
Location: mm/mlock.c:420
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff812a7920-ffffffff812a7b6e: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812e8f40)
Location: mm/mlock.c:421
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff812e8f40-ffffffff812e91ae: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
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
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffff8000102fe0d8)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffff8000102fe0d8-ffff8000102fe42c: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c051d24c)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
c051d24c-c051d428: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c0000000003c97c0)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
c0000000003c97c0-c0000000003c9d58: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffe00020c72e)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffe00020c72e-ffffffe00020c90a: munlock_vma_pages_range (STB_GLOBAL)
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
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125f4b0)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff8125f4b0-ffffffff8125f845: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812518d0)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff812518d0-ffffffff81251c65: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125d250)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff8125d250-ffffffff8125d5e5: munlock_vma_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void munlock_vma_pages_range(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8126cc40)
Location: mm/mlock.c:445
Inline: False
Direct callers:
  - mm/mlock.c:mlock_fixup
  - mm/mmap.c:exit_mmap
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__do_munmap
```
**Symbols:**

```
ffffffff8126cc40-ffffffff8126cfc9: munlock_vma_pages_range (STB_GLOBAL)
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
