# Function: <code>bpf_prog_seq_start</code>

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
void *bpf_prog_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/prog_iter.c (ffffffff812189d0)
Location: kernel/bpf/prog_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff812189d0-ffffffff812189fe: bpf_prog_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *bpf_prog_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/prog_iter.c (ffffffff8121c2b0)
Location: kernel/bpf/prog_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff8121c2b0-ffffffff8121c2de: bpf_prog_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *bpf_prog_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/prog_iter.c (ffffffff81253180)
Location: kernel/bpf/prog_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff81253180-ffffffff812531ae: bpf_prog_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *bpf_prog_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/prog_iter.c (ffffffff8129b330)
Location: kernel/bpf/prog_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff8129b330-ffffffff8129b366: bpf_prog_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bpf_prog_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/prog_iter.c (ffffffff812f7920)
Location: kernel/bpf/prog_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff812f7920-ffffffff812f7956: bpf_prog_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bpf_prog_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/prog_iter.c (ffffffff81325800)
Location: kernel/bpf/prog_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff81325800-ffffffff81325836: bpf_prog_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bpf_prog_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/prog_iter.c (ffffffff81349d40)
Location: kernel/bpf/prog_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff81349d40-ffffffff81349d76: bpf_prog_seq_start (STB_LOCAL)
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
