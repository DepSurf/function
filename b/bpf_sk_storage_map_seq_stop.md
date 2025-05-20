# Function: <code>bpf_sk_storage_map_seq_stop</code>

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
void bpf_sk_storage_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a696c0)
Location: net/core/bpf_sk_storage.c:855
Inline: False
```
**Symbols:**

```
ffffffff81a696c0-ffffffff81a696dc: bpf_sk_storage_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_sk_storage_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a51e60)
Location: net/core/bpf_sk_storage.c:855
Inline: False
```
**Symbols:**

```
ffffffff81a51e60-ffffffff81a51e7c: bpf_sk_storage_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_sk_storage_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81b0aaf0)
Location: net/core/bpf_sk_storage.c:854
Inline: False
```
**Symbols:**

```
ffffffff81b0aaf0-ffffffff81b0ab0c: bpf_sk_storage_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_sk_storage_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81c91260)
Location: net/core/bpf_sk_storage.c:865
Inline: True
```
**Symbols:**

```
ffffffff81c91260-ffffffff81c91290: bpf_sk_storage_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_sk_storage_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81e4c6d0)
Location: net/core/bpf_sk_storage.c:835
Inline: True
```
**Symbols:**

```
ffffffff81e4c6d0-ffffffff81e4c700: bpf_sk_storage_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_sk_storage_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81ea7df0)
Location: net/core/bpf_sk_storage.c:833
Inline: True
```
**Symbols:**

```
ffffffff81ea7df0-ffffffff81ea7e20: bpf_sk_storage_map_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_sk_storage_map_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81f6a8a0)
Location: net/core/bpf_sk_storage.c:834
Inline: True
```
**Symbols:**

```
ffffffff81f6a8a0-ffffffff81f6a8d0: bpf_sk_storage_map_seq_stop (STB_LOCAL)
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
