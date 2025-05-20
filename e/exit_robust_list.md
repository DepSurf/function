# Function: <code>exit_robust_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811029e0)
Location: kernel/futex.c:2980
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff811029e0-ffffffff81102aec: exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81109e90)
Location: kernel/futex.c:3113
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81109e90-ffffffff81109f9c: exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81111680)
Location: kernel/futex.c:3126
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81111680-ffffffff8111178c: exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81112cd0)
Location: kernel/futex.c:3301
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81112cd0-ffffffff81112ddf: exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111e270)
Location: kernel/futex.c:3452
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff8111e270-ffffffff8111e37f: exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8112ab90)
Location: kernel/futex.c:3434
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff8112ab90-ffffffff8112ac9c: exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81136bf0)
Location: kernel/futex.c:3514
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81136bf0-ffffffff81136d10: exit_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81141ee0)
Location: kernel/futex.c:3552
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81141ee0-ffffffff81142002: exit_robust_list (STB_GLOBAL)
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
In kernel/futex.c (ffffffff8114be1d)
Location: kernel/futex.c:3694
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
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115ba60)
Location: kernel/futex.c:3607
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff8115ba60-ffffffff8115bb8e: exit_robust_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811582d0)
Location: kernel/futex.c:3531
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff811582d0-ffffffff811583fe: exit_robust_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81159550)
Location: kernel/futex.c:3528
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff81159550-ffffffff8115967d: exit_robust_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exit_robust_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117e480)
Location: kernel/futex.c:3759
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff8117e480-ffffffff8117e5ad: exit_robust_list (STB_LOCAL)
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
In kernel/futex/core.c (ffffffff811b2eec)
Location: kernel/futex/core.c:765
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
In kernel/futex/core.c (ffffffff811f3ddc)
Location: kernel/futex/core.c:773
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
In kernel/futex/core.c (ffffffff8120856c)
Location: kernel/futex/core.c:773
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
In kernel/futex/core.c (ffffffff8121f3fc)
Location: kernel/futex/core.c:798
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
In kernel/futex.c (ffff8000101b8278)
Location: kernel/futex.c:3694
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
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
In kernel/futex.c (c0402d9c)
Location: kernel/futex.c:3694
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021f0a0)
Location: kernel/futex.c:3694
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
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
In kernel/futex.c (ffffffe00013d46a)
Location: kernel/futex.c:3694
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
```
</details>
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
In kernel/futex.c (ffffffff8114443d)
Location: kernel/futex.c:3694
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
In kernel/futex.c (ffffffff81136c6d)
Location: kernel/futex.c:3694
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
In kernel/futex.c (ffffffff811422ed)
Location: kernel/futex.c:3694
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
In kernel/futex.c (ffffffff8114e35d)
Location: kernel/futex.c:3694
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
