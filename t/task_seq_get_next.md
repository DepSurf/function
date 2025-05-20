# Function: <code>task_seq_get_next</code>

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
struct task_struct *task_seq_get_next(struct pid_namespace *ns, u32 *tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81216260)
Location: kernel/bpf/task_iter.c:23
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_start
```
**Symbols:**

```
ffffffff81216260-ffffffff812162b8: task_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *task_seq_get_next(struct pid_namespace *ns, u32 *tid, bool skip_if_dup_files);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff812184c0)
Location: kernel/bpf/task_iter.c:24
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_start
```
**Symbols:**

```
ffffffff812184c0-ffffffff81218587: task_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *task_seq_get_next(struct pid_namespace *ns, u32 *tid, bool skip_if_dup_files);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8121b990)
Location: kernel/bpf/task_iter.c:24
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_start
```
**Symbols:**

```
ffffffff8121b990-ffffffff8121ba57: task_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *task_seq_get_next(struct pid_namespace *ns, u32 *tid, bool skip_if_dup_files);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81252890)
Location: kernel/bpf/task_iter.c:24
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_start
```
**Symbols:**

```
ffffffff81252890-ffffffff81252957: task_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *task_seq_get_next(struct pid_namespace *ns, u32 *tid, bool skip_if_dup_files);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8129a940)
Location: kernel/bpf/task_iter.c:25
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_start
```
**Symbols:**

```
ffffffff8129a940-ffffffff8129aa20: task_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *task_seq_get_next(struct bpf_iter_seq_task_common *common, u32 *tid, bool skip_if_dup_files);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff812f7170)
Location: kernel/bpf/task_iter.c:109
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_start
```
**Symbols:**

```
ffffffff812f7170-ffffffff812f72dd: task_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *task_seq_get_next(struct bpf_iter_seq_task_common *common, u32 *tid, bool skip_if_dup_files);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81325040)
Location: kernel/bpf/task_iter.c:109
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_start
```
**Symbols:**

```
ffffffff81325040-ffffffff813251ad: task_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *task_seq_get_next(struct bpf_iter_seq_task_common *common, u32 *tid, bool skip_if_dup_files);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff813489c0)
Location: kernel/bpf/task_iter.c:89
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - kernel/bpf/task_iter.c:task_seq_next
  - kernel/bpf/task_iter.c:task_seq_start
```
**Symbols:**

```
ffffffff813489c0-ffffffff81348c49: task_seq_get_next (STB_LOCAL)
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
<b>Param added. </b>
<code>bool skip_if_dup_files</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_iter_seq_task_common *common</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pid_namespace *ns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
