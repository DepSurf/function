# Function: <code>task_clear_spec_ssb_disable</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104369f)
Location: include/linux/sched.h:1476
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104512e)
Location: include/linux/sched.h:1482
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
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
In arch/x86/kernel/process.c (ffffffff8103cec3)
Location: include/linux/sched.h:1555
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810478a4)
Location: include/linux/sched.h:1555
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8103d683)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810480e4)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff810407f3)
Location: include/linux/sched.h:1590
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104bce9)
Location: include/linux/sched.h:1590
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff81040743)
Location: include/linux/sched.h:1648
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b229)
Location: include/linux/sched.h:1648
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff81042133)
Location: include/linux/sched.h:1670
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104cf89)
Location: include/linux/sched.h:1670
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff81048483)
Location: include/linux/sched.h:1767
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810545f9)
Location: include/linux/sched.h:1767
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8105178d)
Location: include/linux/sched.h:1792
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81060278)
Location: include/linux/sched.h:1792
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8105eded)
Location: include/linux/sched.h:1819
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106e9d8)
Location: include/linux/sched.h:1819
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff810604f8)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810701b3)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff81067578)
Location: include/linux/sched.h:1722
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810779d3)
Location: include/linux/sched.h:1722
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ssbd.c (ffff8000100abfd0)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_set
```
</details>
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
In arch/x86/kernel/process.c (ffffffff8103d803)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048254)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8102cef3)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81037564)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8103d643)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048094)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
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
In arch/x86/kernel/process.c (ffffffff8103e733)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810494a4)
Location: include/linux/sched.h:1548
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
</details>
</li>
</ul>

## Differences
