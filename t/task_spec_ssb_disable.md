# Function: <code>task_spec_ssb_disable</code>

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
In arch/x86/kernel/cpu/bugs.c (ffffffff81043998)
Location: include/linux/sched.h:1474
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8103a321)
Location: include/linux/sched.h:1480
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104527e)
Location: include/linux/sched.h:1480
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8103c8e1)
Location: include/linux/sched.h:1553
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047d70)
Location: include/linux/sched.h:1553
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
In arch/x86/kernel/process.c (ffffffff8103d0a1)
Location: include/linux/sched.h:1546
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810485c0)
Location: include/linux/sched.h:1546
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
In arch/x86/kernel/process.c (ffffffff8103ff41)
Location: include/linux/sched.h:1588
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c21e)
Location: include/linux/sched.h:1588
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
In arch/x86/kernel/process.c (ffffffff8103fe81)
Location: include/linux/sched.h:1646
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b713)
Location: include/linux/sched.h:1646
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
In arch/x86/kernel/process.c (ffffffff81041811)
Location: include/linux/sched.h:1668
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d3c4)
Location: include/linux/sched.h:1668
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
In arch/x86/kernel/process.c (ffffffff81047ab1)
Location: include/linux/sched.h:1765
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054aae)
Location: include/linux/sched.h:1765
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
In arch/x86/kernel/process.c (ffffffff81050c01)
Location: include/linux/sched.h:1790
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810607fe)
Location: include/linux/sched.h:1790
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
In arch/x86/kernel/process.c (ffffffff8105e161)
Location: include/linux/sched.h:1817
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f06e)
Location: include/linux/sched.h:1817
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
In arch/x86/kernel/process.c (ffffffff8105f811)
Location: include/linux/sched.h:1826
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81070930)
Location: include/linux/sched.h:1826
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
In arch/x86/kernel/process.c (ffffffff81066971)
Location: include/linux/sched.h:1720
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81078214)
Location: include/linux/sched.h:1720
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ssbd.c (ffff8000100ac1a8)
Location: include/linux/sched.h:1546
Inline: True
Inline callers:
  - arch/arm64/kernel/ssbd.c:arch_prctl_spec_ctrl_get
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
In arch/x86/kernel/process.c (ffffffff8103d221)
Location: include/linux/sched.h:1546
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048730)
Location: include/linux/sched.h:1546
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
In arch/x86/kernel/process.c (ffffffff8102c8d1)
Location: include/linux/sched.h:1546
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81037a90)
Location: include/linux/sched.h:1546
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
In arch/x86/kernel/process.c (ffffffff8103d061)
Location: include/linux/sched.h:1546
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048570)
Location: include/linux/sched.h:1546
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
In arch/x86/kernel/process.c (ffffffff8103e0f1)
Location: include/linux/sched.h:1546
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81049980)
Location: include/linux/sched.h:1546
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
```
</details>
</li>
</ul>

## Differences
