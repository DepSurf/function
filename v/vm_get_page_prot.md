# Function: <code>vm_get_page_prot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c3e90)
Location: mm/mmap.c:85
Inline: True
Inline callers:
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:__install_special_mapping
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff811c3e90-ffffffff811c3ea6: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811dfcc0)
Location: mm/mmap.c:97
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff811dfcc0-ffffffff811dfd54: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811efc10)
Location: mm/mmap.c:102
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff811efc10-ffffffff811efca4: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fd65d)
Location: mm/mmap.c:102
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff811fab30-ffffffff811fab5d: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81215bfd)
Location: mm/mmap.c:103
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff81213040-ffffffff8121306d: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81236a65)
Location: mm/mmap.c:110
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff81233fd0-ffffffff81234008: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124a315)
Location: mm/mmap.c:110
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff81247780-ffffffff812477b8: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125c65a)
Location: mm/mmap.c:112
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff81259990-ffffffff812599cd: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126adba)
Location: mm/mmap.c:106
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff81267e60-ffffffff81267e9d: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129cfda)
Location: mm/mmap.c:109
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mwriteprotect_range
  - fs/exec.c:__bprm_mm_init
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff81297ea0-ffffffff81297edd: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a83da)
Location: mm/mmap.c:109
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mwriteprotect_range
  - fs/exec.c:__bprm_mm_init
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
**Symbols:**

```
ffffffff812a3040-ffffffff812a307d: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812abdea)
Location: mm/mmap.c:115
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mwriteprotect_range
  - fs/exec.c:__bprm_mm_init
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
**Symbols:**

```
ffffffff812a88a0-ffffffff812a88dd: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ed4ea)
Location: mm/mmap.c:115
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - mm/userfaultfd.c:mwriteprotect_range
  - mm/userfaultfd.c:mwriteprotect_range
  - fs/exec.c:__bprm_mm_init
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
**Symbols:**

```
ffffffff812e9f10-ffffffff812e9f4d: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgprot.c (ffffffff810af6a0)
Location: arch/x86/mm/pgprot.c:7
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
  - mm/userfaultfd.c:uffd_wp_range
  - mm/userfaultfd.c:uffd_wp_range
  - fs/exec.c:alloc_bprm
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
**Symbols:**

```
ffffffff810af6a0-ffffffff810af701: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgprot.c (ffffffff810c9b40)
Location: arch/x86/mm/pgprot.c:35
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
  - mm/userfaultfd.c:uffd_wp_range
  - mm/userfaultfd.c:uffd_wp_range
  - fs/exec.c:alloc_bprm
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
**Symbols:**

```
ffffffff810c9b40-ffffffff810c9b97: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgprot.c (ffffffff810cd1b0)
Location: arch/x86/mm/pgprot.c:35
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
  - fs/exec.c:alloc_bprm
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
**Symbols:**

```
ffffffff810cd1b0-ffffffff810cd207: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgprot.c (ffffffff810d5890)
Location: arch/x86/mm/pgprot.c:35
Inline: False
Direct callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
  - mm/mprotect.c:mprotect_fixup
  - fs/exec.c:alloc_bprm
  - drivers/video/fbdev/core/fb_io_fops.c:fb_io_mmap
  - drivers/gpu/drm/drm_gem.c:drm_gem_mmap_obj
```
**Symbols:**

```
ffffffff810d5890-ffffffff810d58e7: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000103024c8)
Location: mm/mmap.c:106
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vm_pgprot_modify
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
**Symbols:**

```
ffff8000102ff070-ffff8000102ff0a4: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0520bb4)
Location: mm/mmap.c:106
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - fs/exec.c:__do_execve_file
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
**Symbols:**

```
c051de64-c051de8c: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003ce99c)
Location: mm/mmap.c:106
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vm_pgprot_modify
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
c0000000003cabf0-c0000000003cac20: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020f416)
Location: mm/mmap.c:106
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - fs/exec.c:__do_execve_file
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
```
**Symbols:**

```
ffffffe00020d0e0-ffffffe00020d110: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126340a)
Location: mm/mmap.c:106
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff812604b0-ffffffff812604ed: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125582a)
Location: mm/mmap.c:106
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff812528d0-ffffffff8125290d: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812611aa)
Location: mm/mmap.c:106
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff8125e250-ffffffff8125e28d: vm_get_page_prot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
pgprot_t vm_get_page_prot(long unsigned int vm_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81270b7a)
Location: mm/mmap.c:106
Inline: True
Inline callers:
  - mm/mmap.c:__install_special_mapping
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:mmap_region
  - mm/mmap.c:vma_wants_writenotify
  - mm/mmap.c:vma_set_page_prot
  - mm/mmap.c:vma_set_page_prot
Direct callers:
  - mm/mprotect.c:mprotect_fixup
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/char/agp/frontend.c:agp_create_segment
```
**Symbols:**

```
ffffffff8126dc30-ffffffff8126dc6d: vm_get_page_prot (STB_GLOBAL)
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
