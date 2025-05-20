# Function: <code>unix_get_first</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *unix_get_first(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d7cd10)
Location: net/unix/af_unix.c:3242
Inline: False
Direct callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_seq_start
```
**Symbols:**

```
ffffffff81d7cd10-ffffffff81d7ce71: unix_get_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *unix_get_first(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f49e40)
Location: net/unix/af_unix.c:3277
Inline: False
Direct callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_seq_start
```
**Symbols:**

```
ffffffff81f49e40-ffffffff81f49f2e: unix_get_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *unix_get_first(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81fa9ae0)
Location: net/unix/af_unix.c:3197
Inline: False
Direct callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_seq_start
```
**Symbols:**

```
ffffffff81fa9ae0-ffffffff81fa9bce: unix_get_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *unix_get_first(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff82076f60)
Location: net/unix/af_unix.c:3214
Inline: False
Direct callers:
  - net/unix/af_unix.c:bpf_iter_unix_batch
  - net/unix/af_unix.c:unix_seq_next
  - net/unix/af_unix.c:unix_seq_start
```
**Symbols:**

```
ffffffff82076f60-ffffffff8207704e: unix_get_first (STB_LOCAL)
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
