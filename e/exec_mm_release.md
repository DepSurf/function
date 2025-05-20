# Function: <code>exec_mm_release</code>

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
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e690)
Location: kernel/fork.c:1332
Inline: False
```
**Symbols:**

```
ffffffff8109e690-ffffffff8109e6b9: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5d60)
Location: kernel/fork.c:1346
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810a5d60-ffffffff810a5d89: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1740)
Location: kernel/fork.c:1343
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810a1740-ffffffff810a1769: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a24c0)
Location: kernel/fork.c:1349
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810a24c0-ffffffff810a24e9: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b3bc0)
Location: kernel/fork.c:1428
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810b3bc0-ffffffff810b3be9: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c9e60)
Location: kernel/fork.c:1499
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810c9e60-ffffffff810c9e8f: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e74b0)
Location: kernel/fork.c:1522
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810e74b0-ffffffff810e74df: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f2fd0)
Location: kernel/fork.c:1663
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810f2fd0-ffffffff810f2fff: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fc380)
Location: kernel/fork.c:1659
Inline: False
Direct callers:
  - fs/exec.c:exec_mmap
```
**Symbols:**

```
ffffffff810fc380-ffffffff810fc3af: exec_mm_release (STB_GLOBAL)
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
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f3500)
Location: kernel/fork.c:1332
Inline: False
```
**Symbols:**

```
ffff8000100f3500-ffff8000100f353c: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c035198c)
Location: kernel/fork.c:1332
Inline: False
```
**Symbols:**

```
c035198c-c03519bc: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000139000)
Location: kernel/fork.c:1332
Inline: False
```
**Symbols:**

```
c000000000139000-c00000000013904c: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c11b2)
Location: kernel/fork.c:1332
Inline: False
```
**Symbols:**

```
ffffffe0000c11b2-ffffffe0000c11ee: exec_mm_release (STB_GLOBAL)
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
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097fb0)
Location: kernel/fork.c:1332
Inline: False
```
**Symbols:**

```
ffffffff81097fb0-ffffffff81097fd9: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086a10)
Location: kernel/fork.c:1332
Inline: False
```
**Symbols:**

```
ffffffff81086a10-ffffffff81086a39: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097f60)
Location: kernel/fork.c:1332
Inline: False
```
**Symbols:**

```
ffffffff81097f60-ffffffff81097f89: exec_mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void exec_mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109fb60)
Location: kernel/fork.c:1332
Inline: False
```
**Symbols:**

```
ffffffff8109fb60-ffffffff8109fb89: exec_mm_release (STB_GLOBAL)
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
