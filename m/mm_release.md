# Function: <code>mm_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107e480)
Location: kernel/fork.c:862
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8107e480-ffffffff8107e5b6: mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080180)
Location: kernel/fork.c:920
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81080180-ffffffff810802bd: mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084ae0)
Location: kernel/fork.c:1074
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81084ae0-ffffffff81084c1d: mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810819c0)
Location: kernel/fork.c:1121
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff810819c0-ffffffff81081afd: mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088290)
Location: kernel/fork.c:1133
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81088290-ffffffff810883cd: mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108bfe0)
Location: kernel/fork.c:1202
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff8108bfe0-ffffffff8108c11d: mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810938a0)
Location: kernel/fork.c:1258
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff810938a0-ffffffff810939dd: mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097fa0)
Location: kernel/fork.c:1277
Inline: False
Direct callers:
  - kernel/exit.c:do_exit
```
**Symbols:**

```
ffffffff81097fa0-ffffffff810980eb: mm_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109d860)
Location: kernel/fork.c:1292
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff8109d860-ffffffff8109d92c: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a4a20)
Location: kernel/fork.c:1306
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff810a4a20-ffffffff810a4aec: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0130)
Location: kernel/fork.c:1303
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff810a0130-ffffffff810a01fc: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0ef0)
Location: kernel/fork.c:1309
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff810a0ef0-ffffffff810a0fbc: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b21e0)
Location: kernel/fork.c:1388
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff810b21e0-ffffffff810b22ac: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c7f90)
Location: kernel/fork.c:1460
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff810c7f90-ffffffff810c8061: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e5150)
Location: kernel/fork.c:1483
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff810e5150-ffffffff810e5221: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f07f0)
Location: kernel/fork.c:1624
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff810f07f0-ffffffff810f08c4: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f9be0)
Location: kernel/fork.c:1620
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff810f9be0-ffffffff810f9cbc: mm_release (STB_LOCAL)
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
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f23c0)
Location: kernel/fork.c:1292
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffff8000100f23c0-ffff8000100f25d8: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0350568)
Location: kernel/fork.c:1292
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
c0350568-c0350664: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000137e80)
Location: kernel/fork.c:1292
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
c000000000137e80-c000000000138010: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bf07e)
Location: kernel/fork.c:1292
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffe0000bf07e-ffffffe0000bf168: mm_release (STB_LOCAL)
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
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097180)
Location: kernel/fork.c:1292
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff81097180-ffffffff8109724c: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085c00)
Location: kernel/fork.c:1292
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff81085c00-ffffffff81085cca: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097130)
Location: kernel/fork.c:1292
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff81097130-ffffffff810971fc: mm_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mm_release(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e550)
Location: kernel/fork.c:1292
Inline: False
Direct callers:
  - kernel/fork.c:exec_mm_release
  - kernel/fork.c:exit_mm_release
```
**Symbols:**

```
ffffffff8109e550-ffffffff8109e61a: mm_release (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
