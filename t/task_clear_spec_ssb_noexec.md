# Function: <code>task_clear_spec_ssb_noexec</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103cecb)
Location: include/linux/sched.h:1559
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047857)
Location: include/linux/sched.h:1559
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff8103d68b)
Location: include/linux/sched.h:1552
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048097)
Location: include/linux/sched.h:1552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff810407fb)
Location: include/linux/sched.h:1594
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104bc67)
Location: include/linux/sched.h:1594
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff8104074b)
Location: include/linux/sched.h:1652
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b1a7)
Location: include/linux/sched.h:1652
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff8104213b)
Location: include/linux/sched.h:1674
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104cf07)
Location: include/linux/sched.h:1674
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff8104848b)
Location: include/linux/sched.h:1771
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054577)
Location: include/linux/sched.h:1771
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff81051795)
Location: include/linux/sched.h:1796
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810601db)
Location: include/linux/sched.h:1796
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff8105edf5)
Location: include/linux/sched.h:1823
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106e93b)
Location: include/linux/sched.h:1823
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff81060500)
Location: include/linux/sched.h:1832
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8107012b)
Location: include/linux/sched.h:1832
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff81067580)
Location: include/linux/sched.h:1726
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8107794b)
Location: include/linux/sched.h:1726
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d80b)
Location: include/linux/sched.h:1552
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048207)
Location: include/linux/sched.h:1552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff8102cefb)
Location: include/linux/sched.h:1552
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81037517)
Location: include/linux/sched.h:1552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff8103d64b)
Location: include/linux/sched.h:1552
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048047)
Location: include/linux/sched.h:1552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/process.c (ffffffff8103e73b)
Location: include/linux/sched.h:1552
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81049457)
Location: include/linux/sched.h:1552
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
</details>
</li>
</ul>

## Differences
