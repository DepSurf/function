# Function: <code>bpf_iter_fini_seq_net</code>

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
void bpf_iter_fini_seq_net(void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813c9f20)
Location: fs/proc/proc_net.c:111
Inline: False
```
**Symbols:**

```
ffffffff813c9f20-ffffffff813c9f5b: bpf_iter_fini_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_iter_fini_seq_net(void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813dbbf0)
Location: fs/proc/proc_net.c:95
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/udp.c:bpf_iter_fini_udp
```
**Symbols:**

```
ffffffff813dbbf0-ffffffff813dbc31: bpf_iter_fini_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_iter_fini_seq_net(void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff813e2b10)
Location: fs/proc/proc_net.c:95
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/udp.c:bpf_iter_fini_udp
```
**Symbols:**

```
ffffffff813e2b10-ffffffff813e2b51: bpf_iter_fini_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_iter_fini_seq_net(void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81434620)
Location: fs/proc/proc_net.c:95
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/udp.c:bpf_iter_fini_udp
```
**Symbols:**

```
ffffffff81434620-ffffffff81434661: bpf_iter_fini_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_iter_fini_seq_net(void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff814ae790)
Location: fs/proc/proc_net.c:108
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/udp.c:bpf_iter_fini_udp
  - net/unix/af_unix.c:bpf_iter_fini_unix
```
**Symbols:**

```
ffffffff814ae790-ffffffff814ae7f5: bpf_iter_fini_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_iter_fini_seq_net(void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff81544df0)
Location: fs/proc/proc_net.c:105
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/udp.c:bpf_iter_fini_udp
  - net/unix/af_unix.c:bpf_iter_fini_unix
```
**Symbols:**

```
ffffffff81544df0-ffffffff81544e55: bpf_iter_fini_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_iter_fini_seq_net(void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8157c9d0)
Location: fs/proc/proc_net.c:105
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/udp.c:bpf_iter_fini_udp
  - net/unix/af_unix.c:bpf_iter_fini_unix
```
**Symbols:**

```
ffffffff8157c9d0-ffffffff8157ca35: bpf_iter_fini_seq_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_iter_fini_seq_net(void *priv_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff815b52f0)
Location: fs/proc/proc_net.c:105
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_fini_tcp
  - net/ipv4/udp.c:bpf_iter_fini_udp
  - net/unix/af_unix.c:bpf_iter_fini_unix
```
**Symbols:**

```
ffffffff815b52f0-ffffffff815b5355: bpf_iter_fini_seq_net (STB_GLOBAL)
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
