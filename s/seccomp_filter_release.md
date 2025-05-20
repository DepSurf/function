# Function: <code>seccomp_filter_release</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void seccomp_filter_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a4cc0)
Location: kernel/seccomp.c:552
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff811a4cc0-ffffffff811a4d01: seccomp_filter_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void seccomp_filter_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a5920)
Location: kernel/seccomp.c:557
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff811a5920-ffffffff811a5961: seccomp_filter_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void seccomp_filter_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811cf070)
Location: kernel/seccomp.c:560
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff811cf070-ffffffff811cf0b1: seccomp_filter_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void seccomp_filter_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff812031f0)
Location: kernel/seccomp.c:562
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff812031f0-ffffffff81203236: seccomp_filter_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void seccomp_filter_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8124b090)
Location: kernel/seccomp.c:562
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8124b090-ffffffff8124b0d6: seccomp_filter_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void seccomp_filter_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff812623b0)
Location: kernel/seccomp.c:562
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff812623b0-ffffffff812623f6: seccomp_filter_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void seccomp_filter_release(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8127c5f0)
Location: kernel/seccomp.c:569
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8127c5f0-ffffffff8127c636: seccomp_filter_release (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
