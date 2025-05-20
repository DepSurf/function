# Function: <code>futex_exit_release</code>

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
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114de20)
Location: kernel/futex.c:3860
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff8114de20-ffffffff8114de8b: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115e660)
Location: kernel/futex.c:3773
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff8115e660-ffffffff8115e726: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115a4d0)
Location: kernel/futex.c:3697
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff8115a4d0-ffffffff8115a596: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115b850)
Location: kernel/futex.c:3694
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff8115b850-ffffffff8115b916: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811808a0)
Location: kernel/futex.c:3925
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff811808a0-ffffffff81180966: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b34b0)
Location: kernel/futex/core.c:1108
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff811b34b0-ffffffff811b3518: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f4450)
Location: kernel/futex/core.c:1116
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff811f4450-ffffffff811f44b8: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81208be0)
Location: kernel/futex/core.c:1116
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff81208be0-ffffffff81208c48: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121fa80)
Location: kernel/futex/core.c:1141
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff8121fa80-ffffffff8121fae8: futex_exit_release (STB_GLOBAL)
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
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101bbfc8)
Location: kernel/futex.c:3860
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffff8000101bbfc8-ffff8000101bc00c: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0404314)
Location: kernel/futex.c:3860
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
c0404314-c0404350: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c000000000222050)
Location: kernel/futex.c:3860
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
c000000000222050-c000000000222120: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe0001400f2)
Location: kernel/futex.c:3860
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffe0001400f2-ffffffe000140140: futex_exit_release (STB_GLOBAL)
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
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81146440)
Location: kernel/futex.c:3860
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff81146440-ffffffff811464ab: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81139740)
Location: kernel/futex.c:3860
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff81139740-ffffffff811397a5: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811442f0)
Location: kernel/futex.c:3860
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff811442f0-ffffffff8114435b: futex_exit_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void futex_exit_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81150e70)
Location: kernel/futex.c:3860
Inline: False
Direct callers:
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff81150e70-ffffffff81150ed2: futex_exit_release (STB_GLOBAL)
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
