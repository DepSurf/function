# Function: <code>ptrace_get_syscall_info_seccomp</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a6c45)
Location: kernel/ptrace.c:921
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810ad518)
Location: kernel/ptrace.c:926
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (ffffffff810b4d22)
Location: kernel/ptrace.c:926
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (ffffffff810aff02)
Location: kernel/ptrace.c:920
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (ffffffff810b1493)
Location: kernel/ptrace.c:955
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (ffffffff810c3773)
Location: kernel/ptrace.c:955
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (ffffffff810daee9)
Location: kernel/ptrace.c:954
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (ffffffff810fb022)
Location: kernel/ptrace.c:954
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (ffffffff81106eef)
Location: kernel/ptrace.c:955
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
In kernel/ptrace.c (ffffffff8111083f)
Location: kernel/ptrace.c:938
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
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
long unsigned int ptrace_get_syscall_info_seccomp(struct task_struct *child, struct pt_regs *regs, struct ptrace_syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff800010106ab0)
Location: kernel/ptrace.c:926
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
**Symbols:**

```
ffff800010106ab0-ffff800010106b7c: ptrace_get_syscall_info_seccomp (STB_LOCAL)
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
Location: kernel/ptrace.c:926
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014e0f8)
Location: kernel/ptrace.c:926
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffe0000cb89a)
Location: kernel/ptrace.c:926
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7888)
Location: kernel/ptrace.c:926
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81096268)
Location: kernel/ptrace.c:926
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a6de8)
Location: kernel/ptrace.c:926
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810af0b8)
Location: kernel/ptrace.c:926
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
