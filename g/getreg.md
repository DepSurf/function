# Function: <code>getreg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103bf20)
Location: arch/x86/kernel/ptrace.c:454
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
```
**Symbols:**

```
ffffffff8103bf20-ffffffff8103c0ef: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103bd00)
Location: arch/x86/kernel/ptrace.c:421
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8103bd00-ffffffff8103be1b: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103b9d0)
Location: arch/x86/kernel/ptrace.c:421
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8103b9d0-ffffffff8103bae6: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81039a20)
Location: arch/x86/kernel/ptrace.c:422
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff81039a20-ffffffff81039b36: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c420)
Location: arch/x86/kernel/ptrace.c:422
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8103c420-ffffffff8103c532: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d920)
Location: arch/x86/kernel/ptrace.c:422
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8103d920-ffffffff8103da32: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103ef70)
Location: arch/x86/kernel/ptrace.c:423
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
```
**Symbols:**

```
ffffffff8103ef70-ffffffff8103f0bc: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041560)
Location: arch/x86/kernel/ptrace.c:397
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff81041560-ffffffff810416c1: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041ce0)
Location: arch/x86/kernel/ptrace.c:397
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff81041ce0-ffffffff81041e41: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81045050)
Location: arch/x86/kernel/ptrace.c:409
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff81045050-ffffffff810451b5: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81044ab0)
Location: arch/x86/kernel/ptrace.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff81044ab0-ffffffff81044c15: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81046a90)
Location: arch/x86/kernel/ptrace.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff81046a90-ffffffff81046bec: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104ce80)
Location: arch/x86/kernel/ptrace.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff8104ce80-ffffffff8104cfdc: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81058010)
Location: arch/x86/kernel/ptrace.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff81058010-ffffffff810581ac: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810658a0)
Location: arch/x86/kernel/ptrace.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff810658a0-ffffffff81065a11: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81067040)
Location: arch/x86/kernel/ptrace.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff81067040-ffffffff810671b9: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106e4c0)
Location: arch/x86/kernel/ptrace.c:407
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff8106e4c0-ffffffff8106e639: getreg (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041e60)
Location: arch/x86/kernel/ptrace.c:397
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff81041e60-ffffffff81041fc1: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81031520)
Location: arch/x86/kernel/ptrace.c:397
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff81031520-ffffffff81031681: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041ca0)
Location: arch/x86/kernel/ptrace.c:397
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff81041ca0-ffffffff81041e01: getreg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int getreg(struct task_struct *task, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81043080)
Location: arch/x86/kernel/ptrace.c:397
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:compat_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:genregs_get
```
**Symbols:**

```
ffffffff81043080-ffffffff810431e1: getreg (STB_LOCAL)
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
