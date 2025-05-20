# Function: <code>copy_thread_tls</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102de20)
Location: arch/x86/kernel/process_64.c:155
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8102de20-ffffffff8102e089: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102cd40)
Location: arch/x86/kernel/process_64.c:139
Inline: False
```
**Symbols:**

```
ffffffff8102cd40-ffffffff8102cfbd: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102cc00)
Location: arch/x86/kernel/process_64.c:144
Inline: False
```
**Symbols:**

```
ffffffff8102cc00-ffffffff8102ce60: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102ae00)
Location: arch/x86/kernel/process_64.c:269
Inline: False
```
**Symbols:**

```
ffffffff8102ae00-ffffffff8102b060: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102bb40)
Location: arch/x86/kernel/process_64.c:267
Inline: False
```
**Symbols:**

```
ffffffff8102bb40-ffffffff8102bd8b: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102cb60)
Location: arch/x86/kernel/process_64.c:289
Inline: False
```
**Symbols:**

```
ffffffff8102cb60-ffffffff8102cda2: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102ddb0)
Location: arch/x86/kernel/process_64.c:383
Inline: False
```
**Symbols:**

```
ffffffff8102ddb0-ffffffff8102dff2: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fb30)
Location: arch/x86/kernel/process_64.c:374
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff8102fb30-ffffffff8102fd55: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030490)
Location: arch/x86/kernel/process_64.c:374
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81030490-ffffffff810306b5: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810400a0)
Location: arch/x86/kernel/process.c:125
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810400a0-ffffffff8104027a: copy_thread_tls (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stk_sz, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff800010089258)
Location: arch/arm64/kernel/process.c:363
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffff800010089258-ffff8000100893e4: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int stack_start, long unsigned int stk_sz, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/process.c (c030b318)
Location: arch/arm/kernel/process.c:227
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c030b318-c030b400: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int usp, long unsigned int kthread_arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c0000000000220b0)
Location: arch/powerpc/kernel/process.c:1590
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c0000000000220b0-c000000000022544: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int usp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/process.c (ffffffe0000b5aac)
Location: arch/riscv/kernel/process.c:102
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffe0000b5aac-ffffffe0000b5bb4: copy_thread_tls (STB_GLOBAL)
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
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810305f0)
Location: arch/x86/kernel/process_64.c:374
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810305f0-ffffffff81030815: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81020080)
Location: arch/x86/kernel/process_64.c:374
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81020080-ffffffff810202a5: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030450)
Location: arch/x86/kernel/process_64.c:374
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff81030450-ffffffff81030675: copy_thread_tls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_thread_tls(long unsigned int clone_flags, long unsigned int sp, long unsigned int arg, struct task_struct *p, long unsigned int tls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810312e0)
Location: arch/x86/kernel/process_64.c:374
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff810312e0-ffffffff81031505: copy_thread_tls (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int stack_start</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int stk_sz</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int sp</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int arg</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int stack_start</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int stk_sz</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int sp</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int arg</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int usp</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int kthread_arg</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int sp</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int arg</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int usp</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int sp</code>
</li>
</ul>
</details>
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
