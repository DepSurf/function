# Function: <code>task_update_spec_tif</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void task_update_spec_tif(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81044e60)
Location: arch/x86/kernel/cpu/bugs.c:772
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff81044e60-ffffffff81044e85: task_update_spec_tif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void task_update_spec_tif(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810477f0)
Location: arch/x86/kernel/cpu/bugs.c:970
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff810477f0-ffffffff81047814: task_update_spec_tif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void task_update_spec_tif(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048030)
Location: arch/x86/kernel/cpu/bugs.c:1100
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff81048030-ffffffff81048054: task_update_spec_tif (STB_LOCAL)
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c106)
Location: arch/x86/kernel/cpu/bugs.c:1207
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b63e)
Location: arch/x86/kernel/cpu/bugs.c:1201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8104d2ee)
Location: arch/x86/kernel/cpu/bugs.c:1201
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/cpu/bugs.c (ffffffff81054a1e)
Location: arch/x86/kernel/cpu/bugs.c:1323
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/cpu/bugs.c (ffffffff810600df)
Location: arch/x86/kernel/cpu/bugs.c:1825
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8106e7d3)
Location: arch/x86/kernel/cpu/bugs.c:1874
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/cpu/bugs.c (ffffffff8106ffb3)
Location: arch/x86/kernel/cpu/bugs.c:1985
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
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
In arch/x86/kernel/cpu/bugs.c (ffffffff810777d3)
Location: arch/x86/kernel/cpu/bugs.c:2126
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
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
<summary>In <code>aws</code>: ✅</summary>

```c
void task_update_spec_tif(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810481a0)
Location: arch/x86/kernel/cpu/bugs.c:1100
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff810481a0-ffffffff810481c4: task_update_spec_tif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void task_update_spec_tif(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810374b0)
Location: arch/x86/kernel/cpu/bugs.c:1100
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff810374b0-ffffffff810374d4: task_update_spec_tif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void task_update_spec_tif(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047fe0)
Location: arch/x86/kernel/cpu/bugs.c:1100
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff81047fe0-ffffffff81048004: task_update_spec_tif (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void task_update_spec_tif(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810493f0)
Location: arch/x86/kernel/cpu/bugs.c:1100
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff810493f0-ffffffff81049414: task_update_spec_tif (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
