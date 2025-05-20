# Function: <code>timespec_to_jiffies</code>

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
In kernel/signal.c (ffffffff8109127c)
Location: include/linux/jiffies.h:415
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f3166)
Location: include/linux/jiffies.h:415
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In fs/fuse/dir.c (ffffffff81311b5e)
Location: include/linux/jiffies.h:415
Inline: True
```
```
In ipc/sem.c (ffffffff813282d6)
Location: include/linux/jiffies.h:415
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
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
In kernel/time/posix-cpu-timers.c (ffffffff810fa276)
Location: include/linux/jiffies.h:415
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In fs/fuse/dir.c (ffffffff8134604e)
Location: include/linux/jiffies.h:415
Inline: True
```
```
In ipc/sem.c (ffffffff8135cf7f)
Location: include/linux/jiffies.h:415
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
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
In kernel/time/posix-cpu-timers.c (ffffffff81107bf6)
Location: include/linux/jiffies.h:419
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_set
```
```
In ipc/sem.c (ffffffff8137365e)
Location: include/linux/jiffies.h:419
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813872f5)
Location: include/linux/jiffies.h:420
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
</details>
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
