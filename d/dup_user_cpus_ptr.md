# Function: <code>dup_user_cpus_ptr</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dup_user_cpus_ptr(struct task_struct *dst, struct task_struct *src, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f7a80)
Location: kernel/sched/core.c:2500
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff810f7a80-ffffffff810f7af7: dup_user_cpus_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dup_user_cpus_ptr(struct task_struct *dst, struct task_struct *src, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81113cf0)
Location: kernel/sched/core.c:2599
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff81113cf0-ffffffff81113d83: dup_user_cpus_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dup_user_cpus_ptr(struct task_struct *dst, struct task_struct *src, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113af80)
Location: kernel/sched/core.c:2632
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff8113af80-ffffffff8113b06b: dup_user_cpus_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dup_user_cpus_ptr(struct task_struct *dst, struct task_struct *src, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2808
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff820d51fb-ffffffff820d521e: dup_user_cpus_ptr.cold (STB_LOCAL)
ffffffff8114a270-ffffffff8114a3b6: dup_user_cpus_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dup_user_cpus_ptr(struct task_struct *dst, struct task_struct *src, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2836
Inline: False
Direct callers:
  - kernel/fork.c:dup_task_struct
```
**Symbols:**

```
ffffffff821b015e-ffffffff821b0181: dup_user_cpus_ptr.cold (STB_LOCAL)
ffffffff81155de0-ffffffff81155f26: dup_user_cpus_ptr (STB_GLOBAL)
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
