# Function: <code>check_rlimit</code>

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
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114424e)
Location: kernel/time/posix-cpu-timers.c:807
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff811434c0-ffffffff811434fb: check_rlimit.part.0 (STB_LOCAL)
ffffffff81144667-ffffffff811446b8: check_rlimit.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811535a8)
Location: kernel/time/posix-cpu-timers.c:800
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8114f868)
Location: kernel/time/posix-cpu-timers.c:812
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81150d3d)
Location: kernel/time/posix-cpu-timers.c:812
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8117510d)
Location: kernel/time/posix-cpu-timers.c:870
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811aa3dd)
Location: kernel/time/posix-cpu-timers.c:877
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811ea3fd)
Location: kernel/time/posix-cpu-timers.c:877
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811feb1d)
Location: kernel/time/posix-cpu-timers.c:878
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff81214da3)
Location: kernel/time/posix-cpu-timers.c:878
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffff8000101ae7c8)
Location: kernel/time/posix-cpu-timers.c:807
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffff8000101ad670-ffff8000101ad710: check_rlimit.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c03f98a0)
Location: kernel/time/posix-cpu-timers.c:807
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
c03f85a0-c03f865c: check_rlimit.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (c000000000212d78)
Location: kernel/time/posix-cpu-timers.c:807
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
c0000000002119d0-c000000000211a8c: check_rlimit.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffe00013824c)
Location: kernel/time/posix-cpu-timers.c:807
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffe0001375e2-ffffffe00013766e: check_rlimit.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113c9fe)
Location: kernel/time/posix-cpu-timers.c:807
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff8113bc70-ffffffff8113bcab: check_rlimit.part.0 (STB_LOCAL)
ffffffff8113ce17-ffffffff8113ce68: check_rlimit.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8112f476)
Location: kernel/time/posix-cpu-timers.c:807
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff8112e630-ffffffff8112e66b: check_rlimit.part.0 (STB_LOCAL)
ffffffff8112f961-ffffffff8112f9b2: check_rlimit.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff8113a71e)
Location: kernel/time/posix-cpu-timers.c:807
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff81139990-ffffffff811399cb: check_rlimit.part.0 (STB_LOCAL)
ffffffff8113ab37-ffffffff8113ab88: check_rlimit.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/posix-cpu-timers.c (ffffffff811471de)
Location: kernel/time/posix-cpu-timers.c:807
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
Direct callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
**Symbols:**

```
ffffffff81146480-ffffffff811464bb: check_rlimit.part.0 (STB_LOCAL)
ffffffff811475ee-ffffffff8114763f: check_rlimit.part.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
