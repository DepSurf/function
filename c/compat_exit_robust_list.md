# Function: <code>compat_exit_robust_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex_compat.c (ffffffff81103170)
Location: kernel/futex_compat.c:50
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81103170-ffffffff81103287: compat_exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex_compat.c (ffffffff8110a640)
Location: kernel/futex_compat.c:50
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff8110a640-ffffffff8110a756: compat_exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex_compat.c (ffffffff81111e40)
Location: kernel/futex_compat.c:50
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81111e40-ffffffff81111f56: compat_exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex_compat.c (ffffffff81113470)
Location: kernel/futex_compat.c:50
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81113470-ffffffff8111358e: compat_exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex_compat.c (ffffffff8111ea00)
Location: kernel/futex_compat.c:51
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff8111ea00-ffffffff8111eb1e: compat_exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex_compat.c (ffffffff8112bfc0)
Location: kernel/futex_compat.c:51
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff8112bfc0-ffffffff8112c0de: compat_exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81137870)
Location: kernel/futex.c:3704
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81137870-ffffffff81137992: compat_exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811427f0)
Location: kernel/futex.c:3742
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff811427f0-ffffffff81142919: compat_exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114bf2c)
Location: kernel/futex.c:3994
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115b930)
Location: kernel/futex.c:3907
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff8115b930-ffffffff8115ba5e: compat_exit_robust_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158400)
Location: kernel/futex.c:3833
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff81158400-ffffffff8115852e: compat_exit_robust_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81159680)
Location: kernel/futex.c:3839
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff81159680-ffffffff811597ad: compat_exit_robust_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void compat_exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117e350)
Location: kernel/futex.c:4076
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff8117e350-ffffffff8117e47d: compat_exit_robust_list (STB_LOCAL)
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
In kernel/futex/core.c (ffffffff811b2fdd)
Location: kernel/futex/core.c:859
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
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
In kernel/futex/core.c (ffffffff811f3ecd)
Location: kernel/futex/core.c:867
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
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
In kernel/futex/core.c (ffffffff8120865d)
Location: kernel/futex/core.c:867
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
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
In kernel/futex/core.c (ffffffff8121f4ed)
Location: kernel/futex/core.c:892
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b8290)
Location: kernel/futex.c:3994
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021f0d0)
Location: kernel/futex.c:3994
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114454c)
Location: kernel/futex.c:3994
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81136d7c)
Location: kernel/futex.c:3994
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811423fc)
Location: kernel/futex.c:3994
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114e475)
Location: kernel/futex.c:3994
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
