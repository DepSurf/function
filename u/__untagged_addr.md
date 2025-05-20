# Function: <code>__untagged_addr</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff811d96db)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:task_set_syscall_user_dispatch
```
```
In mm/gup.c (ffffffff813e7a90)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
```
```
In mm/mincore.c (ffffffff813f60f2)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mlock.c (ffffffff813f7845)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff813fe1c5)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_munmap
  - mm/mmap.c:__x64_sys_munmap
```
```
In mm/mprotect.c (ffffffff814040ec)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff8140651d)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff81406d14)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/mempolicy.c (ffffffff8144a014)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:kernel_mbind
```
```
In lib/strncpy_from_user.c (ffffffff818e0861)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff818e09d3)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff811ef38b)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:task_set_syscall_user_dispatch
```
```
In mm/gup.c (ffffffff81412700)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
```
```
In mm/mincore.c (ffffffff81421da2)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mincore.c:__ia32_sys_mincore
  - mm/mincore.c:__x64_sys_mincore
```
```
In mm/mlock.c (ffffffff81423425)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_munlock
  - mm/mlock.c:__x64_sys_munlock
  - mm/mlock.c:do_mlock
```
```
In mm/mmap.c (ffffffff8142a5a5)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_munmap
  - mm/mmap.c:__x64_sys_munmap
```
```
In mm/mprotect.c (ffffffff814306bc)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mprotect.c:do_mprotect_pkey
```
```
In mm/mremap.c (ffffffff81432c2d)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/msync.c (ffffffff814333c4)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/msync.c:__do_sys_msync
```
```
In mm/mempolicy.c (ffffffff81483aa4)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
  - mm/mempolicy.c:kernel_mbind
```
```
In fs/proc/task_mmu.c (ffffffff8159bafb)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:do_pagemap_scan
```
```
In lib/strncpy_from_user.c (ffffffff819273a1)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81927516)
Location: arch/x86/include/asm/uaccess_64.h:19
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
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
