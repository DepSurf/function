# Function: <code>arch_atomic_dec_unless_positive</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: include/linux/atomic-arch-fallback.h:1152
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff8129c221)
Location: include/linux/atomic-arch-fallback.h:1152
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff8130c2ee)
Location: include/linux/atomic-arch-fallback.h:1152
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff8131c663)
Location: include/linux/atomic-arch-fallback.h:1152
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff813966e6)
Location: include/linux/atomic-arch-fallback.h:1152
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
Location: include/linux/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff812a7544)
Location: include/linux/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff81318232)
Location: include/linux/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff813281b8)
Location: include/linux/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff81365b62)
Location: include/linux/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff813a8406)
Location: include/linux/atomic-arch-fallback.h:1222
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
Location: include/linux/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/mmap.c (ffffffff812ad27b)
Location: include/linux/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In mm/memfd.c (ffffffff8131e41f)
Location: include/linux/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff8132e0dc)
Location: include/linux/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff8136c5a2)
Location: include/linux/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff813af45f)
Location: include/linux/atomic-arch-fallback.h:1222
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
Location: include/linux/atomic/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/core.c (ffffffff81283a96)
Location: include/linux/atomic/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memfd.c (ffffffff8136b7f5)
Location: include/linux/atomic/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff8137b8cc)
Location: include/linux/atomic/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff813bb272)
Location: include/linux/atomic/atomic-arch-fallback.h:1222
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff813ff00f)
Location: include/linux/atomic/atomic-arch-fallback.h:1222
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
Location: include/linux/atomic/atomic-arch-fallback.h:1306
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/core.c (ffffffff812d6c7d)
Location: include/linux/atomic/atomic-arch-fallback.h:1306
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memfd.c (ffffffff813e9970)
Location: include/linux/atomic/atomic-arch-fallback.h:1306
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff813fc164)
Location: include/linux/atomic/atomic-arch-fallback.h:1306
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff814411dd)
Location: include/linux/atomic/atomic-arch-fallback.h:1306
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff81472baf)
Location: include/linux/atomic/atomic-arch-fallback.h:1306
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
Location: include/linux/atomic/atomic-arch-fallback.h:1306
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/core.c (ffffffff8133fa3b)
Location: include/linux/atomic/atomic-arch-fallback.h:1306
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memfd.c (ffffffff81471990)
Location: include/linux/atomic/atomic-arch-fallback.h:1306
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff81485bd4)
Location: include/linux/atomic/atomic-arch-fallback.h:1306
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff814d011e)
Location: include/linux/atomic/atomic-arch-fallback.h:1306
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff81504906)
Location: include/linux/atomic/atomic-arch-fallback.h:1306
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
</details>
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
