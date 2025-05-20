# Function: <code>ptrace_get_task_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *ptrace_get_task_struct(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108ac00)
Location: kernel/ptrace.c:1074
Inline: False
Direct callers:
  - kernel/ptrace.c:SyS_ptrace
  - kernel/ptrace.c:compat_SyS_ptrace
```
**Symbols:**

```
ffffffff8108ac00-ffffffff8108ac26: ptrace_get_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *ptrace_get_task_struct(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108dbf0)
Location: kernel/ptrace.c:1079
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff8108dbf0-ffffffff8108dc12: ptrace_get_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *ptrace_get_task_struct(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810929f0)
Location: kernel/ptrace.c:1089
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff810929f0-ffffffff81092a12: ptrace_get_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *ptrace_get_task_struct(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108fb30)
Location: kernel/ptrace.c:1104
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff8108fb30-ffffffff8108fb52: ptrace_get_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *ptrace_get_task_struct(pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810969f0)
Location: kernel/ptrace.c:1102
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff810969f0-ffffffff81096a12: ptrace_get_task_struct (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
