# Function: <code>__skb_ext_put</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189d130)
Location: net/core/skbuff.c:5720
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
**Symbols:**

```
ffffffff8189d130-ffffffff8189d1b9: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e79b0)
Location: net/core/skbuff.c:6080
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
**Symbols:**

```
ffffffff818e79b0-ffffffff818e7a35: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81919dd0)
Location: net/core/skbuff.c:6097
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
**Symbols:**

```
ffffffff81919dd0-ffffffff81919e55: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ebf60)
Location: net/core/skbuff.c:6240
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/mptcp/protocol.c:mptcp_v6_destroy
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff819ebf60-ffffffff819ec023: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb770)
Location: net/core/skbuff.c:6377
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff819eb770-ffffffff819eb833: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d1d60)
Location: net/core/skbuff.c:6465
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_reuse_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff819d1d60-ffffffff819d1e23: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a819c0)
Location: net/core/skbuff.c:6541
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_reuse_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff81a819c0-ffffffff81a81aa3: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf61a0)
Location: net/core/skbuff.c:6462
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/gro.c:napi_reuse_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/mptcp/protocol.c:__mptcp_move_skb
```
**Symbols:**

```
ffffffff81bf61a0-ffffffff81bf629e: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da4a80)
Location: net/core/skbuff.c:6663
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/gro.c:napi_reuse_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
**Symbols:**

```
ffffffff81da4a80-ffffffff81da4b7e: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e136f0)
Location: net/core/skbuff.c:6708
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/gro.c:napi_reuse_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
**Symbols:**

```
ffffffff81e136f0-ffffffff81e137ee: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed0720)
Location: net/core/skbuff.c:6855
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:skb_ext_maybe_cow
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/gro.c:napi_reuse_skb
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/fastopen.c:mptcp_fastopen_subflow_synack_set_params
```
**Symbols:**

```
ffffffff81ed0720-ffffffff81ed081e: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb2588)
Location: net/core/skbuff.c:6097
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
**Symbols:**

```
ffff800010bb2588-ffff800010bb2648: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd080c)
Location: net/core/skbuff.c:6097
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_reuse_skb
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
**Symbols:**

```
c0cd080c-c0cd08b8: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8a090)
Location: net/core/skbuff.c:6097
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
**Symbols:**

```
c000000000c8a090-c000000000c8a1b4: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffe000744734)
Location: net/core/skbuff.c:6097
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
**Symbols:**

```
ffffffe000744504-ffffffe00074454a: __skb_ext_put.part.0 (STB_LOCAL)
ffffffe00074454a-ffffffe000744594: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b9dd0)
Location: net/core/skbuff.c:6097
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
**Symbols:**

```
ffffffff818b9dd0-ffffffff818b9e55: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81873d20)
Location: net/core/skbuff.c:6097
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
**Symbols:**

```
ffffffff81873d20-ffffffff81873da5: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190add0)
Location: net/core/skbuff.c:6097
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
**Symbols:**

```
ffffffff8190add0-ffffffff8190ae55: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __skb_ext_put(struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192bed0)
Location: net/core/skbuff.c:6097
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_skb_free_stolen_head
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
**Symbols:**

```
ffffffff8192bed0-ffffffff8192bf55: __skb_ext_put (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
