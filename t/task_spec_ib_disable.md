# Function: <code>task_spec_ib_disable</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103a330)
Location: include/linux/sched.h:1487
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81045247)
Location: include/linux/sched.h:1487
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
In arch/x86/kernel/process.c (ffffffff8103c8f0)
Location: include/linux/sched.h:1564
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047d2a)
Location: include/linux/sched.h:1564
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
In arch/x86/kernel/process.c (ffffffff8103d0b0)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104857a)
Location: include/linux/sched.h:1557
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
In arch/x86/kernel/process.c (ffffffff8103ff50)
Location: include/linux/sched.h:1599
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c1cb)
Location: include/linux/sched.h:1599
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
In arch/x86/kernel/process.c (ffffffff8103fe90)
Location: include/linux/sched.h:1657
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b6c0)
Location: include/linux/sched.h:1657
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
In arch/x86/kernel/process.c (ffffffff81041820)
Location: include/linux/sched.h:1679
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d371)
Location: include/linux/sched.h:1679
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
In arch/x86/kernel/process.c (ffffffff81047ac0)
Location: include/linux/sched.h:1776
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054b1c)
Location: include/linux/sched.h:1776
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
In arch/x86/kernel/process.c (ffffffff81050c10)
Location: include/linux/sched.h:1801
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81060890)
Location: include/linux/sched.h:1801
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
In arch/x86/kernel/process.c (ffffffff8105e170)
Location: include/linux/sched.h:1828
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106f0ea)
Location: include/linux/sched.h:1828
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
In arch/x86/kernel/process.c (ffffffff8105f820)
Location: include/linux/sched.h:1837
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810709ad)
Location: include/linux/sched.h:1837
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
In arch/x86/kernel/process.c (ffffffff81066980)
Location: include/linux/sched.h:1731
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8107829d)
Location: include/linux/sched.h:1731
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
In arch/x86/kernel/process.c (ffffffff8103d230)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff810486ea)
Location: include/linux/sched.h:1557
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
In arch/x86/kernel/process.c (ffffffff8102c8e0)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81037a4a)
Location: include/linux/sched.h:1557
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
In arch/x86/kernel/process.c (ffffffff8103d070)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104852a)
Location: include/linux/sched.h:1557
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
In arch/x86/kernel/process.c (ffffffff8103e100)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:speculation_ctrl_update_tif
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104993a)
Location: include/linux/sched.h:1557
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_get
```
</details>
</li>
</ul>

## Differences
