# Function: <code>futex_exit_recursive</code>

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
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114dd70)
Location: kernel/futex.c:3794
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8114dd70-ffffffff8114ddac: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115e540)
Location: kernel/futex.c:3707
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8115e540-ffffffff8115e582: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115a3b0)
Location: kernel/futex.c:3631
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8115a3b0-ffffffff8115a3f2: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115b730)
Location: kernel/futex.c:3628
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8115b730-ffffffff8115b772: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81180780)
Location: kernel/futex.c:3859
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81180780-ffffffff811807c2: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b33f0)
Location: kernel/futex/core.c:1042
Inline: False
Direct callers:
  - kernel/exit.c:make_task_dead
```
**Symbols:**

```
ffffffff811b33f0-ffffffff811b343e: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f4370)
Location: kernel/futex/core.c:1050
Inline: False
Direct callers:
  - kernel/exit.c:make_task_dead
```
**Symbols:**

```
ffffffff811f4370-ffffffff811f43be: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81208b00)
Location: kernel/futex/core.c:1050
Inline: False
Direct callers:
  - kernel/exit.c:make_task_dead
```
**Symbols:**

```
ffffffff81208b00-ffffffff81208b4e: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121f9a0)
Location: kernel/futex/core.c:1075
Inline: False
Direct callers:
  - kernel/exit.c:make_task_dead
```
**Symbols:**

```
ffffffff8121f9a0-ffffffff8121f9ee: futex_exit_recursive (STB_GLOBAL)
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
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101bbf30)
Location: kernel/futex.c:3794
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffff8000101bbf30-ffff8000101bbf84: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0404298)
Location: kernel/futex.c:3794
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
c0404298-c04042d8: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c000000000221f10)
Location: kernel/futex.c:3794
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
c000000000221f10-c000000000221f80: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00014005c)
Location: kernel/futex.c:3794
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffe00014005c-ffffffe0001400a6: futex_exit_recursive (STB_GLOBAL)
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
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81146390)
Location: kernel/futex.c:3794
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81146390-ffffffff811463cc: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81139690)
Location: kernel/futex.c:3794
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81139690-ffffffff811396cc: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81144240)
Location: kernel/futex.c:3794
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81144240-ffffffff8114427c: futex_exit_recursive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void futex_exit_recursive(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81150dc0)
Location: kernel/futex.c:3794
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81150dc0-ffffffff81150dfc: futex_exit_recursive (STB_GLOBAL)
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
