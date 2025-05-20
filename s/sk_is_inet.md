# Function: <code>sk_is_inet</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8b2a5)
Location: include/net/inet_sock.h:268
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e476a5)
Location: include/net/inet_sock.h:268
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea1b15)
Location: include/net/inet_sock.h:273
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
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
In net/core/sock.c (ffffffff81ec4b97)
Location: include/net/sock.h:2768
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81ed738d)
Location: include/net/sock.h:2768
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_complete_tx_timestamp
```
```
In net/core/filter.c (ffffffff81f2b5ad)
Location: include/net/sock.h:2768
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
  - net/core/filter.c:bpf_sk_lookup_assign
```
```
In net/core/skmsg.c (ffffffff81f65d95)
Location: include/net/sock.h:2768
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
```
```
In net/core/sock_map.c (ffffffff81f67e1c)
Location: include/net/sock.h:2768
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_sk_state_allowed
```
```
In net/ipv4/ip_output.c (ffffffff81fc0004)
Location: include/net/sock.h:2768
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:2768
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/sock.h:2768
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/sock.h:2768
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204f541)
Location: include/net/sock.h:2768
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_eat_skb
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/net/sock.h:2768
Inline: True
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
