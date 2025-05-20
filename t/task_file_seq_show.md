# Function: <code>task_file_seq_show</code>

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
int task_file_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff812163f0)
Location: kernel/bpf/task_iter.c:277
Inline: False
```
**Symbols:**

```
ffffffff812163f0-ffffffff81216472: task_file_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int task_file_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81218430)
Location: kernel/bpf/task_iter.c:249
Inline: False
```
**Symbols:**

```
ffffffff81218430-ffffffff812184b2: task_file_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int task_file_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8121b880)
Location: kernel/bpf/task_iter.c:249
Inline: False
```
**Symbols:**

```
ffffffff8121b880-ffffffff8121b902: task_file_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int task_file_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81252780)
Location: kernel/bpf/task_iter.c:249
Inline: False
```
**Symbols:**

```
ffffffff81252780-ffffffff81252802: task_file_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int task_file_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff8129a7d0)
Location: kernel/bpf/task_iter.c:249
Inline: False
```
**Symbols:**

```
ffffffff8129a7d0-ffffffff8129a88c: task_file_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int task_file_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff812f6a60)
Location: kernel/bpf/task_iter.c:392
Inline: False
```
**Symbols:**

```
ffffffff812f6a60-ffffffff812f6b1c: task_file_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int task_file_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81324920)
Location: kernel/bpf/task_iter.c:392
Inline: False
```
**Symbols:**

```
ffffffff81324920-ffffffff813249dc: task_file_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int task_file_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/task_iter.c (ffffffff81348790)
Location: kernel/bpf/task_iter.c:370
Inline: False
```
**Symbols:**

```
ffffffff81348790-ffffffff8134884c: task_file_seq_show (STB_LOCAL)
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
