# Function: <code>hook_ptrace_traceme</code>

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
int hook_ptrace_traceme(const struct task_struct * parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff81538500)
Location: security/landlock/ptrace.c:111
Inline: False
```
**Symbols:**

```
ffffffff81538500-ffffffff81538579: hook_ptrace_traceme (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hook_ptrace_traceme(const struct task_struct * parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff81596cf0)
Location: security/landlock/ptrace.c:111
Inline: False
```
**Symbols:**

```
ffffffff81596cf0-ffffffff81596d69: hook_ptrace_traceme (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hook_ptrace_traceme(const struct task_struct * parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff816391b0)
Location: security/landlock/ptrace.c:106
Inline: False
```
**Symbols:**

```
ffffffff816391b0-ffffffff816391d1: hook_ptrace_traceme (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hook_ptrace_traceme(const struct task_struct * parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff816f0720)
Location: security/landlock/ptrace.c:106
Inline: False
```
**Symbols:**

```
ffffffff816f0720-ffffffff816f0741: hook_ptrace_traceme (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hook_ptrace_traceme(const struct task_struct * parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff8172abc0)
Location: security/landlock/ptrace.c:106
Inline: False
```
**Symbols:**

```
ffffffff8172abc0-ffffffff8172abe1: hook_ptrace_traceme (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hook_ptrace_traceme(const struct task_struct * parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff8176c5a0)
Location: security/landlock/ptrace.c:106
Inline: False
```
**Symbols:**

```
ffffffff8176c5a0-ffffffff8176c5c1: hook_ptrace_traceme (STB_LOCAL)
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
