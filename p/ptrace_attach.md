# Function: <code>ptrace_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108add0)
Location: kernel/ptrace.c:316
Inline: False
Direct callers:
  - kernel/ptrace.c:SyS_ptrace
  - kernel/ptrace.c:compat_SyS_ptrace
```
**Symbols:**

```
ffffffff8108add0-ffffffff8108b08a: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108ddc0)
Location: kernel/ptrace.c:315
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff8108ddc0-ffffffff8108e07f: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81093510)
Location: kernel/ptrace.c:328
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff81093510-ffffffff81093762: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81090600)
Location: kernel/ptrace.c:343
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff81090600-ffffffff8109085c: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81097470)
Location: kernel/ptrace.c:343
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_SyS_ptrace
  - kernel/ptrace.c:SyS_ptrace
```
**Symbols:**

```
ffffffff81097470-ffffffff810976cc: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8109a940)
Location: kernel/ptrace.c:343
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff8109a940-ffffffff8109abbd: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a2b70)
Location: kernel/ptrace.c:343
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a2b70-ffffffff810a2ded: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7830)
Location: kernel/ptrace.c:358
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a7830-ffffffff810a7abb: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810ade50)
Location: kernel/ptrace.c:363
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810ade50-ffffffff810ae0db: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b5930)
Location: kernel/ptrace.c:363
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810b5930-ffffffff810b5bbb: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b0b20)
Location: kernel/ptrace.c:357
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810b0b20-ffffffff810b0dab: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b20c0)
Location: kernel/ptrace.c:374
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810b20c0-ffffffff810b234b: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c3ed0)
Location: kernel/ptrace.c:374
Inline: False
Direct callers:
  - kernel/ptrace.c:__x64_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810c3ed0-ffffffff810c41b6: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810db4d0)
Location: kernel/ptrace.c:388
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810db4d0-ffffffff810db795: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fb590)
Location: kernel/ptrace.c:388
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810fb590-ffffffff810fb850: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81107630)
Location: kernel/ptrace.c:389
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81107630-ffffffff811078f0: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81110f90)
Location: kernel/ptrace.c:406
Inline: False
Direct callers:
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81110f90-ffffffff81111285: ptrace_attach (STB_LOCAL)
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
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff800010107f58)
Location: kernel/ptrace.c:363
Inline: False
Direct callers:
  - kernel/ptrace.c:__arm64_compat_sys_ptrace
  - kernel/ptrace.c:__arm64_sys_ptrace
```
**Symbols:**

```
ffff800010107f58-ffff800010108274: ptrace_attach (STB_LOCAL)
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
In kernel/ptrace.c (c03624e0)
Location: kernel/ptrace.c:363
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014f320)
Location: kernel/ptrace.c:363
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_compat_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
```
**Symbols:**

```
c00000000014f320-c00000000014f6fc: ptrace_attach (STB_LOCAL)
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
In kernel/ptrace.c (ffffffe0000cc3aa)
Location: kernel/ptrace.c:363
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
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
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a81c0)
Location: kernel/ptrace.c:363
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a81c0-ffffffff810a844b: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81096b80)
Location: kernel/ptrace.c:363
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff81096b80-ffffffff81096e1c: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7720)
Location: kernel/ptrace.c:363
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810a7720-ffffffff810a79ab: ptrace_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptrace_attach(struct task_struct *task, long int request, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810af840)
Location: kernel/ptrace.c:363
Inline: False
Direct callers:
  - kernel/ptrace.c:__x32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_compat_sys_ptrace
  - kernel/ptrace.c:__ia32_sys_ptrace
  - kernel/ptrace.c:__x64_sys_ptrace
```
**Symbols:**

```
ffffffff810af840-ffffffff810afadb: ptrace_attach (STB_LOCAL)
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
