# Function: <code>raw_atomic_dec_unless_positive</code>

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
In kernel/fork.c (ffffffff810f2445)
Location: include/linux/atomic/atomic-arch-fallback.h:2499
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/core.c (ffffffff813709b0)
Location: include/linux/atomic/atomic-arch-fallback.h:2499
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memfd.c (ffffffff814a62e2)
Location: include/linux/atomic/atomic-arch-fallback.h:2499
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff814b98c8)
Location: include/linux/atomic/atomic-arch-fallback.h:2499
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff815063c1)
Location: include/linux/atomic/atomic-arch-fallback.h:2499
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff8153c008)
Location: include/linux/atomic/atomic-arch-fallback.h:2499
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
Location: include/linux/atomic/atomic-arch-fallback.h:2508
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In kernel/events/core.c (ffffffff81399cb0)
Location: include/linux/atomic/atomic-arch-fallback.h:2508
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In mm/memfd.c (ffffffff814d7232)
Location: include/linux/atomic/atomic-arch-fallback.h:2508
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
```
In fs/exec.c (ffffffff814ebdb8)
Location: include/linux/atomic/atomic-arch-fallback.h:2508
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff8153b0e1)
Location: include/linux/atomic/atomic-arch-fallback.h:2508
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff815712e8)
Location: include/linux/atomic/atomic-arch-fallback.h:2508
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
