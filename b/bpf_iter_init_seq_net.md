# Function: <code>bpf_iter_init_seq_net</code>

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
int bpf_iter_init_seq_net(void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813c9ea0)
Location: fs/proc/proc_net.c:101
Inline: False
```
**Symbols:**

```
ffffffff813c9ea0-ffffffff813c9f11: bpf_iter_init_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_iter_init_seq_net(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813dbb70)
Location: fs/proc/proc_net.c:85
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_init_tcp
  - net/ipv4/udp.c:bpf_iter_init_udp
```
**Symbols:**

```
ffffffff813dbb70-ffffffff813dbbe7: bpf_iter_init_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_init_seq_net(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813e2a90)
Location: fs/proc/proc_net.c:85
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_init_tcp
  - net/ipv4/udp.c:bpf_iter_init_udp
```
**Symbols:**

```
ffffffff813e2a90-ffffffff813e2b07: bpf_iter_init_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_init_seq_net(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff814345a0)
Location: fs/proc/proc_net.c:85
Inline: False
Direct callers:
  - net/ipv4/udp.c:bpf_iter_init_udp
```
**Symbols:**

```
ffffffff814345a0-ffffffff81434617: bpf_iter_init_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_init_seq_net(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff814ae6f0)
Location: fs/proc/proc_net.c:97
Inline: False
Direct callers:
  - net/ipv4/udp.c:bpf_iter_init_udp
```
**Symbols:**

```
ffffffff814ae6f0-ffffffff814ae785: bpf_iter_init_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_init_seq_net(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81544d40)
Location: fs/proc/proc_net.c:94
Inline: False
Direct callers:
  - net/ipv4/udp.c:bpf_iter_init_udp
```
**Symbols:**

```
ffffffff81544d40-ffffffff81544dd5: bpf_iter_init_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_iter_init_seq_net(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8157c920)
Location: fs/proc/proc_net.c:94
Inline: False
```
**Symbols:**

```
ffffffff8157c920-ffffffff8157c9b5: bpf_iter_init_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_iter_init_seq_net(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff815b5240)
Location: fs/proc/proc_net.c:94
Inline: False
```
**Symbols:**

```
ffffffff815b5240-ffffffff815b52d5: bpf_iter_init_seq_net (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_iter_aux_info *aux</code>
</li>
</ul>
</details>
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
