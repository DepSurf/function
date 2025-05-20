# Function: <code>collect_syscall</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff814137d5)
Location: lib/syscall.c:6
Inline: True
Inline callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff8145b4e5)
Location: lib/syscall.c:6
Inline: True
Inline callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81479f70)
Location: lib/syscall.c:6
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff81479f70-ffffffff8147a0fb: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81483280)
Location: lib/syscall.c:7
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff81483280-ffffffff814833e5: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff814bf2c0)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff814bf2c0-ffffffff814bf428: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff814f0320)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff814f0320-ffffffff814f048b: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, long int *callno, long unsigned int *args, unsigned int maxargs, long unsigned int *sp, long unsigned int *pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81504240)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff81504240-ffffffff815043ab: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff815323a0)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff815323a0-ffffffff815324d1: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff815531e0)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff815531e0-ffffffff81553311: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff815dc5b0)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff815dc5b0-ffffffff815dc70a: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff815fa230)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff815fa230-ffffffff815fa37f: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff815dce10)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff815dce10-ffffffff815dcf57: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81648770)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff81648770-ffffffff816488b7: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff8175eba0)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff8175eba0-ffffffff8175ed04: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff8188c4c0)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff8188c4c0-ffffffff8188c624: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff818ce930)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff818ce930-ffffffff818cea8c: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81920710)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff81920710-ffffffff8192086c: collect_syscall (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffff80001065f518)
Location: lib/syscall.c:8
Inline: True
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffff80001065f518-ffff80001065f5fc: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/syscall.c (c0808630)
Location: lib/syscall.c:8
Inline: True
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
c0808630-c08086f8: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/syscall.c (c0000000008120a0)
Location: lib/syscall.c:8
Inline: True
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
c0000000008120a0-c00000000081220c: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffe00048c546)
Location: lib/syscall.c:8
Inline: True
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffe00048c546-ffffffe00048c604: collect_syscall (STB_LOCAL)
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
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff8154b7c0)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff8154b7c0-ffffffff8154b8f1: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff8153baa0)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff8153baa0-ffffffff8153bbd1: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81547500)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff81547500-ffffffff81547631: collect_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int collect_syscall(struct task_struct *target, struct syscall_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/syscall.c (ffffffff81561350)
Location: lib/syscall.c:8
Inline: False
Direct callers:
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff81561350-ffffffff81561481: collect_syscall (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
