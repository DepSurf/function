# Function: <code>bpf_iter_tcp_realloc_batch</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_tcp_realloc_batch(struct bpf_tcp_iter_state *iter, unsigned int new_batch_sz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b799b0)
Location: net/ipv4/tcp_ipv4.c:2745
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
```
**Symbols:**

```
ffffffff81b799b0-ffffffff81b79a5e: bpf_iter_tcp_realloc_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_tcp_realloc_batch(struct bpf_tcp_iter_state *iter, unsigned int new_batch_sz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d093b0)
Location: net/ipv4/tcp_ipv4.c:2711
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
```
**Symbols:**

```
ffffffff81d093b0-ffffffff81d0946c: bpf_iter_tcp_realloc_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_tcp_realloc_batch(struct bpf_tcp_iter_state *iter, unsigned int new_batch_sz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ece630)
Location: net/ipv4/tcp_ipv4.c:2785
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
```
**Symbols:**

```
ffffffff81ece630-ffffffff81ece6ec: bpf_iter_tcp_realloc_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_iter_tcp_realloc_batch(struct bpf_tcp_iter_state *iter, unsigned int new_batch_sz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2d2d0)
Location: net/ipv4/tcp_ipv4.c:2793
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
```
**Symbols:**

```
ffffffff81f2d2d0-ffffffff81f2d351: bpf_iter_tcp_realloc_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_iter_tcp_realloc_batch(struct bpf_tcp_iter_state *iter, unsigned int new_batch_sz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2170)
Location: net/ipv4/tcp_ipv4.c:2997
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
```
**Symbols:**

```
ffffffff81ff2170-ffffffff81ff21f1: bpf_iter_tcp_realloc_batch (STB_LOCAL)
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
