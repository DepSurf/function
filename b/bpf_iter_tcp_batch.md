# Function: <code>bpf_iter_tcp_batch</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_iter_tcp_batch(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:2818
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_start
```
**Symbols:**

```
ffffffff81b7b880-ffffffff81b7bc09: bpf_iter_tcp_batch (STB_LOCAL)
ffffffff81d3b816-ffffffff81d3b82a: bpf_iter_tcp_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_iter_tcp_batch(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:2783
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_start
```
**Symbols:**

```
ffffffff81d0aac0-ffffffff81d0ae77: bpf_iter_tcp_batch (STB_LOCAL)
ffffffff81f08017-ffffffff81f0802c: bpf_iter_tcp_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_iter_tcp_batch(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:2859
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_start
```
**Symbols:**

```
ffffffff81ed0380-ffffffff81ed078d: bpf_iter_tcp_batch (STB_LOCAL)
ffffffff820afac0-ffffffff820afad5: bpf_iter_tcp_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_iter_tcp_batch(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:2867
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_start
```
**Symbols:**

```
ffffffff81f2f030-ffffffff81f2f443: bpf_iter_tcp_batch (STB_LOCAL)
ffffffff82130e20-ffffffff82130e35: bpf_iter_tcp_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_iter_tcp_batch(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:3071
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_next
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_start
```
**Symbols:**

```
ffffffff81ff4580-ffffffff81ff4993: bpf_iter_tcp_batch (STB_LOCAL)
ffffffff8221269b-ffffffff822126b0: bpf_iter_tcp_batch.cold (STB_LOCAL)
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
