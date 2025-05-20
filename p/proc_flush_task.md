# Function: <code>proc_flush_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127e750)
Location: fs/proc/base.c:2923
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8127e750-ffffffff8127e8e5: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812ab750)
Location: fs/proc/base.c:3012
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff812ab750-ffffffff812ab8e5: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812c1010)
Location: fs/proc/base.c:3047
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff812c1010-ffffffff812c11a5: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812ce3a0)
Location: fs/proc/base.c:3173
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff812ce3a0-ffffffff812ce56e: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812f2c00)
Location: fs/proc/base.c:3173
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff812f2c00-ffffffff812f2d99: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131fa20)
Location: fs/proc/base.c:3094
Inline: False
```
**Symbols:**

```
ffffffff8131fa20-ffffffff8131fbb9: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81336b80)
Location: fs/proc/base.c:3188
Inline: False
```
**Symbols:**

```
ffffffff81336b80-ffffffff81336d1a: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135ec80)
Location: fs/proc/base.c:3220
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8135ec80-ffffffff8135ee15: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81376ee0)
Location: fs/proc/base.c:3220
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff81376ee0-ffffffff81377075: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff8000104426e0)
Location: fs/proc/base.c:3220
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffff8000104426e0-ffff800010442888: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0607e2c)
Location: fs/proc/base.c:3220
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
c0607e2c-c0607fc8: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000557d90)
Location: fs/proc/base.c:3220
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
c000000000557d90-c000000000557fac: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d929a)
Location: fs/proc/base.c:3220
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffe0002d929a-ffffffe0002d9404: proc_flush_task (STB_GLOBAL)
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
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136f4c0)
Location: fs/proc/base.c:3220
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8136f4c0-ffffffff8136f655: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135ff50)
Location: fs/proc/base.c:3220
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8135ff50-ffffffff813600e5: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136cf90)
Location: fs/proc/base.c:3220
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff8136cf90-ffffffff8136d125: proc_flush_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void proc_flush_task(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813808b0)
Location: fs/proc/base.c:3220
Inline: False
Direct callers:
  - kernel/exit.c:release_task
```
**Symbols:**

```
ffffffff813808b0-ffffffff81380a45: proc_flush_task (STB_GLOBAL)
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
