# Function: <code>bpf_iter_tcp_seq_show</code>

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
int bpf_iter_tcp_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad03c0)
Location: net/ipv4/tcp_ipv4.c:2679
Inline: False
```
**Symbols:**

```
ffffffff81ad03c0-ffffffff81ad0481: bpf_iter_tcp_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_tcp_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abb530)
Location: net/ipv4/tcp_ipv4.c:2697
Inline: False
```
**Symbols:**

```
ffffffff81abb530-ffffffff81abb5f1: bpf_iter_tcp_seq_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_iter_tcp_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:2917
Inline: False
```
**Symbols:**

```
ffffffff81b7a0d0-ffffffff81b7a21a: bpf_iter_tcp_seq_show (STB_LOCAL)
ffffffff81d3b72a-ffffffff81d3b770: bpf_iter_tcp_seq_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_iter_tcp_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:2882
Inline: False
```
**Symbols:**

```
ffffffff81d0a240-ffffffff81d0a3b4: bpf_iter_tcp_seq_show (STB_LOCAL)
ffffffff81f07fab-ffffffff81f07ff1: bpf_iter_tcp_seq_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_iter_tcp_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:2959
Inline: False
```
**Symbols:**

```
ffffffff81ecfac0-ffffffff81ecfc34: bpf_iter_tcp_seq_show (STB_LOCAL)
ffffffff820afa54-ffffffff820afa9a: bpf_iter_tcp_seq_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_iter_tcp_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:2967
Inline: False
```
**Symbols:**

```
ffffffff81f2e790-ffffffff81f2e8e0: bpf_iter_tcp_seq_show (STB_LOCAL)
ffffffff82130dcf-ffffffff82130e07: bpf_iter_tcp_seq_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_iter_tcp_seq_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:3171
Inline: False
```
**Symbols:**

```
ffffffff81ff35f0-ffffffff81ff3740: bpf_iter_tcp_seq_show (STB_LOCAL)
ffffffff822125d9-ffffffff82212611: bpf_iter_tcp_seq_show.cold (STB_LOCAL)
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
