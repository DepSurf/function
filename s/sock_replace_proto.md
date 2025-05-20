# Function: <code>sock_replace_proto</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f2684c)
Location: include/net/sock.h:1896
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81f2845f)
Location: include/net/sock.h:1896
Inline: True
```
```
In net/unix/unix_bpf.c (ffffffff81f516d6)
Location: include/net/sock.h:1896
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f8650c)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff81f87fb8)
Location: include/net/sock.h:1887
Inline: True
```
```
In net/unix/unix_bpf.c (ffffffff81fb1056)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff8204db0c)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
```
In net/ipv4/udp_bpf.c (ffffffff8204f6d8)
Location: include/net/sock.h:1863
Inline: True
```
```
In net/unix/unix_bpf.c (ffffffff8207e70e)
Location: include/net/sock.h:1863
Inline: True
Inline callers:
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_stream_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
  - net/unix/unix_bpf.c:unix_dgram_bpf_update_proto
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
