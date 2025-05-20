# Function: <code>futex_cleanup_begin</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114de25)
Location: kernel/futex.c:3802
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
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
In kernel/futex.c (ffffffff8115e665)
Location: kernel/futex.c:3715
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
In kernel/futex.c (ffffffff8115a4d5)
Location: kernel/futex.c:3639
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
In kernel/futex.c (ffffffff8115b855)
Location: kernel/futex.c:3636
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
In kernel/futex.c (ffffffff811808a5)
Location: kernel/futex.c:3867
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
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
In kernel/futex/core.c (ffffffff811b34b5)
Location: kernel/futex/core.c:1050
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_exit_release
  - kernel/futex/core.c:futex_exec_release
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
In kernel/futex/core.c (ffffffff811f4455)
Location: kernel/futex/core.c:1058
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_exit_release
  - kernel/futex/core.c:futex_exec_release
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
In kernel/futex/core.c (ffffffff81208be5)
Location: kernel/futex/core.c:1058
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_exit_release
  - kernel/futex/core.c:futex_exec_release
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
In kernel/futex/core.c (ffffffff8121fa85)
Location: kernel/futex/core.c:1083
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_exit_release
  - kernel/futex/core.c:futex_exec_release
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
void futex_cleanup_begin(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b6c20)
Location: kernel/futex.c:3802
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffff8000101b6c20-ffff8000101b6cc0: futex_cleanup_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void futex_cleanup_begin(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0400258)
Location: kernel/futex.c:3802
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
c0400258-c04002b0: futex_cleanup_begin (STB_LOCAL)
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
In kernel/futex.c (c000000000222074)
Location: kernel/futex.c:3802
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void futex_cleanup_begin(struct task_struct *tsk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013ca5a)
Location: kernel/futex.c:3802
Inline: False
Direct callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
**Symbols:**

```
ffffffe00013ca5a-ffffffe00013cae6: futex_cleanup_begin (STB_LOCAL)
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
In kernel/futex.c (ffffffff81146445)
Location: kernel/futex.c:3802
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
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
In kernel/futex.c (ffffffff81139745)
Location: kernel/futex.c:3802
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
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
In kernel/futex.c (ffffffff811442f5)
Location: kernel/futex.c:3802
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
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
In kernel/futex.c (ffffffff81150e75)
Location: kernel/futex.c:3802
Inline: True
Inline callers:
  - kernel/futex.c:futex_exit_release
  - kernel/futex.c:futex_exec_release
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
