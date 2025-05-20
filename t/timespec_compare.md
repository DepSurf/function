# Function: <code>timespec_compare</code>

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
In arch/x86/xen/time.c (ffffffff81023568)
Location: include/linux/time.h:24
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff810f502e)
Location: include/linux/time.h:24
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:timekeeping_resume
```
```
In fs/inode.c (ffffffff812290bd)
Location: include/linux/time.h:24
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff81022935)
Location: include/linux/time.h:24
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff810fcf71)
Location: include/linux/time.h:24
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/inode.c (ffffffff812517e2)
Location: include/linux/time.h:24
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff81023085)
Location: include/linux/time.h:24
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff810ffd76)
Location: include/linux/time.h:24
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/inode.c (ffffffff8126493f)
Location: include/linux/time.h:24
Inline: True
Inline callers:
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
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
In arch/x86/xen/time.c (ffffffff8101ae10)
Location: include/linux/time.h:33
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff81101f65)
Location: include/linux/time.h:33
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/inode.c (ffffffff81272168)
Location: include/linux/time.h:33
Inline: True
Inline callers:
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
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
