# Function: <code>exit_pi_state_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81102670)
Location: kernel/futex.c:787
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81102670-ffffffff8110280f: exit_pi_state_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81109b20)
Location: kernel/futex.c:867
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81109b20-ffffffff81109cc5: exit_pi_state_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81111310)
Location: kernel/futex.c:876
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81111310-ffffffff811114b5: exit_pi_state_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81112980)
Location: kernel/futex.c:884
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81112980-ffffffff81112b0c: exit_pi_state_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111de90)
Location: kernel/futex.c:890
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff8111de90-ffffffff8111e0a8: exit_pi_state_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8112a880)
Location: kernel/futex.c:872
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff8112a880-ffffffff8112aaaa: exit_pi_state_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811369c0)
Location: kernel/futex.c:880
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff811369c0-ffffffff81136bea: exit_pi_state_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:895
Inline: False
Direct callers:
  - kernel/fork.c:mm_release
```
**Symbols:**

```
ffffffff81142abd-ffffffff81142ae3: exit_pi_state_list.cold (STB_LOCAL)
ffffffff81141cc0-ffffffff81141edf: exit_pi_state_list (STB_GLOBAL)
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
In kernel/futex.c (ffffffff8114c03b)
Location: kernel/futex.c:916
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
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115c230)
Location: kernel/futex.c:844
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff8115c230-ffffffff8115c482: exit_pi_state_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158530)
Location: kernel/futex.c:840
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff81158530-ffffffff81158782: exit_pi_state_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811597b0)
Location: kernel/futex.c:839
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff811597b0-ffffffff811599fa: exit_pi_state_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117e6d0)
Location: kernel/futex.c:897
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffff8117e6d0-ffffffff8117e91a: exit_pi_state_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2320)
Location: kernel/futex/core.c:935
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_cleanup
```
**Symbols:**

```
ffffffff811b2320-ffffffff811b251f: exit_pi_state_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f31a0)
Location: kernel/futex/core.c:943
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_cleanup
```
**Symbols:**

```
ffffffff811f31a0-ffffffff811f339f: exit_pi_state_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81207920)
Location: kernel/futex/core.c:943
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_cleanup
```
**Symbols:**

```
ffffffff81207920-ffffffff81207b17: exit_pi_state_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exit_pi_state_list(struct task_struct *curr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121eb30)
Location: kernel/futex/core.c:968
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_cleanup
```
**Symbols:**

```
ffffffff8121eb30-ffffffff8121ed27: exit_pi_state_list (STB_LOCAL)
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
In kernel/futex.c (ffff8000101b82b0)
Location: kernel/futex.c:916
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
In kernel/futex.c (c0402dbc)
Location: kernel/futex.c:916
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
In kernel/futex.c (c00000000021f100)
Location: kernel/futex.c:916
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
In kernel/futex.c (ffffffe00013d582)
Location: kernel/futex.c:916
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
In kernel/futex.c (ffffffff8114465b)
Location: kernel/futex.c:916
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
In kernel/futex.c (ffffffff81136e8b)
Location: kernel/futex.c:916
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
In kernel/futex.c (ffffffff8114250b)
Location: kernel/futex.c:916
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
In kernel/futex.c (ffffffff8114e583)
Location: kernel/futex.c:916
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
