# Function: <code>posix_cputimers_init</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109ed29)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81143fb5)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff810a633d)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81153a05)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff810a1c4a)
Location: include/linux/posix-timers.h:139
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8114fe75)
Location: include/linux/posix-timers.h:139
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff810a2aaf)
Location: include/linux/posix-timers.h:139
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811512a5)
Location: include/linux/posix-timers.h:139
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff810b41d4)
Location: include/linux/posix-timers.h:146
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81175675)
Location: include/linux/posix-timers.h:146
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff810ca537)
Location: include/linux/posix-timers.h:145
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811aa595)
Location: include/linux/posix-timers.h:145
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff810e7ba0)
Location: include/linux/posix-timers.h:145
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ea625)
Location: include/linux/posix-timers.h:145
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff810f37c0)
Location: include/linux/posix-timers.h:150
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811fed55)
Location: include/linux/posix-timers.h:150
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff810fcb91)
Location: include/linux/posix-timers.h:88
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff812150a5)
Location: include/linux/posix-timers.h:88
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffff8000100f386c)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ae53c)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (c035200c)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (c03f9528)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (c000000000139640)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (c000000000212ab4)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffe0000bffde)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffe00013803e)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff81098649)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113c765)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff810870b3)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f205)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff810985f9)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113a485)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
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
In kernel/fork.c (ffffffff810a0220)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81146f45)
Location: include/linux/posix-timers.h:128
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_group_init
```
</details>
</li>
</ul>

## Differences
