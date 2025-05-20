# Function: <code>timespec64_compare</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101b710)
Location: include/linux/time64.h:53
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff8110cec8)
Location: include/linux/time64.h:53
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/inode.c (ffffffff81294a73)
Location: include/linux/time64.h:53
Inline: True
Inline callers:
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
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
In arch/x86/xen/time.c (ffffffff8101c050)
Location: include/linux/time64.h:54
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff811189f3)
Location: include/linux/time64.h:54
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff812bac58)
Location: include/linux/time64.h:54
Inline: True
Inline callers:
  - fs/inode.c:__atime_needs_update
  - fs/inode.c:__atime_needs_update
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
In arch/x86/xen/time.c (ffffffff8101bb90)
Location: include/linux/time64.h:55
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff811244d2)
Location: include/linux/time64.h:55
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff812cfe76)
Location: include/linux/time64.h:55
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff8101d6d0)
Location: include/linux/time64.h:58
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff8112ee12)
Location: include/linux/time64.h:58
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff812ecdc2)
Location: include/linux/time64.h:58
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff8101dfd0)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff8113add2)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff812fe952)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff810205b0)
Location: include/linux/time64.h:52
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff81149f27)
Location: include/linux/time64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff813379f2)
Location: include/linux/time64.h:52
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff81020ff0)
Location: include/linux/time64.h:52
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff81146477)
Location: include/linux/time64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff81343332)
Location: include/linux/time64.h:52
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff81023390)
Location: include/linux/time64.h:52
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff811474d7)
Location: include/linux/time64.h:52
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff81349601)
Location: include/linux/time64.h:52
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff8102756e)
Location: include/linux/time64.h:54
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff8116afd7)
Location: include/linux/time64.h:54
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff81397351)
Location: include/linux/time64.h:54
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff8102b862)
Location: include/linux/time64.h:54
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff8119ee4a)
Location: include/linux/time64.h:54
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/inode.c (ffffffff814194fb)
Location: include/linux/time64.h:54
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff810325b2)
Location: include/linux/time64.h:57
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff811ddaca)
Location: include/linux/time64.h:57
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/inode.c (ffffffff814a4f2f)
Location: include/linux/time64.h:57
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff81032552)
Location: include/linux/time64.h:57
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff811f1f9a)
Location: include/linux/time64.h:57
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/inode.c (ffffffff814da1a7)
Location: include/linux/time64.h:57
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff81038842)
Location: include/linux/time64.h:57
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff812080da)
Location: include/linux/time64.h:57
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
```
In fs/inode.c (ffffffff8150c7df)
Location: include/linux/time64.h:57
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/arm/xen/enlighten.c (ffff8000100f0160)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffff8000101a4f74)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffff8000103af828)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In kernel/time/timekeeping.c (c03efec8)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (c058f5c8)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In kernel/time/timekeeping.c (c000000000206c44)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (c0000000004ab3a8)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In kernel/time/timekeeping.c (ffffffe0001314f4)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffe0002742aa)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff8101dfd0)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff81133582)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff812f6f32)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In kernel/time/timekeeping.c (ffffffff81125fe2)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff812e7b52)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff8101df90)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff811312a2)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff812f4d42)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
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
In arch/x86/xen/time.c (ffffffff8101e210)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In kernel/time/timekeeping.c (ffffffff8113dcc2)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
```
In fs/inode.c (ffffffff81305ed2)
Location: include/linux/time64.h:60
Inline: True
Inline callers:
  - fs/inode.c:atime_needs_update
  - fs/inode.c:atime_needs_update
```
</details>
</li>
</ul>

## Differences
