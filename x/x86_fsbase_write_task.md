# Function: <code>x86_fsbase_write_task</code>

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
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d5f0)
Location: arch/x86/kernel/process_64.c:369
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102d5f0-ffffffff8102d614: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fa82)
Location: arch/x86/kernel/process_64.c:360
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102f3d0-ffffffff8102f3fb: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810303e2)
Location: arch/x86/kernel/process_64.c:360
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102fd30-ffffffff8102fd5b: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032b9f)
Location: arch/x86/kernel/process_64.c:358
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff810325d0-ffffffff810325fb: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810338c8)
Location: arch/x86/kernel/process_64.c:466
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81033270-ffffffff8103329b: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103541f)
Location: arch/x86/kernel/process_64.c:466
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81034d70-ffffffff81034d9b: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103a6ff)
Location: arch/x86/kernel/process_64.c:490
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8103a090-ffffffff8103a0bb: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810417c5)
Location: arch/x86/kernel/process_64.c:490
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff810410d0-ffffffff8104110f: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104af25)
Location: arch/x86/kernel/process_64.c:490
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8104a7f0-ffffffff8104a82f: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104b67f)
Location: arch/x86/kernel/process_64.c:491
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8104b030-ffffffff8104b06f: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8105292b)
Location: arch/x86/kernel/process_64.c:491
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff810522a0-ffffffff810522df: x86_fsbase_write_task (STB_GLOBAL)
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
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030542)
Location: arch/x86/kernel/process_64.c:360
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102fe90-ffffffff8102febb: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8101ffc2)
Location: arch/x86/kernel/process_64.c:360
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8101f8f0-ffffffff8101f91b: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810303a2)
Location: arch/x86/kernel/process_64.c:360
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102fcf0-ffffffff8102fd1b: x86_fsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void x86_fsbase_write_task(struct task_struct *task, long unsigned int fsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81031231)
Location: arch/x86/kernel/process_64.c:360
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff81030b40-ffffffff81030b6b: x86_fsbase_write_task (STB_GLOBAL)
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
