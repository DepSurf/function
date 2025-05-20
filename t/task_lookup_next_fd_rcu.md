# Function: <code>task_lookup_next_fd_rcu</code>

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
struct file *task_lookup_next_fd_rcu(struct task_struct *task, unsigned int *ret_fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81345630)
Location: fs/file.c:890
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - fs/proc/fd.c:proc_readfd_common
```
**Symbols:**

```
ffffffff81345630-ffffffff813456bf: task_lookup_next_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *task_lookup_next_fd_rcu(struct task_struct *task, unsigned int *ret_fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134b9d0)
Location: fs/file.c:902
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - fs/proc/fd.c:proc_readfd_common
```
**Symbols:**

```
ffffffff8134b9d0-ffffffff8134ba5f: task_lookup_next_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *task_lookup_next_fd_rcu(struct task_struct *task, unsigned int *ret_fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81399810)
Location: fs/file.c:962
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - fs/proc/fd.c:proc_readfd_common
```
**Symbols:**

```
ffffffff81399810-ffffffff8139989b: task_lookup_next_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *task_lookup_next_fd_rcu(struct task_struct *task, unsigned int *ret_fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141c1d0)
Location: fs/file.c:964
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - fs/proc/fd.c:proc_readfd_common
```
**Symbols:**

```
ffffffff8141c1d0-ffffffff8141c262: task_lookup_next_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *task_lookup_next_fd_rcu(struct task_struct *task, unsigned int *ret_fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a6d60)
Location: fs/file.c:964
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - fs/proc/fd.c:proc_readfd_common
```
**Symbols:**

```
ffffffff814a6d60-ffffffff814a6df2: task_lookup_next_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *task_lookup_next_fd_rcu(struct task_struct *task, unsigned int *ret_fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814dbd40)
Location: fs/file.c:965
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_file_seq_get_next
  - fs/proc/fd.c:proc_readfd_common
```
**Symbols:**

```
ffffffff814dbd40-ffffffff814dbdd2: task_lookup_next_fd_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
