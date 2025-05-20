# Function: <code>is_file_hugepages</code>

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
In mm/mmap.c (ffffffff811c5b4d)
Location: include/linux/hugetlb.h:268
Inline: True
Inline callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
```
```
In ipc/shm.c (ffffffff81329fb2)
Location: include/linux/hugetlb.h:268
Inline: True
Inline callers:
  - ipc/shm.c:shm_destroy
  - ipc/shm.c:newseg
  - ipc/shm.c:SyS_shmctl
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
In mm/mmap.c (ffffffff811e34d2)
Location: include/linux/hugetlb.h:267
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In ipc/shm.c (ffffffff813601bb)
Location: include/linux/hugetlb.h:267
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff811f34b2)
Location: include/linux/hugetlb.h:267
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In ipc/shm.c (ffffffff813769d4)
Location: include/linux/hugetlb.h:267
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:SyS_shmctl
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff811fe52a)
Location: include/linux/hugetlb.h:287
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In ipc/shm.c (0)
Location: include/linux/hugetlb.h:287
Inline: True
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
In mm/mmap.c (ffffffff81216ada)
Location: include/linux/hugetlb.h:280
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In ipc/shm.c (0)
Location: include/linux/hugetlb.h:280
Inline: True
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
In mm/mmap.c (ffffffff81237ab1)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff81293c77)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffffffff813df4df)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff8124b447)
Location: include/linux/hugetlb.h:307
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff812a8937)
Location: include/linux/hugetlb.h:307
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In ipc/shm.c (ffffffff813f9c3b)
Location: include/linux/hugetlb.h:307
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff8125d891)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff812c5097)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/io_uring.c (ffffffff81331a89)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffffffff81426240)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff8126c061)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff812d6a27)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/io_uring.c (ffffffff8134568e)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffffffff8143ff90)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff8129bda0)
Location: include/linux/hugetlb.h:439
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff8130bac5)
Location: include/linux/hugetlb.h:439
Inline: True
```
```
In fs/io_uring.c (ffffffff8137f6c4)
Location: include/linux/hugetlb.h:439
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffffffff81490d0c)
Location: include/linux/hugetlb.h:439
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff812a703d)
Location: include/linux/hugetlb.h:440
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff81317b8b)
Location: include/linux/hugetlb.h:440
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/io_uring.c (ffffffff8138dc43)
Location: include/linux/hugetlb.h:440
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffffffff814ae45e)
Location: include/linux/hugetlb.h:440
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff812ace7c)
Location: include/linux/hugetlb.h:457
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff8131dd7b)
Location: include/linux/hugetlb.h:457
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/io_uring.c (ffffffff81391baa)
Location: include/linux/hugetlb.h:457
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffffffff814b428b)
Location: include/linux/hugetlb.h:457
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff812ee5cc)
Location: include/linux/hugetlb.h:474
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff8136b11e)
Location: include/linux/hugetlb.h:474
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/io_uring.c (ffffffff813dfaca)
Location: include/linux/hugetlb.h:474
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffffffff8150c925)
Location: include/linux/hugetlb.h:474
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab4f6)
Location: include/linux/hugetlb.h:474
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In mm/mmap.c (ffffffff813519c8)
Location: include/linux/hugetlb.h:497
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff813e90c9)
Location: include/linux/hugetlb.h:497
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In ipc/shm.c (ffffffff8159e8ca)
Location: include/linux/hugetlb.h:497
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
```
In io_uring/io_uring.c (ffffffff816ca1e3)
Location: include/linux/hugetlb.h:497
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_pin_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5c8e)
Location: include/linux/hugetlb.h:497
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In mm/mmap.c (ffffffff813cb652)
Location: include/linux/hugetlb.h:497
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff81471034)
Location: include/linux/hugetlb.h:497
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In ipc/shm.c (ffffffff81647f8a)
Location: include/linux/hugetlb.h:497
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
```
```
In io_uring/rsrc.c (ffffffff817a2332)
Location: include/linux/hugetlb.h:497
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_pin_pages
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b73250)
Location: include/linux/hugetlb.h:497
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
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
In mm/filemap.c (ffffffff8138cdc2)
Location: include/linux/hugetlb.h:539
Inline: True
Inline callers:
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
```
```
In mm/mmap.c (ffffffff813ffeec)
Location: include/linux/hugetlb.h:539
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff814a6011)
Location: include/linux/hugetlb.h:539
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In ipc/shm.c (ffffffff816804a3)
Location: include/linux/hugetlb.h:539
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
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
In mm/filemap.c (ffffffff813b68d2)
Location: include/linux/hugetlb.h:562
Inline: True
Inline callers:
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
```
```
In mm/mmap.c (ffffffff8142c441)
Location: include/linux/hugetlb.h:562
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff814d6f36)
Location: include/linux/hugetlb.h:562
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In ipc/shm.c (ffffffff816bc8c2)
Location: include/linux/hugetlb.h:562
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffff800010303430)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffff80001037bb88)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/io_uring.c (ffff8000104037bc)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffff800010528764)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cfec4)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (c000000000470ca4)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/io_uring.c (c0000000005104b0)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (c000000000673234)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_add_rss_swap
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffe00020ffec)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffe00025234c)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/io_uring.c (ffffffe0002ae0ac)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffffffe00038bdea)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_add_rss_swap
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff812646b1)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff812cf007)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/io_uring.c (ffffffff8133dc6e)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffffffff81438570)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff81256ad1)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff812bfc97)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/io_uring.c (ffffffff8132e92e)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffffffff81428fe0)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff81262451)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff812cce17)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/io_uring.c (ffffffff8133b73e)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffffffff81434710)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
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
In mm/mmap.c (ffffffff81271e11)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
```
```
In mm/memfd.c (ffffffff812ddbb7)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/io_uring.c (ffffffff8134e8ee)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
```
In ipc/shm.c (ffffffff8144b835)
Location: include/linux/hugetlb.h:293
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
```
</details>
</li>
</ul>

## Differences
