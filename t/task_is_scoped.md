# Function: <code>task_is_scoped</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool task_is_scoped(const const struct task_struct * parent, const const struct task_struct * child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff81538480)
Location: security/landlock/ptrace.c:55
Inline: False
Direct callers:
  - security/landlock/ptrace.c:hook_ptrace_traceme
  - security/landlock/ptrace.c:hook_ptrace_access_check
```
**Symbols:**

```
ffffffff81538480-ffffffff815384fb: task_is_scoped (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool task_is_scoped(const const struct task_struct * parent, const const struct task_struct * child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff81596c70)
Location: security/landlock/ptrace.c:55
Inline: False
Direct callers:
  - security/landlock/ptrace.c:hook_ptrace_traceme
  - security/landlock/ptrace.c:hook_ptrace_access_check
```
**Symbols:**

```
ffffffff81596c70-ffffffff81596ceb: task_is_scoped (STB_LOCAL)
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
In security/landlock/ptrace.c (ffffffff81639117)
Location: security/landlock/ptrace.c:50
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
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
In security/landlock/ptrace.c (ffffffff816f0677)
Location: security/landlock/ptrace.c:50
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
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
In security/landlock/ptrace.c (ffffffff8172ab17)
Location: security/landlock/ptrace.c:50
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
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
In security/landlock/ptrace.c (ffffffff8176c4fd)
Location: security/landlock/ptrace.c:50
Inline: True
Inline callers:
  - security/landlock/ptrace.c:task_ptrace
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
