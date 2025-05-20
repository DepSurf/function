# Function: <code>task_current_syscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81413770)
Location: lib/syscall.c:50
Inline: False
```
**Symbols:**

```
ffffffff81413770-ffffffff814139bc: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff8145b480)
Location: lib/syscall.c:50
Inline: False
```
**Symbols:**

```
ffffffff8145b480-ffffffff8145b6cf: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff8147a100)
Location: lib/syscall.c:61
Inline: False
```
**Symbols:**

```
ffffffff8147a100-ffffffff8147a1aa: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff814833f0)
Location: lib/syscall.c:63
Inline: False
```
**Symbols:**

```
ffffffff814833f0-ffffffff814834a3: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff814bf430)
Location: lib/syscall.c:64
Inline: False
```
**Symbols:**

```
ffffffff814bf430-ffffffff814bf4e3: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff814f0490)
Location: lib/syscall.c:64
Inline: False
```
**Symbols:**

```
ffffffff814f0490-ffffffff814f0543: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff815043b0)
Location: lib/syscall.c:64
Inline: False
```
**Symbols:**

```
ffffffff815043b0-ffffffff81504463: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff815324e0)
Location: lib/syscall.c:62
Inline: False
```
**Symbols:**

```
ffffffff815324e0-ffffffff81532562: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81553320)
Location: lib/syscall.c:62
Inline: False
```
**Symbols:**

```
ffffffff81553320-ffffffff815533a2: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff815dc710)
Location: lib/syscall.c:62
Inline: False
```
**Symbols:**

```
ffffffff815dc710-ffffffff815dc796: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff815fa380)
Location: lib/syscall.c:69
Inline: False
```
**Symbols:**

```
ffffffff815fa380-ffffffff815fa402: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff815dcf60)
Location: lib/syscall.c:69
Inline: False
```
**Symbols:**

```
ffffffff815dcf60-ffffffff815dcfe2: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff816488c0)
Location: lib/syscall.c:69
Inline: False
```
**Symbols:**

```
ffffffff816488c0-ffffffff81648942: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff8175ed10)
Location: lib/syscall.c:69
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_syscall
```
**Symbols:**

```
ffffffff8175ed10-ffffffff8175eda2: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff8188c640)
Location: lib/syscall.c:69
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_syscall
```
**Symbols:**

```
ffffffff8188c640-ffffffff8188c6d2: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff818ceaa0)
Location: lib/syscall.c:69
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_syscall
```
**Symbols:**

```
ffffffff818ceaa0-ffffffff818ceb32: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81920880)
Location: lib/syscall.c:69
Inline: False
Direct callers:
  - fs/proc/base.c:proc_pid_syscall
```
**Symbols:**

```
ffffffff81920880-ffffffff81920912: task_current_syscall (STB_GLOBAL)
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
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffff80001065f600)
Location: lib/syscall.c:62
Inline: False
```
**Symbols:**

```
ffff80001065f600-ffff80001065f69c: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (c08086f8)
Location: lib/syscall.c:62
Inline: False
```
**Symbols:**

```
c08086f8-c0808788: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (c000000000812210)
Location: lib/syscall.c:62
Inline: False
```
**Symbols:**

```
c000000000812210-c0000000008122f4: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffe00048c604)
Location: lib/syscall.c:62
Inline: False
```
**Symbols:**

```
ffffffe00048c604-ffffffe00048c674: task_current_syscall (STB_GLOBAL)
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
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff8154b900)
Location: lib/syscall.c:62
Inline: False
```
**Symbols:**

```
ffffffff8154b900-ffffffff8154b982: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff8153bbe0)
Location: lib/syscall.c:62
Inline: False
```
**Symbols:**

```
ffffffff8153bbe0-ffffffff8153bc62: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81547640)
Location: lib/syscall.c:62
Inline: False
```
**Symbols:**

```
ffffffff81547640-ffffffff815476c2: task_current_syscall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int task_current_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81561490)
Location: lib/syscall.c:62
Inline: False
```
**Symbols:**

```
ffffffff81561490-ffffffff81561512: task_current_syscall (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct syscall_info *info</code>
</li>
<li>
<b>Param removed. </b>
<code>long int *callno</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *args</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int maxargs</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *sp</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *pc</code>
</li>
</ul>
</details>
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
