# Function: <code>nf_conntrack_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81751200)
Location: net/netfilter/core.c:382
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/virtio_net.c:start_xmit
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_scrub_packet
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
  - net/ipv4/ipmr.c:ip_mr_input
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv_spkt
  - net/packet/af_packet.c:packet_rcv
```
**Symbols:**

```
ffffffff81751200-ffffffff8175121b: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817bd230)
Location: net/netfilter/core.c:382
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/virtio_net.c:start_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff817bd230-ffffffff817bd24b: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff817ecb40)
Location: net/netfilter/core.c:391
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff817ecb40-ffffffff817ecb5b: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8180d0e0)
Location: net/netfilter/core.c:320
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8180d0e0-ffffffff8180d0fb: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8188c300)
Location: net/netfilter/core.c:547
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8188c300-ffffffff8188c31e: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818dfe10)
Location: net/netfilter/core.c:594
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_local_deliver_finish
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff818dfe10-ffffffff818dfe32: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190c980)
Location: net/netfilter/core.c:594
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8190c980-ffffffff8190c9a2: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8196e4c0)
Location: net/netfilter/core.c:573
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff8196e4c0-ffffffff8196e4e2: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a4f00)
Location: net/netfilter/core.c:573
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff819a4f00-ffffffff819a4f22: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8df20)
Location: net/netfilter/core.c:593
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81a8df20-ffffffff81a8df42: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a97f30)
Location: net/netfilter/core.c:670
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81a97f30-ffffffff81a97f57: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a83280)
Location: net/netfilter/core.c:670
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_reuse_skb
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81a83280-ffffffff81a832a7: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81b3cd40)
Location: net/netfilter/core.c:671
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/dev.c:napi_reuse_skb
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81b3cd40-ffffffff81b3cd67: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81cc91f0)
Location: net/netfilter/core.c:699
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/gro.c:napi_reuse_skb
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:nf_conntrack_put
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81cc91f0-ffffffff81cc922f: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81e88d90)
Location: net/netfilter/core.c:696
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/gro.c:napi_reuse_skb
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:nf_conntrack_put
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81e88d90-ffffffff81e88dcf: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81ee6d00)
Location: net/netfilter/core.c:708
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/virtio_net.c:start_xmit
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/gro.c:napi_reuse_skb
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:nf_conntrack_put
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81ee6d00-ffffffff81ee6d52: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81faab10)
Location: net/netfilter/core.c:714
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/virtio_net.c:start_xmit
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/gro.c:napi_reuse_skb
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:nf_conntrack_put
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ip_encap
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:udpv6_queue_rcv_one_skb
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/tcp_ipv6.c:nf_conntrack_put
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
  - net/ipv6/seg6_local.c:end_dt_vrf_core
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81faab10-ffffffff81faab62: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c54390)
Location: net/netfilter/core.c:573
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffff800010c54390-ffff800010c543d0: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d640b8)
Location: net/netfilter/core.c:573
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
c0d640b8-c0d640f0: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d53690)
Location: net/netfilter/core.c:573
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
c000000000d53690-c000000000d536e4: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007bea98)
Location: net/netfilter/core.c:573
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/raw.c:raw_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffe0007bea98-ffffffe0007beaca: nf_conntrack_destroy (STB_GLOBAL)
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
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81944d70)
Location: net/netfilter/core.c:573
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81944d70-ffffffff81944d92: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818fe860)
Location: net/netfilter/core.c:573
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff818fe860-ffffffff818fe882: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81995f00)
Location: net/netfilter/core.c:573
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/netfilter/nf_conntrack_core.c:nf_ct_iterate_cleanup
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_update
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
  - net/netfilter/nf_conntrack_core.c:destroy_conntrack
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
  - net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation
  - net/netfilter/nf_conntrack_proto.c:ipv6_getorigdst
  - net/netfilter/nf_conntrack_proto.c:getorigdst
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_inet_error
  - net/netfilter/nf_conntrack_ecache.c:ecache_work_evict_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_done_list
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_done
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff81995f00-ffffffff81995f22: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void nf_conntrack_destroy(struct nf_conntrack *nfct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b9060)
Location: net/netfilter/core.c:573
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_release_head_state
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
  - net/ipv4/ip_output.c:ip_copy_metadata
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/ipv6/ip6_output.c:ip6_copy_metadata
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/raw.c:raw6_local_deliver
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
**Symbols:**

```
ffffffff819b9060-ffffffff819b9096: nf_conntrack_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
