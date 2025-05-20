# Function: <code>ptrace_set_debugreg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c250)
Location: arch/x86/kernel/ptrace.c:753
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103c250-ffffffff8103c400: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103bf90)
Location: arch/x86/kernel/ptrace.c:706
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8103bf90-ffffffff8103c140: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103b590)
Location: arch/x86/kernel/ptrace.c:706
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8103b590-ffffffff8103b740: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810395e0)
Location: arch/x86/kernel/ptrace.c:707
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff810395e0-ffffffff81039779: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103bfe0)
Location: arch/x86/kernel/ptrace.c:707
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8103bfe0-ffffffff8103c179: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d4d0)
Location: arch/x86/kernel/ptrace.c:707
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8103d4d0-ffffffff8103d666: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103ea60)
Location: arch/x86/kernel/ptrace.c:698
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8103ea60-ffffffff8103ebf6: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041326)
Location: arch/x86/kernel/ptrace.c:673
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff810412e0-ffffffff81041477: ptrace_set_debugreg (STB_LOCAL)
ffffffff810426eb-ffffffff810426fe: ptrace_set_debugreg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041a70)
Location: arch/x86/kernel/ptrace.c:673
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81041a70-ffffffff81041c06: ptrace_set_debugreg (STB_LOCAL)
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
In arch/x86/kernel/ptrace.c (ffffffff81045b69)
Location: arch/x86/kernel/ptrace.c:685
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
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
In arch/x86/kernel/ptrace.c (ffffffff810455e3)
Location: arch/x86/kernel/ptrace.c:650
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810465a0)
Location: arch/x86/kernel/ptrace.c:650
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff810465a0-ffffffff81046744: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104cc80)
Location: arch/x86/kernel/ptrace.c:650
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8104cc80-ffffffff8104ce7c: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81057de0)
Location: arch/x86/kernel/ptrace.c:649
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81057de0-ffffffff81058007: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81065610)
Location: arch/x86/kernel/ptrace.c:668
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81065610-ffffffff81065837: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81066dc0)
Location: arch/x86/kernel/ptrace.c:668
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81066dc0-ffffffff81066fdb: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106e240)
Location: arch/x86/kernel/ptrace.c:669
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8106e240-ffffffff8106e45b: ptrace_set_debugreg (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptrace_set_debugreg(struct task_struct *task, long unsigned int addr, long unsigned int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c000000000011e40)
Location: arch/powerpc/kernel/ptrace.c:2385
Inline: False
Direct callers:
  - arch/powerpc/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
c000000000011e40-c0000000000120fc: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041bf0)
Location: arch/x86/kernel/ptrace.c:673
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81041bf0-ffffffff81041d86: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810312b0)
Location: arch/x86/kernel/ptrace.c:673
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff810312b0-ffffffff81031446: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041a30)
Location: arch/x86/kernel/ptrace.c:673
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81041a30-ffffffff81041bc6: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ptrace_set_debugreg(struct task_struct *tsk, int n, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042e10)
Location: arch/x86/kernel/ptrace.c:673
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81042e10-ffffffff81042fa6: ptrace_set_debugreg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int data</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>int n</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int val</code>
</li>
</ul>
</details>
</li>
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
