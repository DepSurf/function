# Function: <code>hook_ptrace_access_check</code>

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
int hook_ptrace_access_check(const struct task_struct * child, const unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff81538580)
Location: security/landlock/ptrace.c:93
Inline: False
```
**Symbols:**

```
ffffffff81538580-ffffffff815385be: hook_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hook_ptrace_access_check(const struct task_struct * child, const unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff81596d70)
Location: security/landlock/ptrace.c:93
Inline: False
```
**Symbols:**

```
ffffffff81596d70-ffffffff81596dae: hook_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hook_ptrace_access_check(const struct task_struct * child, const unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff816391e0)
Location: security/landlock/ptrace.c:88
Inline: False
```
**Symbols:**

```
ffffffff816391e0-ffffffff81639204: hook_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hook_ptrace_access_check(const struct task_struct * child, const unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff816f0760)
Location: security/landlock/ptrace.c:88
Inline: False
```
**Symbols:**

```
ffffffff816f0760-ffffffff816f0784: hook_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hook_ptrace_access_check(const struct task_struct * child, const unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff8172ac00)
Location: security/landlock/ptrace.c:88
Inline: False
```
**Symbols:**

```
ffffffff8172ac00-ffffffff8172ac24: hook_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hook_ptrace_access_check(const struct task_struct * child, const unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/ptrace.c (ffffffff8176c5e0)
Location: security/landlock/ptrace.c:88
Inline: False
```
**Symbols:**

```
ffffffff8176c5e0-ffffffff8176c604: hook_ptrace_access_check (STB_LOCAL)
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
