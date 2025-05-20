# Function: <code>futex_exec_release</code>

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
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114ddb0)
Location: kernel/futex.c:3842
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff8114ddb0-ffffffff8114de1b: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115e590)
Location: kernel/futex.c:3755
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff8115e590-ffffffff8115e656: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115a400)
Location: kernel/futex.c:3679
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff8115a400-ffffffff8115a4c6: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115b780)
Location: kernel/futex.c:3676
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff8115b780-ffffffff8115b846: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811807d0)
Location: kernel/futex.c:3907
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff811807d0-ffffffff81180896: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b3440)
Location: kernel/futex/core.c:1090
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff811b3440-ffffffff811b34a8: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f43d0)
Location: kernel/futex/core.c:1098
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff811f43d0-ffffffff811f4438: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81208b60)
Location: kernel/futex/core.c:1098
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff81208b60-ffffffff81208bc8: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121fa00)
Location: kernel/futex/core.c:1123
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff8121fa00-ffffffff8121fa68: futex_exec_release (STB_GLOBAL)
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
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101bbf88)
Location: kernel/futex.c:3842
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffff8000101bbf88-ffff8000101bbfc8: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c04042d8)
Location: kernel/futex.c:3842
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
c04042d8-c0404314: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c000000000221f80)
Location: kernel/futex.c:3842
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
c000000000221f80-c000000000222050: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe0001400a6)
Location: kernel/futex.c:3842
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffe0001400a6-ffffffe0001400f2: futex_exec_release (STB_GLOBAL)
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
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811463d0)
Location: kernel/futex.c:3842
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff811463d0-ffffffff8114643b: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811396d0)
Location: kernel/futex.c:3842
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff811396d0-ffffffff81139735: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81144280)
Location: kernel/futex.c:3842
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff81144280-ffffffff811442eb: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void futex_exec_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81150e00)
Location: kernel/futex.c:3842
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
```
**Symbols:**

```
ffffffff81150e00-ffffffff81150e62: futex_exec_release (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
