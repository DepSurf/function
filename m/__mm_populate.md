# Function: <code>__mm_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811bb650)
Location: mm/gup.c:930
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:do_mlock
  - mm/mlock.c:SyS_mlockall
  - mm/mmap.c:vm_brk
  - mm/mmap.c:SyS_brk
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mremap.c:SyS_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff811bb650-ffffffff811bb778: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811d60b0)
Location: mm/gup.c:1053
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_brk
  - mm/mremap.c:SyS_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff811d60b0-ffffffff811d61da: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811e6010)
Location: mm/gup.c:1057
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_brk
  - mm/mremap.c:SyS_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff811e6010-ffffffff811e613a: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811f0650)
Location: mm/gup.c:1138
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_brk
  - mm/mremap.c:SyS_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff811f0650-ffffffff811f078f: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81207c10)
Location: mm/gup.c:1227
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:SyS_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_brk
  - mm/mremap.c:SyS_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81207c10-ffffffff81207d4f: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81228990)
Location: mm/gup.c:1233
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81228990-ffffffff81228abf: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123c230)
Location: mm/gup.c:1258
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8123c230-ffffffff8123c35f: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124dd90)
Location: mm/gup.c:1241
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8124dd90-ffffffff8124ded7: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125c2c0)
Location: mm/gup.c:1244
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8125c2c0-ffffffff8125c407: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128b700)
Location: mm/gup.c:1463
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8128b700-ffffffff8128b847: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81295570)
Location: mm/gup.c:1414
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81295570-ffffffff812956e3: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129aed0)
Location: mm/gup.c:1499
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8129aed0-ffffffff8129b03c: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812db940)
Location: mm/gup.c:1587
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812db940-ffffffff812dbaa9: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133b710)
Location: mm/gup.c:1621
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8133b710-ffffffff8133b887: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b32d0)
Location: mm/gup.c:1602
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff813b32d0-ffffffff813b3458: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e80c0)
Location: mm/gup.c:1724
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff813e80c0-ffffffff813e824b: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81412d30)
Location: mm/gup.c:1750
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__do_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
  - mm/mremap.c:__do_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81412d30-ffffffff81412ebb: __mm_populate (STB_GLOBAL)
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f3760)
Location: mm/gup.c:1244
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__arm64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:__arm64_sys_brk
  - mm/mremap.c:__arm64_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffff8000102f3760-ffff8000102f38dc: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c05159d4)
Location: mm/gup.c:1244
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_brk
  - mm/mremap.c:__se_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c05159d4-c0515b54: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003ba300)
Location: mm/gup.c:1244
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_brk
  - mm/mremap.c:__se_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c0000000003ba300-c0000000003ba50c: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe000205888)
Location: mm/gup.c:1244
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__se_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_brk
  - mm/mremap.c:__se_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffe000205888-ffffffe00020598c: __mm_populate (STB_GLOBAL)
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
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81254910)
Location: mm/gup.c:1244
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81254910-ffffffff81254a57: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81247560)
Location: mm/gup.c:1244
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81247560-ffffffff812476a7: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812526b0)
Location: mm/gup.c:1244
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812526b0-ffffffff812527f7: __mm_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __mm_populate(long unsigned int start, long unsigned int len, int ignore_errors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81262080)
Location: mm/gup.c:1244
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
  - mm/mlock.c:do_mlock
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81262080-ffffffff812621c7: __mm_populate (STB_GLOBAL)
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
