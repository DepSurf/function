# Function: <code>mm_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81075e4c)
Location: include/linux/mm.h:1952
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff811ac018)
Location: include/linux/mm.h:1952
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff811c3cdd)
Location: include/linux/mm.h:1952
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
```
```
In mm/mmap.c (ffffffff811c6c7c)
Location: include/linux/mm.h:1952
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk
  - mm/mmap.c:SyS_brk
  - mm/mmap.c:SyS_remap_file_pages
```
```
In mm/mremap.c (ffffffff811c9e57)
Location: include/linux/mm.h:1952
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
```
In ipc/shm.c (ffffffff8132b712)
Location: include/linux/mm.h:1952
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107738c)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff811c4c83)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff811dfb0b)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
```
```
In mm/mmap.c (ffffffff811e33d0)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_brk
```
```
In mm/mremap.c (ffffffff811e650f)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
```
In ipc/shm.c (ffffffff81360428)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In arch/x86/mm/mpx.c (ffffffff8107af3c)
Location: include/linux/mm.h:2059
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff811d4d93)
Location: include/linux/mm.h:2059
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff811efa5f)
Location: include/linux/mm.h:2059
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
```
```
In mm/mmap.c (ffffffff811f33b0)
Location: include/linux/mm.h:2059
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_brk
```
```
In mm/mremap.c (ffffffff811f67d5)
Location: include/linux/mm.h:2059
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
```
In ipc/shm.c (ffffffff81376c46)
Location: include/linux/mm.h:2059
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In arch/x86/mm/mpx.c (ffffffff8107974d)
Location: include/linux/mm.h:2136
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff811ddbd9)
Location: include/linux/mm.h:2136
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff811fa98a)
Location: include/linux/mm.h:2136
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
```
```
In mm/mmap.c (ffffffff811fe1d0)
Location: include/linux/mm.h:2136
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_brk
```
```
In mm/mremap.c (ffffffff812016e3)
Location: include/linux/mm.h:2136
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
```
In ipc/shm.c (ffffffff8138a767)
Location: include/linux/mm.h:2136
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In arch/x86/mm/mpx.c (ffffffff8107f961)
Location: include/linux/mm.h:2245
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff811f3659)
Location: include/linux/mm.h:2245
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81212e5b)
Location: include/linux/mm.h:2245
Inline: True
Inline callers:
  - mm/mlock.c:SyS_mlockall
```
```
In mm/mmap.c (ffffffff81216780)
Location: include/linux/mm.h:2245
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:SyS_remap_file_pages
  - mm/mmap.c:SyS_brk
```
```
In mm/mremap.c (ffffffff8121a0a3)
Location: include/linux/mm.h:2245
Inline: True
Inline callers:
  - mm/mremap.c:SyS_mremap
