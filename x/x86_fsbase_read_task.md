# Function: <code>x86_fsbase_read_task</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d550)
Location: arch/x86/kernel/process_64.c:341
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102d550-ffffffff8102d591: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f330)
Location: arch/x86/kernel/process_64.c:332
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102f330-ffffffff8102f371: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fc90)
Location: arch/x86/kernel/process_64.c:332
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102fc90-ffffffff8102fcd1: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032a9a)
Location: arch/x86/kernel/process_64.c:330
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:getreg
```
**Symbols:**

```
ffffffff81032530-ffffffff81032571: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810331c0)
Location: arch/x86/kernel/process_64.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/ptrace.c:getreg
```
**Symbols:**

```
ffffffff810331c0-ffffffff8103321d: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81034c70)
Location: arch/x86/kernel/process_64.c:436
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/ptrace.c:getreg
```
**Symbols:**

```
ffffffff81034c70-ffffffff81034ccd: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81039f90)
Location: arch/x86/kernel/process_64.c:460
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/ptrace.c:getreg
```
**Symbols:**

```
ffffffff81039f90-ffffffff81039fed: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81040f50)
Location: arch/x86/kernel/process_64.c:460
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/ptrace.c:getreg
```
**Symbols:**

```
ffffffff81040f50-ffffffff8104100c: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104a650)
Location: arch/x86/kernel/process_64.c:460
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/ptrace.c:getreg
```
**Symbols:**

```
ffffffff8104a650-ffffffff8104a70c: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104ae90)
Location: arch/x86/kernel/process_64.c:461
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/ptrace.c:getreg
```
**Symbols:**

```
ffffffff8104ae90-ffffffff8104af4c: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81052100)
Location: arch/x86/kernel/process_64.c:461
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/ptrace.c:getreg
```
**Symbols:**

```
ffffffff81052100-ffffffff810521bc: x86_fsbase_read_task (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fdf0)
Location: arch/x86/kernel/process_64.c:332
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102fdf0-ffffffff8102fe31: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8101f810)
Location: arch/x86/kernel/process_64.c:332
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8101f810-ffffffff8101f875: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fc50)
Location: arch/x86/kernel/process_64.c:332
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102fc50-ffffffff8102fc91: x86_fsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int x86_fsbase_read_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030aa0)
Location: arch/x86/kernel/process_64.c:332
Inline: True
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff81030aa0-ffffffff81030ae1: x86_fsbase_read_task (STB_GLOBAL)
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
