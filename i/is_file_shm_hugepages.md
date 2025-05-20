# Function: <code>is_file_shm_hugepages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8132afe0)
Location: ipc/shm.c:495
Inline: True
Direct callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:mmap_region
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8132afe0-ffffffff8132aff8: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8135fc80)
Location: ipc/shm.c:497
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8135fc80-ffffffff8135fc96: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81376480)
Location: ipc/shm.c:500
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff81376480-ffffffff81376496: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8138a000)
Location: ipc/shm.c:501
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff8138a000-ffffffff8138a016: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813af410)
Location: ipc/shm.c:515
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:do_mmap
```
**Symbols:**

```
ffffffff813af410-ffffffff813af426: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813df4df)
Location: ipc/shm.c:558
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:memfd_file_seals_ptr
```
**Symbols:**

```
ffffffff813ded60-ffffffff813ded76: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f9c3b)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:memfd_file_seals_ptr
```
**Symbols:**

```
ffffffff813f9460-ffffffff813f9476: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81426240)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:memfd_file_seals_ptr
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff81425bd0-ffffffff81425be6: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143ff90)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:memfd_file_seals_ptr
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff8143f920-ffffffff8143f936: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81490d10)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff81490a60-ffffffff81490a76: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814ae462)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff814ae1a0-ffffffff814ae1b6: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b428f)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff814b3fd0-ffffffff814b3fe6: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8150c929)
Location: ipc/shm.c:668
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - fs/io_uring.c:io_sqe_buffer_register
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff8150c660-ffffffff8150c676: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8159e8ce)
Location: ipc/shm.c:665
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - io_uring/io_uring.c:io_pin_pages
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff8159e5d0-ffffffff8159e5ec: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81647f8e)
Location: ipc/shm.c:681
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - io_uring/rsrc.c:io_pin_pages
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81647c60-ffffffff81647c7c: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816804aa)
Location: ipc/shm.c:681
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff81680170-ffffffff8168018f: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816bc8c9)
Location: ipc/shm.c:677
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/filemap.c:__ia32_sys_cachestat
  - mm/filemap.c:__x64_sys_cachestat
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff816bc560-ffffffff816bc57f: is_file_shm_hugepages (STB_GLOBAL)
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
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff800010528764)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:memfd_file_seals_ptr
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffff800010528068-ffff8000105280a0: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c06e18d0)
Location: ipc/shm.c:576
Inline: False
```
**Symbols:**

```
c06e18d0-c06e1900: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000673248)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shm_add_rss_swap
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:memfd_file_seals_ptr
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
c000000000672a50-c000000000672a7c: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffe00038bb22)
Location: ipc/shm.c:576
Inline: True
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:memfd_file_seals_ptr
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffe00038bb22-ffffffe00038bb52: is_file_shm_hugepages (STB_GLOBAL)
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
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81438570)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:memfd_file_seals_ptr
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff81437f00-ffffffff81437f16: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81428fe0)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:memfd_file_seals_ptr
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff81428970-ffffffff81428986: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81434710)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:memfd_file_seals_ptr
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff814340a0-ffffffff814340b6: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_file_shm_hugepages(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8144b835)
Location: ipc/shm.c:576
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:newseg
  - ipc/shm.c:shm_destroy
Direct callers:
  - mm/mmap.c:mmap_region
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:do_mmap
  - mm/memfd.c:memfd_file_seals_ptr
  - fs/io_uring.c:io_sqe_buffer_register
```
**Symbols:**

```
ffffffff8144b1b0-ffffffff8144b1c6: is_file_shm_hugepages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
