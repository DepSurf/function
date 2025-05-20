# Function: <code>ssb_prctl_set</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81043660)
Location: arch/x86/kernel/cpu/bugs.c:548
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff81043660-ffffffff8104370d: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810451d2)
Location: arch/x86/kernel/cpu/bugs.c:789
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff81044e90-ffffffff81044eb2: ssb_prctl_set.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047820)
Location: arch/x86/kernel/cpu/bugs.c:987
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff81047820-ffffffff810478eb: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048060)
Location: arch/x86/kernel/cpu/bugs.c:1117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff81048060-ffffffff8104812b: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104bc30)
Location: arch/x86/kernel/cpu/bugs.c:1224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff8104bc30-ffffffff8104bd02: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104b170)
Location: arch/x86/kernel/cpu/bugs.c:1218
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff8104b170-ffffffff8104b242: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104ced0)
Location: arch/x86/kernel/cpu/bugs.c:1218
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff8104ced0-ffffffff8104cfa2: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81054540)
Location: arch/x86/kernel/cpu/bugs.c:1358
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff81054540-ffffffff81054612: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810601a0)
Location: arch/x86/kernel/cpu/bugs.c:1860
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff810601a0-ffffffff810602a1: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8106e900)
Location: arch/x86/kernel/cpu/bugs.c:1909
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff8106e900-ffffffff8106ea01: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810700f0)
Location: arch/x86/kernel/cpu/bugs.c:2020
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff810700f0-ffffffff810701f1: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81077910)
Location: arch/x86/kernel/cpu/bugs.c:2161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff81077910-ffffffff81077a11: ssb_prctl_set (STB_LOCAL)
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
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810481d0)
Location: arch/x86/kernel/cpu/bugs.c:1117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff810481d0-ffffffff8104829b: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810374e0)
Location: arch/x86/kernel/cpu/bugs.c:1117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff810374e0-ffffffff810375ab: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048010)
Location: arch/x86/kernel/cpu/bugs.c:1117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff81048010-ffffffff810480db: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ssb_prctl_set(struct task_struct *task, long unsigned int ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81049420)
Location: arch/x86/kernel/cpu/bugs.c:1117
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
```
**Symbols:**

```
ffffffff81049420-ffffffff810494eb: ssb_prctl_set (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
