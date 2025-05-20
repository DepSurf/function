# Function: <code>vm_munmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c68d0)
Location: mm/mmap.c:2617
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/mmap.c:SyS_munmap
  - fs/aio.c:kill_ioctx
  - fs/aio.c:SyS_io_setup
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff811c68d0-ffffffff811c6928: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e2360)
Location: mm/mmap.c:2514
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:kill_ioctx
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff811e2360-ffffffff811e23c2: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f2330)
Location: mm/mmap.c:2667
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff811f2330-ffffffff811f2392: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fd2f0)
Location: mm/mmap.c:2710
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/mmap.c:SyS_munmap
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff811fd2f0-ffffffff811fd39d: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81215850)
Location: mm/mmap.c:2736
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/mmap.c:SyS_munmap
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff81215850-ffffffff812158fd: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81236660)
Location: mm/mmap.c:2791
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - mm/mmap.c:__ia32_sys_munmap
  - mm/mmap.c:__x64_sys_munmap
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff81236660-ffffffff8123670d: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81249f80)
Location: mm/mmap.c:2863
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff81249f80-ffffffff81249f92: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125c280)
Location: mm/mmap.c:2869
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff8125c280-ffffffff8125c292: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126a9e0)
Location: mm/mmap.c:2874
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff8126a9e0-ffffffff8126a9f2: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129bc10)
Location: mm/mmap.c:2884
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff8129bc10-ffffffff8129bc22: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a6ec0)
Location: mm/mmap.c:2947
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff812a6ec0-ffffffff812a6ed2: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ab9d0)
Location: mm/mmap.c:2951
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff812ab9d0-ffffffff812ab9e2: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ed0c0)
Location: mm/mmap.c:2923
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff812ed0c0-ffffffff812ed0d2: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81350450)
Location: mm/mmap.c:2924
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff81350450-ffffffff8135046c: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813c9d00)
Location: mm/mmap.c:2795
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff813c9d00-ffffffff813c9d1c: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813fe190)
Location: mm/mmap.c:2909
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff813fe190-ffffffff813fe1ac: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142a570)
Location: mm/mmap.c:2998
Inline: False
Direct callers:
  - arch/x86/kernel/shstk.c:shstk_free
  - arch/x86/kernel/shstk.c:alloc_shstk
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_load
  - fs/compat_binfmt_elf.c:elf_load
```
**Symbols:**

```
ffffffff8142a570-ffffffff8142a58c: vm_munmap (STB_GLOBAL)
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
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff8000103020e0)
Location: mm/mmap.c:2874
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffff8000103020e0-ffff800010302118: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0520828)
Location: mm/mmap.c:2874
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:kill_ioctx
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_flat.c:load_flat_file
```
**Symbols:**

```
c0520828-c0520848: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003ce500)
Location: mm/mmap.c:2874
Inline: False
Direct callers:
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
c0000000003ce500-c0000000003ce518: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020f104)
Location: mm/mmap.c:2874
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:kill_ioctx
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_flat.c:load_flat_file
```
**Symbols:**

```
ffffffe00020f104-ffffffe00020f138: vm_munmap (STB_GLOBAL)
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
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81263030)
Location: mm/mmap.c:2874
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff81263030-ffffffff81263042: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81255450)
Location: mm/mmap.c:2874
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff81255450-ffffffff81255462: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81260dd0)
Location: mm/mmap.c:2874
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff81260dd0-ffffffff81260de2: vm_munmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vm_munmap(long unsigned int start, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812707a0)
Location: mm/mmap.c:2874
Inline: False
Direct callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
  - fs/aio.c:kill_ioctx
  - fs/aio.c:ioctx_alloc
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff812707a0-ffffffff812707b2: vm_munmap (STB_GLOBAL)
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
