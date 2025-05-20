# Function: <code>do_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c7480)
Location: mm/mmap.c:1267
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:SyS_remap_file_pages
  - fs/aio.c:SyS_io_setup
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff811c7480-ffffffff811c7891: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e3a30)
Location: mm/mmap.c:1151
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:SyS_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff811e3a30-ffffffff811e3f3a: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f3a10)
Location: mm/mmap.c:1304
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:SyS_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff811f3a10-ffffffff811f3f32: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fea10)
Location: mm/mmap.c:1320
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:SyS_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff811fea10-ffffffff811fee8e: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81216fd0)
Location: mm/mmap.c:1321
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:SyS_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81216fd0-ffffffff81217481: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81237fd0)
Location: mm/mmap.c:1359
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81237fd0-ffffffff8123856a: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124b9b0)
Location: mm/mmap.c:1383
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8124b9b0-ffffffff8124bf25: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125de30)
Location: mm/mmap.c:1385
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8125de30-ffffffff8125e3af: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126c600)
Location: mm/mmap.c:1389
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8126c600-ffffffff8126cbb3: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129c3b0)
Location: mm/mmap.c:1366
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__do_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8129c3b0-ffffffff8129c968: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a76e0)
Location: mm/mmap.c:1404
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__do_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812a76e0-ffffffff812a7cb1: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ad3e0)
Location: mm/mmap.c:1408
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__do_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812ad3e0-ffffffff812ad974: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812eeae0)
Location: mm/mmap.c:1404
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__do_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812eeae0-ffffffff812ef05f: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81351ec0)
Location: mm/mmap.c:1416
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__do_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81351ec0-ffffffff8135243e: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813cbe70)
Location: mm/mmap.c:1239
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__do_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff813cbe70-ffffffff813cc411: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81400790)
Location: mm/mmap.c:1188
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__do_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81400790-ffffffff81400d67: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142cdd0)
Location: mm/mmap.c:1216
Inline: False
Direct callers:
  - arch/x86/kernel/shstk.c:alloc_shstk
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__do_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8142cdd0-ffffffff8142d3a6: do_mmap (STB_GLOBAL)
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
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010303998)
Location: mm/mmap.c:1389
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffff800010303998-ffff800010303e04: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c05220cc)
Location: mm/mmap.c:1389
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__se_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c05220cc-c05225f0: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003d0530)
Location: mm/mmap.c:1389
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__se_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c0000000003d0530-c0000000003d0b20: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe0002103bc)
Location: mm/mmap.c:1389
Inline: False
Direct callers:
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__se_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffe0002103bc-ffffffe00021078e: do_mmap (STB_GLOBAL)
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
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81264c50)
Location: mm/mmap.c:1389
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81264c50-ffffffff81265203: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81257070)
Location: mm/mmap.c:1389
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81257070-ffffffff81257623: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812629f0)
Location: mm/mmap.c:1389
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812629f0-ffffffff81262fa3: do_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int do_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flags, vm_flags_t vm_flags, long unsigned int pgoff, long unsigned int *populate, struct list_head *uf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812723b0)
Location: mm/mmap.c:1389
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/util.c:vm_mmap_pgoff
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - fs/aio.c:aio_setup_ring
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff812723b0-ffffffff81272963: do_mmap (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct list_head *uf</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>vm_flags_t vm_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, addr, len, prot, flags, vm_flags, pgoff, populate, uf</code> ➡️ <code>file, addr, len, prot, flags, pgoff, populate, uf</code>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>vm_flags_t vm_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, addr, len, prot, flags, pgoff, populate, uf</code> ➡️ <code>file, addr, len, prot, flags, vm_flags, pgoff, populate, uf</code>
</li>
</ul>
</details>
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
