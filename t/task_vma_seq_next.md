# Function: <code>task_vma_seq_next</code>

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
void *task_vma_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8121c220)
Location: kernel/bpf/task_iter.c:458
Inline: False
```
**Symbols:**

```
ffffffff8121c220-ffffffff8121c238: task_vma_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *task_vma_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff812530f0)
Location: kernel/bpf/task_iter.c:458
Inline: False
```
**Symbols:**

```
ffffffff812530f0-ffffffff81253108: task_vma_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *task_vma_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8129b290)
Location: kernel/bpf/task_iter.c:458
Inline: False
```
**Symbols:**

```
ffffffff8129b290-ffffffff8129b2b0: task_vma_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *task_vma_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff812f75d0)
Location: kernel/bpf/task_iter.c:618
Inline: False
```
**Symbols:**

```
ffffffff812f75d0-ffffffff812f75f0: task_vma_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *task_vma_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff813254b0)
Location: kernel/bpf/task_iter.c:618
Inline: False
```
**Symbols:**

```
ffffffff813254b0-ffffffff813254d0: task_vma_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *task_vma_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff813496c0)
Location: kernel/bpf/task_iter.c:596
Inline: False
```
**Symbols:**

```
ffffffff813496c0-ffffffff813496e0: task_vma_seq_next (STB_LOCAL)
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
