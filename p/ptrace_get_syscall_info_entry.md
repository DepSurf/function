# Function: <code>ptrace_get_syscall_info_entry</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a6a90)
Location: kernel/ptrace.c:904
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff810a6a90-ffffffff810a6b4a: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810ad070)
Location: kernel/ptrace.c:909
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff810ad070-ffffffff810ad12a: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b4b60)
Location: kernel/ptrace.c:909
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff810b4b60-ffffffff810b4c1d: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810afd40)
Location: kernel/ptrace.c:903
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff810afd40-ffffffff810afdfd: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b12d0)
Location: kernel/ptrace.c:938
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff810b12d0-ffffffff810b1389: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c3580)
Location: kernel/ptrace.c:938
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff810c3580-ffffffff810c3663: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810dace0)
Location: kernel/ptrace.c:937
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff810dace0-ffffffff810dadd5: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fae10)
Location: kernel/ptrace.c:937
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff810fae10-ffffffff810faf05: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81106a30)
Location: kernel/ptrace.c:938
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff81106a30-ffffffff81106b53: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81110380)
Location: kernel/ptrace.c:921
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff81110380-ffffffff811104a3: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffff800010106aec)
Location: kernel/ptrace.c:909
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info_seccomp
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffff800010106b80-ffff800010106c2c: ptrace_get_syscall_info_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c03619d4)
Location: kernel/ptrace.c:909
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014dd10)
Location: kernel/ptrace.c:909
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
c00000000014dd10-c00000000014de0c: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffe0000cb79a)
Location: kernel/ptrace.c:909
Inline: True
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffe0000cb79a-ffffffe0000cb80e: ptrace_get_syscall_info_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a73e0)
Location: kernel/ptrace.c:909
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff810a73e0-ffffffff810a749a: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81095dc0)
Location: kernel/ptrace.c:909
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff81095dc0-ffffffff81095e7a: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a6940)
Location: kernel/ptrace.c:909
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff810a6940-ffffffff810a69fa: ptrace_get_syscall_info_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int ptrace_get_syscall_info_entry(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810aea90)
Location: kernel/ptrace.c:909
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffffffff810aea90-ffffffff810aeb4a: ptrace_get_syscall_info_entry (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
