# Function: <code>ptrace_get_syscall_info</code>

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
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a6b50)
Location: kernel/ptrace.c:954
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810a6b50-ffffffff810a6d03: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810ad410)
Location: kernel/ptrace.c:959
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810ad410-ffffffff810ad5fc: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b4c20)
Location: kernel/ptrace.c:959
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810b4c20-ffffffff810b4dfa: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810afe00)
Location: kernel/ptrace.c:953
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810afe00-ffffffff810affda: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b1390)
Location: kernel/ptrace.c:988
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810b1390-ffffffff810b156c: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c3670)
Location: kernel/ptrace.c:988
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810c3670-ffffffff810c384c: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810dade0)
Location: kernel/ptrace.c:987
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810dade0-ffffffff810dafb0: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810faf20)
Location: kernel/ptrace.c:987
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810faf20-ffffffff810fb0e5: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81106e50)
Location: kernel/ptrace.c:988
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81106e50-ffffffff81107019: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff811107a0)
Location: kernel/ptrace.c:971
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff811107a0-ffffffff81110969: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff800010107810)
Location: kernel/ptrace.c:959
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffff800010107810-ffff800010107b24: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c03618d0)
Location: kernel/ptrace.c:959
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
c03618d0-c0361b3c: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014e050)
Location: kernel/ptrace.c:959
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
c00000000014e050-c00000000014e2e8: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffe0000cb80e)
Location: kernel/ptrace.c:959
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffe0000cb80e-ffffffe0000cb9aa: ptrace_get_syscall_info (STB_LOCAL)
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
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7780)
Location: kernel/ptrace.c:959
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810a7780-ffffffff810a796c: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81096160)
Location: kernel/ptrace.c:959
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81096160-ffffffff8109634c: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a6ce0)
Location: kernel/ptrace.c:959
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810a6ce0-ffffffff810a6ecc: ptrace_get_syscall_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptrace_get_syscall_info(struct task_struct *child, long unsigned int user_size, void *datavp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810aefb0)
Location: kernel/ptrace.c:959
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810aefb0-ffffffff810af19c: ptrace_get_syscall_info (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
