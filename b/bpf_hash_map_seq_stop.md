# Function: <code>bpf_hash_map_seq_stop</code>

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
void bpf_hash_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81219050)
Location: kernel/bpf/hashtab.c:1820
Inline: False
```
**Symbols:**

```
ffffffff81219050-ffffffff8121906c: bpf_hash_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_hash_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121c920)
Location: kernel/bpf/hashtab.c:1820
Inline: False
```
**Symbols:**

```
ffffffff8121c920-ffffffff8121c93c: bpf_hash_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_hash_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81253820)
Location: kernel/bpf/hashtab.c:2000
Inline: False
```
**Symbols:**

```
ffffffff81253820-ffffffff8125383c: bpf_hash_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_hash_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129c470)
Location: kernel/bpf/hashtab.c:2037
Inline: True
```
**Symbols:**

```
ffffffff8129c470-ffffffff8129c4a0: bpf_hash_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_hash_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f9e00)
Location: kernel/bpf/hashtab.c:2068
Inline: True
```
**Symbols:**

```
ffffffff812f9e00-ffffffff812f9e30: bpf_hash_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_hash_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81328330)
Location: kernel/bpf/hashtab.c:2081
Inline: True
```
**Symbols:**

```
ffffffff81328330-ffffffff81328360: bpf_hash_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_hash_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134ca30)
Location: kernel/bpf/hashtab.c:2103
Inline: True
```
**Symbols:**

```
ffffffff8134ca30-ffffffff8134ca60: bpf_hash_map_seq_stop (STB_LOCAL)
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
