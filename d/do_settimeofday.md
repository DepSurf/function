# Function: <code>do_settimeofday</code>

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
In arch/x86/xen/time.c (ffffffff81f639bb)
Location: include/linux/timekeeping.h:49
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In kernel/time/time.c (ffffffff810eb24d)
Location: include/linux/timekeeping.h:49
Inline: True
Inline callers:
  - kernel/time/time.c:SyS_stime
```
```
In kernel/compat.c (ffffffff81111aa0)
Location: include/linux/timekeeping.h:49
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_stime
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
In arch/x86/xen/time.c (ffffffff81f8b5a0)
Location: include/linux/timekeeping.h:65
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In kernel/time/time.c (ffffffff810f1f0b)
Location: include/linux/timekeeping.h:65
Inline: True
Inline callers:
  - kernel/time/time.c:SyS_stime
```
```
In kernel/compat.c (ffffffff8111921e)
Location: include/linux/timekeeping.h:65
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_stime
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
In arch/x86/xen/time.c (ffffffff81fc6983)
Location: include/linux/timekeeping.h:65
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In kernel/time/time.c (ffffffff810f908b)
Location: include/linux/timekeeping.h:65
Inline: True
Inline callers:
  - kernel/time/time.c:SyS_stime
```
```
In kernel/compat.c (ffffffff81120b9e)
Location: include/linux/timekeeping.h:65
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_stime
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
In arch/x86/xen/time.c (ffffffff820a38a5)
Location: include/linux/timekeeping.h:54
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
```
In kernel/time/time.c (ffffffff810fb43e)
Location: include/linux/timekeeping.h:54
Inline: True
Inline callers:
  - kernel/time/time.c:compat_SyS_stime
  - kernel/time/time.c:SyS_stime
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff826a9d8f)
Location: include/linux/timekeeping32.h:26
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_time_init
```
</details>
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
