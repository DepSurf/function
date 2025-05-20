# Function: <code>put_seccomp_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8113b630)
Location: kernel/seccomp.c:479
Inline: False
Direct callers:
  - kernel/fork.c:free_task
  - kernel/seccomp.c:seccomp_get_filter
```
**Symbols:**

```
ffffffff8113b630-ffffffff8113b671: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81143df0)
Location: kernel/seccomp.c:479
Inline: False
Direct callers:
  - kernel/fork.c:free_task
  - kernel/seccomp.c:seccomp_get_filter
```
**Symbols:**

```
ffffffff81143df0-ffffffff81143e3a: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8114dcb0)
Location: kernel/seccomp.c:478
Inline: False
Direct callers:
  - kernel/fork.c:free_task
  - kernel/seccomp.c:seccomp_get_filter
```
**Symbols:**

```
ffffffff8114dcb0-ffffffff8114dcfa: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811502e0)
Location: kernel/seccomp.c:494
Inline: False
Direct callers:
  - kernel/fork.c:free_task
  - kernel/seccomp.c:seccomp_get_filter
```
**Symbols:**

```
ffffffff811502e0-ffffffff8115032a: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8115cb21)
Location: kernel/seccomp.c:511
Inline: True
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8115d170-ffffffff8115d187: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8116bed2)
Location: kernel/seccomp.c:520
Inline: True
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8116c010-ffffffff8116c027: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811798e1)
Location: kernel/seccomp.c:580
Inline: True
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81179a30-ffffffff81179a47: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8118607a)
Location: kernel/seccomp.c:585
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81186810-ffffffff81186827: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81192386)
Location: kernel/seccomp.c:586
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81192790-ffffffff811927a7: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a6f2e)
Location: kernel/seccomp.c:596
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff811a75d0-ffffffff811a75e7: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffff800010209bd4)
Location: kernel/seccomp.c:586
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffff80001020a110-ffff80001020a13c: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c0448788)
Location: kernel/seccomp.c:586
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
c0448fb8-c0448fd8: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c000000000286f24)
Location: kernel/seccomp.c:586
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
c000000000287570-c000000000287588: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffe00016b92c)
Location: kernel/seccomp.c:586
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_attach_filter
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffe00016bf32-ffffffe00016bf92: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8118a9a6)
Location: kernel/seccomp.c:586
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8118adb0-ffffffff8118adc7: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8117dad0)
Location: kernel/seccomp.c:586
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff8117ded0-ffffffff8117dee7: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81188776)
Location: kernel/seccomp.c:586
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff81188b80-ffffffff81188b97: put_seccomp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_seccomp_filter(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811960e4)
Location: kernel/seccomp.c:586
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
Direct callers:
  - kernel/fork.c:free_task
```
**Symbols:**

```
ffffffff811964f0-ffffffff81196507: put_seccomp_filter (STB_GLOBAL)
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
