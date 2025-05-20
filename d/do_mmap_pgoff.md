# Function: <code>do_mmap_pgoff</code>

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
In mm/util.c (ffffffff811abfd9)
Location: include/linux/mm.h:1942
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff811c7b1d)
Location: include/linux/mm.h:1942
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
```
```
In fs/aio.c (ffffffff8125ce26)
Location: include/linux/mm.h:1942
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
```
```
In ipc/shm.c (ffffffff8132b750)
Location: include/linux/mm.h:1942
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
In mm/util.c (ffffffff811c4c44)
Location: include/linux/mm.h:2063
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff811e4182)
Location: include/linux/mm.h:2063
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
```
```
In fs/aio.c (ffffffff81284e1e)
Location: include/linux/mm.h:2063
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff813603a5)
Location: include/linux/mm.h:2063
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
In mm/util.c (ffffffff811d4d54)
Location: include/linux/mm.h:2049
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff811f4182)
Location: include/linux/mm.h:2049
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
```
```
In fs/aio.c (ffffffff8129902d)
Location: include/linux/mm.h:2049
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff81376bc3)
Location: include/linux/mm.h:2049
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
In mm/util.c (ffffffff811ddb89)
Location: include/linux/mm.h:2125
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff811ff0b9)
Location: include/linux/mm.h:2125
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
```
```
In fs/aio.c (ffffffff812a6718)
Location: include/linux/mm.h:2125
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff8138a793)
Location: include/linux/mm.h:2125
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
In mm/util.c (ffffffff811f3609)
Location: include/linux/mm.h:2234
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff812176b9)
Location: include/linux/mm.h:2234
Inline: True
Inline callers:
  - mm/mmap.c:SyS_remap_file_pages
```
```
In fs/aio.c (ffffffff812c9c4c)
Location: include/linux/mm.h:2234
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff813af909)
Location: include/linux/mm.h:2234
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
In mm/util.c (ffffffff812148c9)
Location: include/linux/mm.h:2323
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff81238798)
Location: include/linux/mm.h:2323
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
```
In fs/aio.c (ffffffff812f2f55)
Location: include/linux/mm.h:2323
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff813df742)
Location: include/linux/mm.h:2323
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
In mm/util.c (ffffffff812277a9)
Location: include/linux/mm.h:2396
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff8124c158)
Location: include/linux/mm.h:2396
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
```
In fs/aio.c (ffffffff81307c78)
Location: include/linux/mm.h:2396
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff813f9e8a)
Location: include/linux/mm.h:2396
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
In mm/util.c (ffffffff81237549)
Location: include/linux/mm.h:2391
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff8125e5c4)
Location: include/linux/mm.h:2391
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
```
In fs/aio.c (ffffffff8132c44b)
Location: include/linux/mm.h:2391
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff81426467)
Location: include/linux/mm.h:2391
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
In mm/util.c (ffffffff81245799)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff8126cdd4)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
```
In fs/aio.c (ffffffff8133f29b)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff814401b7)
Location: include/linux/mm.h:2365
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
In mm/util.c (ffffffff812734c9)
Location: include/linux/mm.h:2613
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff8129cb7e)
Location: include/linux/mm.h:2613
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
```
```
In fs/aio.c (ffffffff813778ab)
Location: include/linux/mm.h:2613
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff81490f60)
Location: include/linux/mm.h:2613
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
</details>
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
In mm/util.c (ffff8000102d8cf0)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffff800010303fb0)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/mmap.c:__arm64_sys_remap_file_pages
```
```
In fs/aio.c (ffff8000103fb260)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffff8000105288dc)
Location: include/linux/mm.h:2365
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
In mm/util.c (c04fff2c)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (c05227c8)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
```
```
In fs/aio.c (c05d05f0)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (c06e1e44)
Location: include/linux/mm.h:2365
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
In mm/util.c (c000000000398830)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (c0000000003d0da4)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
```
```
In fs/aio.c (c000000000508198)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (c0000000006734d0)
Location: include/linux/mm.h:2365
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
In mm/util.c (ffffffe0001f31ba)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffe000210908)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/mmap.c:__se_sys_remap_file_pages
```
```
In fs/aio.c (ffffffe0002aab6e)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffe00038bfe4)
Location: include/linux/mm.h:2365
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
In mm/util.c (ffffffff8123dde9)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff81265424)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
```
In fs/aio.c (ffffffff8133787b)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff81438797)
Location: include/linux/mm.h:2365
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
In mm/util.c (ffffffff81230de9)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff81257844)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
```
In fs/aio.c (ffffffff813285ab)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff81429207)
Location: include/linux/mm.h:2365
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
In mm/util.c (ffffffff8123bb89)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff812631c4)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
```
In fs/aio.c (ffffffff8133534b)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff81434937)
Location: include/linux/mm.h:2365
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
In mm/util.c (ffffffff8124b299)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/util.c:vm_mmap_pgoff
```
```
In mm/mmap.c (ffffffff81272b84)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/mmap.c:__ia32_sys_remap_file_pages
  - mm/mmap.c:__x64_sys_remap_file_pages
```
```
In fs/aio.c (ffffffff8134833b)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - fs/aio.c:aio_setup_ring
```
```
In ipc/shm.c (ffffffff8144ba80)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
</details>
</li>
</ul>

## Differences
