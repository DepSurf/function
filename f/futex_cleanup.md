# Function: <code>futex_cleanup</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114bda0)
Location: kernel/futex.c:3759
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff8114bda0-ffffffff8114c211: futex_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115e6aa)
Location: kernel/futex.c:3672
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115a51a)
Location: kernel/futex.c:3596
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115b89a)
Location: kernel/futex.c:3593
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811808ea)
Location: kernel/futex.c:3824
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2e80)
Location: kernel/futex/core.c:1007
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_exit_release
  - kernel/futex/core.c:futex_exec_release
```
**Symbols:**

```
ffffffff811b2e80-ffffffff811b3134: futex_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f3d70)
Location: kernel/futex/core.c:1015
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_exit_release
  - kernel/futex/core.c:futex_exec_release
```
**Symbols:**

```
ffffffff811f3d70-ffffffff811f4024: futex_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81208500)
Location: kernel/futex/core.c:1015
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_exit_release
  - kernel/futex/core.c:futex_exec_release
```
**Symbols:**

```
ffffffff81208500-ffffffff812087b4: futex_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121f390)
Location: kernel/futex/core.c:1040
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_exit_release
  - kernel/futex/core.c:futex_exec_release
```
**Symbols:**

```
ffffffff8121f390-ffffffff8121f644: futex_cleanup (STB_LOCAL)
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
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b8200)
Location: kernel/futex.c:3759
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffff8000101b8200-ffff8000101b8834: futex_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0402d2c)
Location: kernel/futex.c:3759
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
c0402d2c-c04031d4: futex_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021f020)
Location: kernel/futex.c:3759
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
c00000000021f020-c00000000021fb3c: futex_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013d402)
Location: kernel/futex.c:3759
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffe00013d402-ffffffe00013d88a: futex_cleanup (STB_LOCAL)
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
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811443c0)
Location: kernel/futex.c:3759
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff811443c0-ffffffff81144831: futex_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81136bf0)
Location: kernel/futex.c:3759
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff81136bf0-ffffffff81137049: futex_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142270)
Location: kernel/futex.c:3759
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff81142270-ffffffff811426e1: futex_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void futex_cleanup(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114e2e0)
Location: kernel/futex.c:3759
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff8114e2e0-ffffffff8114e740: futex_cleanup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