```
```
In ipc/shm.c (ffffffff813af8dd)
Location: include/linux/mm.h:2245
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In arch/x86/mm/mpx.c (ffffffff81082a71)
Location: include/linux/mm.h:2334
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff81214919)
Location: include/linux/mm.h:2334
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81233e32)
Location: include/linux/mm.h:2334
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
```
In mm/mmap.c (ffffffff81237562)
Location: include/linux/mm.h:2334
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff8123ba63)
Location: include/linux/mm.h:2334
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In ipc/shm.c (ffffffff813df7a8)
Location: include/linux/mm.h:2334
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In arch/x86/mm/mpx.c (ffffffff81089621)
Location: include/linux/mm.h:2407
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff812277f9)
Location: include/linux/mm.h:2407
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81247402)
Location: include/linux/mm.h:2407
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
```
In mm/mmap.c (ffffffff8124ae32)
Location: include/linux/mm.h:2407
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff8124fe60)
Location: include/linux/mm.h:2407
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In ipc/shm.c (ffffffff813f9ee4)
Location: include/linux/mm.h:2407
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In arch/x86/mm/mpx.c (ffffffff8108d763)
Location: include/linux/mm.h:2402
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff8123759b)
Location: include/linux/mm.h:2402
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81259630)
Location: include/linux/mm.h:2402
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
```
In mm/mmap.c (ffffffff8125d1f3)
Location: include/linux/mm.h:2402
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff81261f8f)
Location: include/linux/mm.h:2402
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In ipc/shm.c (ffffffff8142642e)
Location: include/linux/mm.h:2402
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In arch/x86/mm/mpx.c (ffffffff8108e3c3)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff812457eb)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81267b00)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
```
In mm/mmap.c (ffffffff8126b9c3)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff8127075f)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In ipc/shm.c (ffffffff8144017e)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/util.c (ffffffff8127351b)
Location: include/linux/mm.h:2624
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81297c77)
Location: include/linux/mm.h:2624
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff8129b803)
Location: include/linux/mm.h:2624
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff812a11d1)
Location: include/linux/mm.h:2624
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In ipc/shm.c (ffffffff81490f27)
Location: include/linux/mm.h:2624
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/util.c (ffffffff8127dc8f)
Location: include/linux/mm.h:2624
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff812a2d61)
Location: include/linux/mm.h:2624
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff812a69f4)
Location: include/linux/mm.h:2624
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff812ac8ef)
Location: include/linux/mm.h:2624
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In ipc/shm.c (ffffffff814ae6d2)
Location: include/linux/mm.h:2624
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/util.c (ffffffff81282e5c)
Location: include/linux/mm.h:2620
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff812a85db)
Location: include/linux/mm.h:2620
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff812ac9a1)
Location: include/linux/mm.h:2620
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff812b1bee)
Location: include/linux/mm.h:2620
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In ipc/shm.c (ffffffff814b44f9)
Location: include/linux/mm.h:2620
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/util.c (ffffffff812c0f44)
Location: include/linux/mm.h:2650
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff812e9c22)
Location: include/linux/mm.h:2650
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff812ee0ed)
Location: include/linux/mm.h:2650
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff812f37ba)
Location: include/linux/mm.h:2650
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In ipc/shm.c (ffffffff8150cb9c)
Location: include/linux/mm.h:2650
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/util.c (ffffffff8131dd9e)
Location: include/linux/mm.h:2729
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff8134a023)
Location: include/linux/mm.h:2729
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff813514e3)
Location: include/linux/mm.h:2729
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff81357781)
Location: include/linux/mm.h:2729
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In ipc/shm.c (ffffffff8159eb02)
Location: include/linux/mm.h:2729
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/util.c (ffffffff8139189b)
Location: include/linux/mm.h:2899
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff813c2b15)
Location: include/linux/mm.h:2899
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff813cb061)
Location: include/linux/mm.h:2899
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff813d1ca9)
Location: include/linux/mm.h:2899
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In ipc/shm.c (ffffffff816481b9)
Location: include/linux/mm.h:2899
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c4285)
Location: include/linux/mm.h:3210
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff813f7db1)
Location: include/linux/mm.h:3210
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff813ff2b7)
Location: include/linux/mm.h:3210
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff81406978)
Location: include/linux/mm.h:3210
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In ipc/shm.c (ffffffff816806fa)
Location: include/linux/mm.h:3210
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/util.c (ffffffff813eee39)
Location: include/linux/mm.h:3388
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81423981)
Location: include/linux/mm.h:3388
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff8142b7f9)
Location: include/linux/mm.h:3388
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:__do_sys_brk
```
```
In mm/mremap.c (ffffffff81433087)
Location: include/linux/mm.h:3388
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
```
```
In ipc/shm.c (ffffffff816bcb19)
Location: include/linux/mm.h:3388
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
</details>
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
In mm/util.c (ffff8000102d8d3c)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffff8000102fec28)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mlock.c:__arm64_sys_mlockall
```
```
In mm/mmap.c (ffff80001030310c)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__arm64_sys_remap_file_pages
  - mm/mmap.c:__arm64_sys_brk
```
```
In mm/mremap.c (ffff800010306a88)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mremap.c:__arm64_sys_mremap
```
```
In ipc/shm.c (ffff80001052895c)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/util.c (c04fff84)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (c051dcac)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mlock.c:__se_sys_mlockall
```
```
In mm/mmap.c (c05217ac)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_brk
```
```
In mm/mremap.c (c0524954)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
```
In ipc/shm.c (c06e1e34)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/util.c (c000000000398890)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (c0000000003ca844)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mlock.c:__se_sys_mlockall
```
```
In mm/mmap.c (c0000000003cfa30)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_brk
```
```
In mm/mremap.c (c0000000003d496c)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
```
In ipc/shm.c (c000000000673470)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In mm/util.c (ffffffe0001f31fa)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffe00020cf04)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mlock.c:__se_sys_mlockall
```
```
In mm/mmap.c (ffffffe00020fd52)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__se_sys_remap_file_pages
  - mm/mmap.c:__se_sys_brk
```
```
In mm/mremap.c (ffffffe00021213e)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mremap.c:__se_sys_mremap
```
```
In ipc/shm.c (ffffffe00038bf90)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In arch/x86/mm/mpx.c (ffffffff8108d383)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff8123de3b)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81260150)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
```
In mm/mmap.c (ffffffff81264013)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff81268daf)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In ipc/shm.c (ffffffff8143875e)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In arch/x86/mm/mpx.c (ffffffff8107beb3)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff81230e3b)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff81252570)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
```
In mm/mmap.c (ffffffff81256433)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff8125b09f)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In ipc/shm.c (ffffffff814291ce)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In arch/x86/mm/mpx.c (ffffffff8108d333)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff8123bbdb)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff8125def0)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
```
In mm/mmap.c (ffffffff81261db3)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff81266b4f)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In ipc/shm.c (ffffffff814348fe)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
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
In arch/x86/mm/mpx.c (ffffffff8108f6d7)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_handle_bd_fault
```
```
In mm/util.c (ffffffff8124b2eb)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mlock.c (ffffffff8126d8d0)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
```
In mm/mmap.c (ffffffff81271773)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mmap.c:vm_brk_flags
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
  - mm/mmap.c:__ia32_sys_brk
  - mm/mmap.c:__x64_sys_brk
```
```
In mm/mremap.c (ffffffff812764ef)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - mm/mremap.c:__ia32_sys_mremap
  - mm/mremap.c:__x64_sys_mremap
```
```
In ipc/shm.c (ffffffff8144ba49)
Location: include/linux/mm.h:2376
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
</details>
</li>
</ul>

## Differences
