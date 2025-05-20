# Function: <code>sk_is_tcp</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4df7b)
Location: net/core/sock_map.c:534
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem
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
In net/core/sock_map.c (ffffffff81a53f6b)
Location: net/core/sock_map.c:533
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_update_common
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
In net/core/sock_map.c (ffffffff81a4fa7b)
Location: net/core/sock_map.c:524
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
  - net/core/sock_map.c:sock_map_link
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
In net/core/sock_map.c (ffffffff81b0874b)
Location: net/core/sock_map.c:524
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
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
In net/core/sock.c (ffffffff81bebfd1)
Location: include/net/sock.h:2743
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81bf9e1e)
Location: include/net/sock.h:2743
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_complete_tx_timestamp
```
```
In net/core/filter.c (ffffffff81c4bc68)
Location: include/net/sock.h:2743
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
```
```
In net/core/sock_map.c (ffffffff81c8e6ec)
Location: include/net/sock.h:2743
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
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
In net/core/sock.c (ffffffff81d989a1)
Location: include/net/sock.h:2789
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81da8ced)
Location: include/net/sock.h:2789
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_complete_tx_timestamp
```
```
In net/core/filter.c (ffffffff81dfbc98)
Location: include/net/sock.h:2789
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
```
```
In net/core/sock_map.c (ffffffff81e49acc)
Location: include/net/sock.h:2789
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
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
In net/core/sock.c (ffffffff81e0816b)
Location: include/net/sock.h:2777
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81e19ded)
Location: include/net/sock.h:2777
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_complete_tx_timestamp
```
```
In net/core/filter.c (ffffffff81e6cb7d)
Location: include/net/sock.h:2777
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
```
```
In net/core/sock_map.c (ffffffff81ea518c)
Location: include/net/sock.h:2777
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
```
In net/ipv4/ip_output.c (ffffffff81efc0c4)
Location: include/net/sock.h:2777
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:2777
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/sock.h:2777
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/sock.h:2777
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f87e21)
Location: include/net/sock.h:2777
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_eat_skb
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/net/sock.h:2777
Inline: True
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
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setup_caps
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_set_timestamping
```
```
In net/core/skbuff.c (ffffffff81ed738d)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:__skb_complete_tx_timestamp
```
```
In net/core/filter.c (ffffffff81f2b5ad)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_assign
```
```
In net/core/sock_map.c (ffffffff81f67e1c)
Location: include/net/sock.h:2775
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
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:2775
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/net/sock.h:2775
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/sock.h:2775
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204f541)
Location: include/net/sock.h:2775
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_eat_skb
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/net/sock.h:2775
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
