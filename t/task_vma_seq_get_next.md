# Function: <code>task_vma_seq_get_next</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_area_struct *task_vma_seq_get_next(struct bpf_iter_seq_task_vma_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8121bf60)
Location: kernel/bpf/task_iter.c:308
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_next
  - kernel/bpf/task_iter.c:task_vma_seq_start
```
**Symbols:**

```
ffffffff8121bf60-ffffffff8121c211: task_vma_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_area_struct *task_vma_seq_get_next(struct bpf_iter_seq_task_vma_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81252e60)
Location: kernel/bpf/task_iter.c:308
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_next
  - kernel/bpf/task_iter.c:task_vma_seq_start
```
**Symbols:**

```
ffffffff81252e60-ffffffff812530f0: task_vma_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_area_struct *task_vma_seq_get_next(struct bpf_iter_seq_task_vma_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8129aff0)
Location: kernel/bpf/task_iter.c:308
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_next
  - kernel/bpf/task_iter.c:task_vma_seq_start
```
**Symbols:**

```
ffffffff8129aff0-ffffffff8129b28c: task_vma_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_area_struct *task_vma_seq_get_next(struct bpf_iter_seq_task_vma_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff812f7340)
Location: kernel/bpf/task_iter.c:455
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_next
  - kernel/bpf/task_iter.c:task_vma_seq_start
```
**Symbols:**

```
ffffffff812f7340-ffffffff812f75bf: task_vma_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_area_struct *task_vma_seq_get_next(struct bpf_iter_seq_task_vma_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81325210)
Location: kernel/bpf/task_iter.c:455
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_next
  - kernel/bpf/task_iter.c:task_vma_seq_start
```
**Symbols:**

```
ffffffff81325210-ffffffff8132549b: task_vma_seq_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_area_struct *task_vma_seq_get_next(struct bpf_iter_seq_task_vma_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81349420)
Location: kernel/bpf/task_iter.c:433
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:task_vma_seq_next
  - kernel/bpf/task_iter.c:task_vma_seq_start
```
**Symbols:**

```
ffffffff81349420-ffffffff813496ab: task_vma_seq_get_next (STB_LOCAL)
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
