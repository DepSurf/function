# Function: <code>task_file_seq_next</code>

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
void *task_file_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81216850)
Location: kernel/bpf/task_iter.c:223
Inline: False
```
**Symbols:**

```
ffffffff81216850-ffffffff812168e5: task_file_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *task_file_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81218730)
Location: kernel/bpf/task_iter.c:208
Inline: False
```
**Symbols:**

```
ffffffff81218730-ffffffff81218762: task_file_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *task_file_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8121bee0)
Location: kernel/bpf/task_iter.c:208
Inline: False
```
**Symbols:**

```
ffffffff8121bee0-ffffffff8121bf12: task_file_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *task_file_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81252de0)
Location: kernel/bpf/task_iter.c:208
Inline: False
```
**Symbols:**

```
ffffffff81252de0-ffffffff81252e12: task_file_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *task_file_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8129af70)
Location: kernel/bpf/task_iter.c:208
Inline: False
```
**Symbols:**

```
ffffffff8129af70-ffffffff8129afa9: task_file_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *task_file_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff812f7830)
Location: kernel/bpf/task_iter.c:351
Inline: False
```
**Symbols:**

```
ffffffff812f7830-ffffffff812f7869: task_file_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *task_file_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81325710)
Location: kernel/bpf/task_iter.c:351
Inline: False
```
**Symbols:**

```
ffffffff81325710-ffffffff81325749: task_file_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *task_file_seq_next(struct seq_file *seq, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81348e00)
Location: kernel/bpf/task_iter.c:329
Inline: False
```
**Symbols:**

```
ffffffff81348e00-ffffffff81348e39: task_file_seq_next (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
