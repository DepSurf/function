# Function: <code>exit_mm_release</code>

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
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e660)
Location: kernel/fork.c:1326
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8109e660-ffffffff8109e689: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5d30)
Location: kernel/fork.c:1340
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff810a5d30-ffffffff810a5d59: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1710)
Location: kernel/fork.c:1337
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff810a1710-ffffffff810a1739: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a2490)
Location: kernel/fork.c:1343
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff810a2490-ffffffff810a24b9: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3b90)
Location: kernel/fork.c:1422
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff810b3b90-ffffffff810b3bb9: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9e30)
Location: kernel/fork.c:1493
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff810c9e30-ffffffff810c9e5f: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e7470)
Location: kernel/fork.c:1516
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff810e7470-ffffffff810e749f: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f2f90)
Location: kernel/fork.c:1657
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff810f2f90-ffffffff810f2fbf: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fc340)
Location: kernel/fork.c:1653
Inline: False
Direct callers:
  - kernel/exit.c:exit_mm
```
**Symbols:**

```
ffffffff810fc340-ffffffff810fc36f: exit_mm_release (STB_GLOBAL)
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
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f34c0)
Location: kernel/fork.c:1326
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffff8000100f34c0-ffff8000100f34fc: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c035195c)
Location: kernel/fork.c:1326
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
c035195c-c035198c: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000138fb0)
Location: kernel/fork.c:1326
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
c000000000138fb0-c000000000138ffc: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c1176)
Location: kernel/fork.c:1326
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffe0000c1176-ffffffe0000c11b2: exit_mm_release (STB_GLOBAL)
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
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097f80)
Location: kernel/fork.c:1326
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81097f80-ffffffff81097fa9: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810869e0)
Location: kernel/fork.c:1326
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff810869e0-ffffffff81086a09: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097f30)
Location: kernel/fork.c:1326
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81097f30-ffffffff81097f59: exit_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void exit_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109fb30)
Location: kernel/fork.c:1326
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8109fb30-ffffffff8109fb59: exit_mm_release (STB_GLOBAL)
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
