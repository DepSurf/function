# Function: <code>__ptrace_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108b800)
Location: kernel/ptrace.c:72
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:wait_consider_task
  - kernel/ptrace.c:exit_ptrace
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff8108b800-ffffffff8108b902: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108e800)
Location: kernel/ptrace.c:72
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff8108e800-ffffffff8108e902: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81093770)
Location: kernel/ptrace.c:104
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff81093770-ffffffff81093893: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81090860)
Location: kernel/ptrace.c:113
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff81090860-ffffffff81090983: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810976d0)
Location: kernel/ptrace.c:113
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff810976d0-ffffffff810977f3: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8109afe0)
Location: kernel/ptrace.c:113
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff8109afe0-ffffffff8109b110: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a3210)
Location: kernel/ptrace.c:113
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff810a3210-ffffffff810a3345: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7ee0)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff810a7ee0-ffffffff810a8014: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810ae500)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff810ae500-ffffffff810ae634: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b60a0)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff810b60a0-ffffffff810b61d7: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b1290)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff810b1290-ffffffff810b13c9: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b2850)
Location: kernel/ptrace.c:116
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff810b2850-ffffffff810b2989: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c49f0)
Location: kernel/ptrace.c:116
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff810c49f0-ffffffff810c4b28: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810dbd00)
Location: kernel/ptrace.c:116
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:__ptrace_detach
```
**Symbols:**

```
ffffffff810dbd00-ffffffff810dbe45: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fbe10)
Location: kernel/ptrace.c:116
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:__ptrace_detach
```
**Symbols:**

```
ffffffff810fbe10-ffffffff810fbf55: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81107eb0)
Location: kernel/ptrace.c:117
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:__ptrace_detach
```
**Symbols:**

```
ffffffff81107eb0-ffffffff81107ff5: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81111850)
Location: kernel/ptrace.c:117
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:__ptrace_detach
```
**Symbols:**

```
ffffffff81111850-ffffffff81111983: __ptrace_unlink (STB_GLOBAL)
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
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff8000101084e0)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffff8000101084e0-ffff80001010867c: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c0361ea8)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
c0361ea8-c0361ff8: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014faa0)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
c00000000014faa0-c00000000014fcb0: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffe0000cbe92)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffe0000cbe92-ffffffe0000cbfca: __ptrace_unlink (STB_GLOBAL)
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
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a8870)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff810a8870-ffffffff810a89a4: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81097240)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff81097240-ffffffff81097374: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7dd0)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff810a7dd0-ffffffff810a7f04: __ptrace_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __ptrace_unlink(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810aff00)
Location: kernel/ptrace.c:115
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:exit_ptrace
```
**Symbols:**

```
ffffffff810aff00-ffffffff810b0032: __ptrace_unlink (STB_GLOBAL)
```
</details>
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
