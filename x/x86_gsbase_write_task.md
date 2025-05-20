# Function: <code>x86_gsbase_write_task</code>

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
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102d620)
Location: arch/x86/kernel/process_64.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102d620-ffffffff8102d644: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f9dd)
Location: arch/x86/kernel/process_64.c:367
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102f400-ffffffff8102f42b: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103033d)
Location: arch/x86/kernel/process_64.c:367
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102fd60-ffffffff8102fd8b: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032c46)
Location: arch/x86/kernel/process_64.c:365
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff81032600-ffffffff8103262b: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81033912)
Location: arch/x86/kernel/process_64.c:473
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff810332a0-ffffffff810332cb: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81035377)
Location: arch/x86/kernel/process_64.c:473
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81034da0-ffffffff81034dcb: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103a657)
Location: arch/x86/kernel/process_64.c:497
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8103a0c0-ffffffff8103a0eb: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81041706)
Location: arch/x86/kernel/process_64.c:497
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81041110-ffffffff8104114f: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104ae66)
Location: arch/x86/kernel/process_64.c:497
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8104a840-ffffffff8104a87f: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104b774)
Location: arch/x86/kernel/process_64.c:498
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8104b080-ffffffff8104b0bf: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81052a68)
Location: arch/x86/kernel/process_64.c:498
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
Direct callers:
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff810522f0-ffffffff8105232f: x86_gsbase_write_task (STB_GLOBAL)
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
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103049d)
Location: arch/x86/kernel/process_64.c:367
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102fec0-ffffffff8102feeb: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8101ff16)
Location: arch/x86/kernel/process_64.c:367
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8101f920-ffffffff8101f94b: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810302fd)
Location: arch/x86/kernel/process_64.c:367
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff8102fd20-ffffffff8102fd4b: x86_gsbase_write_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void x86_gsbase_write_task(struct task_struct *task, long unsigned int gsbase);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81031178)
Location: arch/x86/kernel/process_64.c:367
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
```
**Symbols:**

```
ffffffff81030b70-ffffffff81030b9b: x86_gsbase_write_task (STB_GLOBAL)
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
