# Function: <code>can_madv_dontneed_vma</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/internal.h:46
Inline: True
```
```
In mm/madvise.c (0)
Location: mm/internal.h:46
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
In mm/oom_kill.c (0)
Location: mm/internal.h:46
Inline: True
```
```
In mm/madvise.c (0)
Location: mm/internal.h:46
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
In mm/oom_kill.c (ffffffff811f2dc1)
Location: mm/internal.h:46
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/madvise.c (ffffffff81245288)
Location: mm/internal.h:46
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
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
In mm/oom_kill.c (ffffffff81204e2d)
Location: mm/internal.h:46
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/madvise.c (ffffffff812598bb)
Location: mm/internal.h:46
Inline: True
Inline callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
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
In mm/oom_kill.c (ffffffff8121c8b5)
Location: mm/internal.h:42
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/madvise.c (ffffffff81274ead)
Location: mm/internal.h:42
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
  - mm/madvise.c:__do_sys_madvise
```
</details>
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
