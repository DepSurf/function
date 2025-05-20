# Function: <code>inet_csk_has_ulp</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3d8af)
Location: include/net/inet_connection_sock.h:350
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
```
```
In net/core/sock_map.c (ffffffff81a4f6c3)
Location: include/net/inet_connection_sock.h:350
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4048f)
Location: include/net/inet_connection_sock.h:345
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b04a27)
Location: include/net/inet_connection_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81bc6df4)
Location: include/net/inet_connection_sock.h:343
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8b2b4)
Location: include/net/inet_connection_sock.h:341
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5bf41)
Location: include/net/inet_connection_sock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e476b4)
Location: include/net/inet_connection_sock.h:344
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f26874)
Location: include/net/inet_connection_sock.h:344
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
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
In net/core/skmsg.c (ffffffff81ea1b24)
Location: include/net/inet_connection_sock.h:344
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f8653f)
Location: include/net/inet_connection_sock.h:344
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
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
In net/core/skmsg.c (ffffffff81f65da4)
Location: include/net/inet_connection_sock.h:355
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204db3f)
Location: include/net/inet_connection_sock.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
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
