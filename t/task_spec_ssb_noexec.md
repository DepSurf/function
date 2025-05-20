# Function: <code>task_spec_ssb_noexec</code>

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
In arch/x86/kernel/process.c (ffffffff8103ceab)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047d60)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8103d66b)
Location: include/linux/sched.h:1550
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810485b0)
Location: include/linux/sched.h:1550
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff810407db)
Location: include/linux/sched.h:1592
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c20e)
Location: include/linux/sched.h:1592
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8104072b)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b703)
Location: include/linux/sched.h:1650
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8104211b)
Location: include/linux/sched.h:1672
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d3b4)
Location: include/linux/sched.h:1672
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8104846b)
Location: include/linux/sched.h:1769
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054a9e)
Location: include/linux/sched.h:1769
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8105176b)
Location: include/linux/sched.h:1794
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810607ee)
Location: include/linux/sched.h:1794
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8105edcb)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f05e)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff810604bb)
Location: include/linux/sched.h:1830
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81070920)
Location: include/linux/sched.h:1830
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8106753b)
Location: include/linux/sched.h:1724
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81078204)
Location: include/linux/sched.h:1724
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8103d7eb)
Location: include/linux/sched.h:1550
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048720)
Location: include/linux/sched.h:1550
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8102cedb)
Location: include/linux/sched.h:1550
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81037a80)
Location: include/linux/sched.h:1550
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8103d62b)
Location: include/linux/sched.h:1550
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048560)
Location: include/linux/sched.h:1550
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8103e71b)
Location: include/linux/sched.h:1550
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:arch_setup_new_exec
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81049970)
Location: include/linux/sched.h:1550
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
```
</details>
</li>
</ul>

## Differences
