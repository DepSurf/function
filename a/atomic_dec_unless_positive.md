# Function: <code>atomic_dec_unless_positive</code>

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
In kernel/events/core.c (ffffffff8117ed68)
Location: include/linux/atomic.h:524
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/shmem.c (ffffffff811a87b9)
Location: include/linux/atomic.h:524
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/mmap.c (ffffffff811c7403)
Location: include/linux/atomic.h:524
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/super.c (ffffffff8120fd16)
Location: include/linux/atomic.h:524
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff8121214f)
Location: include/linux/atomic.h:524
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
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
In kernel/events/core.c (ffffffff8119096d)
Location: include/linux/atomic.h:593
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/shmem.c (ffffffff811bf5c6)
Location: include/linux/atomic.h:593
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/mmap.c (ffffffff811e39b3)
Location: include/linux/atomic.h:593
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/super.c (ffffffff8123670d)
Location: include/linux/atomic.h:593
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff81238c21)
Location: include/linux/atomic.h:593
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
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
In kernel/events/core.c (ffffffff8119f83b)
Location: include/linux/atomic.h:593
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/shmem.c (ffffffff811cfbfc)
Location: include/linux/atomic.h:593
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/mmap.c (ffffffff811f3993)
Location: include/linux/atomic.h:593
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/super.c (ffffffff812493bd)
Location: include/linux/atomic.h:593
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff8124b8d1)
Location: include/linux/atomic.h:593
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
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
In kernel/events/core.c (ffffffff811a6348)
Location: include/linux/atomic.h:616
Inline: True
```
```
In mm/shmem.c (ffffffff811d933b)
Location: include/linux/atomic.h:616
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/mmap.c (ffffffff811fe9b4)
Location: include/linux/atomic.h:616
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/super.c (ffffffff81254ca5)
Location: include/linux/atomic.h:616
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff812579f9)
Location: include/linux/atomic.h:616
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
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
In kernel/events/core.c (ffffffff811b9f3e)
Location: include/linux/atomic.h:620
Inline: True
```
```
In mm/shmem.c (ffffffff811ee61b)
Location: include/linux/atomic.h:620
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
```
```
In mm/mmap.c (ffffffff81216f6a)
Location: include/linux/atomic.h:620
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/super.c (ffffffff81276e35)
Location: include/linux/atomic.h:620
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff81279cc9)
Location: include/linux/atomic.h:620
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
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
In kernel/events/core.c (0)
Location: include/linux/atomic.h:620
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81237eb1)
Location: include/linux/atomic.h:620
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff81294179)
Location: include/linux/atomic.h:620
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/super.c (ffffffff8129d723)
Location: include/linux/atomic.h:620
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (0)
Location: include/linux/atomic.h:620
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
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
In kernel/events/core.c (ffffffff811e94f3)
Location: include/linux/atomic.h:688
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8124b7da)
Location: include/linux/atomic.h:688
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff812a8e41)
Location: include/linux/atomic.h:688
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/super.c (ffffffff812b26b7)
Location: include/linux/atomic.h:688
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff812b64ca)
Location: include/linux/atomic.h:688
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8125dcc3)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff812c596e)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/super.c (ffffffff812cf118)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/super.c:mount_bdev
  - fs/super.c:mount_bdev
```
```
In fs/exec.c (ffffffff812d3249)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8126c493)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff812d737e)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff812e4dd9)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff8134fe76)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/events/core.c (0)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8129c221)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff8130c2ee)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff8131c663)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff813966e6)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/events/core.c (0)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff812a7544)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff81318232)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff813281b8)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff81365b62)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff813a8406)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/events/core.c (ffffffff81248c8d)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff812ad27b)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff8131e41f)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff8132e0dc)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff8136c5a2)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff813af45f)
Location: include/asm-generic/atomic-instrumented.h:816
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/fork.c (ffffffff810b330f)
Location: include/linux/atomic/atomic-instrumented.h:589
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/core.c (ffffffff81283a96)
Location: include/linux/atomic/atomic-instrumented.h:589
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memfd.c (ffffffff8136b7f5)
Location: include/linux/atomic/atomic-instrumented.h:589
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff8137b8cc)
Location: include/linux/atomic/atomic-instrumented.h:589
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff813bb272)
Location: include/linux/atomic/atomic-instrumented.h:589
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff813ff00f)
Location: include/linux/atomic/atomic-instrumented.h:589
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/fork.c (ffffffff810c952f)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/core.c (ffffffff812d6c7d)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memfd.c (ffffffff813e9970)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff813fc164)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff814411dd)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff81472baf)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/fork.c (ffffffff810e6a8b)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/core.c (ffffffff8133fa3b)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memfd.c (ffffffff81471990)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff81485bd4)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff814d011e)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff81504906)
Location: include/linux/atomic/atomic-instrumented.h:628
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/fork.c (ffffffff810f2445)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/core.c (ffffffff813709b0)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memfd.c (ffffffff814a62e2)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff814b98c8)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff815063c1)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff8153c008)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/fork.c (ffffffff810fc015)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/core.c (ffffffff81399cb0)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memfd.c (ffffffff814d7232)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff814ebdb8)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff8153b0e1)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff815712e8)
Location: include/linux/atomic/atomic-instrumented.h:1558
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffff8000103037dc)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffff80001037c570)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffff80001038c83c)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffff800010411a30)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/events/core.c (c04c7990)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (c0521e9c)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (c0566ea0)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (c05743f8)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (c05de104)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/events/core.c (c000000000347130)
Location: include/linux/atomic-fallback.h:1150
Inline: True
```
```
In mm/mmap.c (c0000000003d0368)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (c0000000004717c8)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (c00000000048478c)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (c00000000051f5e8)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/events/core.c (ffffffe0001ca3f2)
Location: include/linux/atomic-fallback.h:1150
Inline: True
```
```
In mm/mmap.c (ffffffe0002102c0)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffe000252912)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffe00025d0d2)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffe0002b9c26)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81264ae3)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff812cf95e)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff812dd3b9)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff81348456)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81256f03)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff812c05de)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff812ce039)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff81339136)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81262883)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff812cd76e)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff812db1c9)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff81345f26)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/events/core.c (0)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff81272243)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff812de57e)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff812ec149)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff81359206)
Location: include/linux/atomic-fallback.h:1150
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
</details>
</li>
</ul>

## Differences
