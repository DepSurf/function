# Function: <code>task_seccomp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff81281117)
Location: fs/proc/array.c:330
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff812ae1bd)
Location: fs/proc/array.c:348
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff812c3b57)
Location: fs/proc/array.c:343
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff812d0ddf)
Location: fs/proc/array.c:347
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff812f5638)
Location: fs/proc/array.c:344
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff813229c1)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff81339af6)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff81361cd1)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
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
In fs/proc/array.c (ffffffff81379f31)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
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
In fs/proc/array.c (ffffffff813c30e4)
Location: fs/proc/array.c:339
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void task_seccomp(struct seq_file *m, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff813d3ae0)
Location: fs/proc/array.c:340
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff813d3ae0-ffffffff813d3cf8: task_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void task_seccomp(struct seq_file *m, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff813da910)
Location: fs/proc/array.c:340
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff813da910-ffffffff813dab28: task_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void task_seccomp(struct seq_file *m, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff8142c060)
Location: fs/proc/array.c:330
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff8142c060-ffffffff8142c278: task_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void task_seccomp(struct seq_file *m, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff814a5310)
Location: fs/proc/array.c:332
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff814a5310-ffffffff814a5534: task_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void task_seccomp(struct seq_file *m, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff8153a8b0)
Location: fs/proc/array.c:335
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff8153a8b0-ffffffff8153aad4: task_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void task_seccomp(struct seq_file *m, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff81572ba0)
Location: fs/proc/array.c:333
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff81572ba0-ffffffff81572dcc: task_seccomp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void task_seccomp(struct seq_file *m, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/array.c (ffffffff815ab550)
Location: fs/proc/array.c:333
Inline: False
Direct callers:
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff815ab550-ffffffff815ab77c: task_seccomp (STB_LOCAL)
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
In fs/proc/array.c (ffff800010446110)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
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
In fs/proc/array.c (c060b2a0)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
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
In fs/proc/array.c (c00000000055bd4c)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
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
In fs/proc/array.c (ffffffe0002dc122)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
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
In fs/proc/array.c (ffffffff81372511)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
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
In fs/proc/array.c (ffffffff81362fe1)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
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
In fs/proc/array.c (ffffffff8136ffe1)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
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
In fs/proc/array.c (ffffffff81383985)
Location: fs/proc/array.c:340
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
```
</details>
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
