# Function: <code>get_unmapped_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c4450)
Location: mm/mmap.c:2007
Inline: True
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_mmap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff811c4450-ffffffff811c4569: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e0380)
Location: mm/mmap.c:1896
Inline: True
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_mmap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff811e0380-ffffffff811e04b3: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f02d0)
Location: mm/mmap.c:2049
Inline: True
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk
  - mm/mmap.c:do_mmap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff811f02d0-ffffffff811f03e3: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fb150)
Location: mm/mmap.c:2071
Inline: True
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff811fb150-ffffffff811fb26f: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81213670)
Location: mm/mmap.c:2087
Inline: True
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
  - mm/mremap.c:SyS_mremap
```
**Symbols:**

```
ffffffff81213670-ffffffff81213792: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812344a0)
Location: mm/mmap.c:2147
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:vma_expandable
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812344a0-ffffffff812345bc: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81247c50)
Location: mm/mmap.c:2182
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:vma_expandable
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81247c50-ffffffff81247d6c: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81259e70)
Location: mm/mmap.c:2183
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:vma_expandable
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81259e70-ffffffff81259f8d: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81268320)
Location: mm/mmap.c:2191
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:vma_expandable
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81268320-ffffffff8126843d: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81298b80)
Location: mm/mmap.c:2190
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:xol_add_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81298b80-ffffffff81298cd6: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a3d00)
Location: mm/mmap.c:2256
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:xol_add_vma
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812a3d00-ffffffff812a3e56: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a9490)
Location: mm/mmap.c:2260
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812a9490-ffffffff812a95b3: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812eaad0)
Location: mm/mmap.c:2229
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff812eaad0-ffffffff812eabf3: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8134d5a0)
Location: mm/mmap.c:2257
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff8134d5a0-ffffffff8134d6e8: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c6ce0)
Location: mm/mmap.c:1759
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:xol_add_vma
  - mm/mmap.c:do_mmap
  - mm/mmap.c:check_brk_limits
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff813c6ce0-ffffffff813c6e28: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fb170)
Location: mm/mmap.c:1787
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:xol_add_vma
  - mm/mmap.c:do_mmap
  - mm/mmap.c:check_brk_limits
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff813fb170-ffffffff813fb2bb: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff814270c0)
Location: mm/mmap.c:1814
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:xol_add_vma
  - mm/mmap.c:do_mmap
  - mm/mmap.c:check_brk_limits
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
**Symbols:**

```
ffffffff814270c0-ffffffff81427217: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000102ff4e0)
Location: mm/mmap.c:2191
Inline: False
Direct callers:
  - arch/arm64/kernel/vdso.c:arch_setup_additional_pages
  - arch/arm64/kernel/vdso.c:aarch32_setup_additional_pages
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:__arm64_sys_mremap
  - mm/mremap.c:__arm64_sys_mremap
```
**Symbols:**

```
ffff8000102ff4e0-ffff8000102ff61c: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (c05213c4)
Location: mm/mmap.c:2191
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
Direct callers:
  - arch/arm/kernel/process.c:arch_setup_additional_pages
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c051e598-c051e650: get_unmapped_area.part.0 (STB_LOCAL)
c051e650-c051e6ac: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cb330)
Location: mm/mmap.c:2191
Inline: False
Direct callers:
  - arch/powerpc/kernel/vdso.c:arch_setup_additional_pages
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
c0000000003cb330-c0000000003cb4b8: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020d4ba)
Location: mm/mmap.c:2191
Inline: False
Direct callers:
  - arch/riscv/kernel/vdso.c:arch_setup_additional_pages
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
  - mm/mremap.c:__se_sys_mremap
```
**Symbols:**

```
ffffffe00020d4ba-ffffffe00020d55c: get_unmapped_area (STB_GLOBAL)
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
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81260970)
Location: mm/mmap.c:2191
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:vma_expandable
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81260970-ffffffff81260a8d: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81252d90)
Location: mm/mmap.c:2191
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:vma_expandable
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff81252d90-ffffffff81252ead: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125e710)
Location: mm/mmap.c:2191
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:vma_expandable
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff8125e710-ffffffff8125e82d: get_unmapped_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int get_unmapped_area(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int pgoff, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126e160)
Location: mm/mmap.c:2191
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:map_vdso
  - kernel/events/uprobes.c:__create_xol_area
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mmap
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - mm/mremap.c:vma_expandable
  - mm/mremap.c:mremap_to
```
**Symbols:**

```
ffffffff8126e160-ffffffff8126e27d: get_unmapped_area (STB_GLOBAL)
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
