# Function: <code>do_arch_prctl_64</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102ac10)
Location: arch/x86/kernel/process_64.c:602
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:SyS_arch_prctl
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8102ac10-ffffffff8102adf7: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102b950)
Location: arch/x86/kernel/process_64.c:603
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:SyS_arch_prctl
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8102b950-ffffffff8102bb37: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102c980)
Location: arch/x86/kernel/process_64.c:627
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8102c980-ffffffff8102cb60: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102dbe0)
Location: arch/x86/kernel/process_64.c:712
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8102dbe0-ffffffff8102ddac: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102f950)
Location: arch/x86/kernel/process_64.c:703
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8102f950-ffffffff8102fb27: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810302b0)
Location: arch/x86/kernel/process_64.c:703
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff810302b0-ffffffff81030487: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032a60)
Location: arch/x86/kernel/process_64.c:614
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81032a60-ffffffff81032cde: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81033750)
Location: arch/x86/kernel/process_64.c:720
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81033750-ffffffff81033995: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810352f0)
Location: arch/x86/kernel/process_64.c:720
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff810352f0-ffffffff810354bf: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103a5d0)
Location: arch/x86/kernel/process_64.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8103a5d0-ffffffff8103a79f: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81041660)
Location: arch/x86/kernel/process_64.c:745
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81041660-ffffffff8104189f: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104adc0)
Location: arch/x86/kernel/process_64.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8104adc0-ffffffff8104afff: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104b600)
Location: arch/x86/kernel/process_64.c:793
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8104b600-ffffffff8104b899: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81052870)
Location: arch/x86/kernel/process_64.c:795
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process.c:copy_thread
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81052870-ffffffff81052b17: do_arch_prctl_64 (STB_GLOBAL)
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
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030410)
Location: arch/x86/kernel/process_64.c:703
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81030410-ffffffff810305e7: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8101fe90)
Location: arch/x86/kernel/process_64.c:703
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff8101fe90-ffffffff8102007e: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030270)
Location: arch/x86/kernel/process_64.c:703
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff81030270-ffffffff81030447: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_arch_prctl_64(struct task_struct *task, int option, long unsigned int arg2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810310e0)
Location: arch/x86/kernel/process_64.c:703
Inline: False
Direct callers:
  - arch/x86/kernel/process_64.c:__ia32_sys_arch_prctl
  - arch/x86/kernel/process_64.c:__x64_sys_arch_prctl
  - arch/x86/kernel/process_64.c:copy_thread_tls
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
**Symbols:**

```
ffffffff810310e0-ffffffff810312dc: do_arch_prctl_64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
