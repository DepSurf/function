# Function: <code>task_file_seq_get_next</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *task_file_seq_get_next(struct bpf_iter_seq_task_file_info *info, struct task_struct **task, struct files_struct **fstruct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81216670)
Location: kernel/bpf/task_iter.c:131
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_next
  - kernel/bpf/task_iter.c:task_file_seq_start
```
**Symbols:**

```
ffffffff81216670-ffffffff81216847: task_file_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *task_file_seq_get_next(struct bpf_iter_seq_task_file_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff812185d0)
Location: kernel/bpf/task_iter.c:138
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_next
  - kernel/bpf/task_iter.c:task_file_seq_start
```
**Symbols:**

```
ffffffff812185d0-ffffffff81218728: task_file_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *task_file_seq_get_next(struct bpf_iter_seq_task_file_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8121bd80)
Location: kernel/bpf/task_iter.c:138
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_next
  - kernel/bpf/task_iter.c:task_file_seq_start
```
**Symbols:**

```
ffffffff8121bd80-ffffffff8121bed3: task_file_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *task_file_seq_get_next(struct bpf_iter_seq_task_file_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81252c80)
Location: kernel/bpf/task_iter.c:138
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_next
  - kernel/bpf/task_iter.c:task_file_seq_start
```
**Symbols:**

```
ffffffff81252c80-ffffffff81252dd3: task_file_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *task_file_seq_get_next(struct bpf_iter_seq_task_file_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8129ae10)
Location: kernel/bpf/task_iter.c:138
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_next
  - kernel/bpf/task_iter.c:task_file_seq_start
```
**Symbols:**

```
ffffffff8129ae10-ffffffff8129af6a: task_file_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *task_file_seq_get_next(struct bpf_iter_seq_task_file_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff812f76d0)
Location: kernel/bpf/task_iter.c:279
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_next
  - kernel/bpf/task_iter.c:task_file_seq_start
```
**Symbols:**

```
ffffffff812f76d0-ffffffff812f781e: task_file_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *task_file_seq_get_next(struct bpf_iter_seq_task_file_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff813255b0)
Location: kernel/bpf/task_iter.c:279
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_next
  - kernel/bpf/task_iter.c:task_file_seq_start
```
**Symbols:**

```
ffffffff813255b0-ffffffff813256fe: task_file_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *task_file_seq_get_next(struct bpf_iter_seq_task_file_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81348cb0)
Location: kernel/bpf/task_iter.c:259
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_next
  - kernel/bpf/task_iter.c:task_file_seq_start
```
**Symbols:**

```
ffffffff81348cb0-ffffffff81348dec: task_file_seq_get_next (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct **task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct files_struct **fstruct</code>
</li>
</ul>
</details>
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
