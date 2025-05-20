# Function: <code>bpf_map_seq_start</code>

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
void *bpf_map_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff81216130)
Location: kernel/bpf/map_iter.c:12
Inline: False
```
**Symbols:**

```
ffffffff81216130-ffffffff8121615e: bpf_map_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *bpf_map_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff81218100)
Location: kernel/bpf/map_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff81218100-ffffffff8121812e: bpf_map_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *bpf_map_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff8121b550)
Location: kernel/bpf/map_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff8121b550-ffffffff8121b57e: bpf_map_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *bpf_map_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff81252450)
Location: kernel/bpf/map_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff81252450-ffffffff8125247e: bpf_map_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *bpf_map_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff8129a240)
Location: kernel/bpf/map_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff8129a240-ffffffff8129a276: bpf_map_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bpf_map_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff812f6200)
Location: kernel/bpf/map_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff812f6200-ffffffff812f6236: bpf_map_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bpf_map_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff813240b0)
Location: kernel/bpf/map_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff813240b0-ffffffff813240e6: bpf_map_seq_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bpf_map_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff81348040)
Location: kernel/bpf/map_iter.c:13
Inline: False
```
**Symbols:**

```
ffffffff81348040-ffffffff81348076: bpf_map_seq_start (STB_LOCAL)
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
