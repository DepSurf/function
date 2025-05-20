# Function: <code>bpf_iter_unix_batch</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_iter_unix_batch(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (0)
Location: net/unix/af_unix.c:3436
Inline: False
Direct callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_next
  - net/unix/af_unix.c:bpf_iter_unix_seq_start
```
**Symbols:**

```
ffffffff81d7dcf0-ffffffff81d7defe: bpf_iter_unix_batch (STB_LOCAL)
ffffffff81f0b95b-ffffffff81f0b96f: bpf_iter_unix_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_iter_unix_batch(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (0)
Location: net/unix/af_unix.c:3470
Inline: False
Direct callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_next
  - net/unix/af_unix.c:bpf_iter_unix_seq_start
```
**Symbols:**

```
ffffffff81f4b0a0-ffffffff81f4b2b6: bpf_iter_unix_batch (STB_LOCAL)
ffffffff820b31a0-ffffffff820b31b5: bpf_iter_unix_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_iter_unix_batch(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (0)
Location: net/unix/af_unix.c:3390
Inline: False
Direct callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_next
  - net/unix/af_unix.c:bpf_iter_unix_seq_start
```
**Symbols:**

```
ffffffff81faae40-ffffffff81fab056: bpf_iter_unix_batch (STB_LOCAL)
ffffffff8213439e-ffffffff821343b3: bpf_iter_unix_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_iter_unix_batch(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (0)
Location: net/unix/af_unix.c:3407
Inline: False
Direct callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_next
  - net/unix/af_unix.c:bpf_iter_unix_seq_start
```
**Symbols:**

```
ffffffff82078230-ffffffff82078446: bpf_iter_unix_batch (STB_LOCAL)
ffffffff82215f67-ffffffff82215f7c: bpf_iter_unix_batch.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
