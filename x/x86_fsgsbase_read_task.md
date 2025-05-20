# Function: <code>x86_fsgsbase_read_task</code>

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
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d2e0)
Location: arch/x86/kernel/process_64.c:298
Inline: False
```
**Symbols:**

```
ffffffff8102d2e0-ffffffff8102d3aa: x86_fsgsbase_read_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f000)
Location: arch/x86/kernel/process_64.c:289
Inline: False
```
**Symbols:**

```
ffffffff8102f000-ffffffff8102f0d1: x86_fsgsbase_read_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f960)
Location: arch/x86/kernel/process_64.c:289
Inline: False
```
**Symbols:**

```
ffffffff8102f960-ffffffff8102fa31: x86_fsgsbase_read_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032130)
Location: arch/x86/kernel/process_64.c:287
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff81032130-ffffffff81032206: x86_fsgsbase_read_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81033030)
Location: arch/x86/kernel/process_64.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
```
**Symbols:**

```
ffffffff81033030-ffffffff810330ff: x86_fsgsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81034ac0)
Location: arch/x86/kernel/process_64.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
```
**Symbols:**

```
ffffffff81034ac0-ffffffff81034b8f: x86_fsgsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81039dc0)
Location: arch/x86/kernel/process_64.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
```
**Symbols:**

```
ffffffff81039dc0-ffffffff81039eae: x86_fsgsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81040d70)
Location: arch/x86/kernel/process_64.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
```
**Symbols:**

```
ffffffff81040d70-ffffffff81040e79: x86_fsgsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104a440)
Location: arch/x86/kernel/process_64.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
```
**Symbols:**

```
ffffffff8104a440-ffffffff8104a549: x86_fsgsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104ac80)
Location: arch/x86/kernel/process_64.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
```
**Symbols:**

```
ffffffff8104ac80-ffffffff8104ad89: x86_fsgsbase_read_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81051ef0)
Location: arch/x86/kernel/process_64.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:x86_gsbase_read_task
  - arch/x86/kernel/process_64.c:x86_fsbase_read_task
  - arch/x86/kernel/ptrace.c:putreg32
  - arch/x86/kernel/ptrace.c:putreg32
```
**Symbols:**

```
ffffffff81051ef0-ffffffff81051ff9: x86_fsgsbase_read_task (STB_GLOBAL)
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
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fac0)
Location: arch/x86/kernel/process_64.c:289
Inline: False
```
**Symbols:**

```
ffffffff8102fac0-ffffffff8102fb91: x86_fsgsbase_read_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8101f4e0)
Location: arch/x86/kernel/process_64.c:289
Inline: False
```
**Symbols:**

```
ffffffff8101f4e0-ffffffff8101f5b1: x86_fsgsbase_read_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f920)
Location: arch/x86/kernel/process_64.c:289
Inline: False
```
**Symbols:**

```
ffffffff8102f920-ffffffff8102f9f1: x86_fsgsbase_read_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int x86_fsgsbase_read_task(struct task_struct *task, short unsigned int selector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030770)
Location: arch/x86/kernel/process_64.c:289
Inline: False
```
**Symbols:**

```
ffffffff81030770-ffffffff81030841: x86_fsgsbase_read_task (STB_LOCAL)
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
