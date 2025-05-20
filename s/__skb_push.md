# Function: <code>__skb_push</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff815f2590)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/skbuff.c (ffffffff81708ee7)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8171a991)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/ipv4/ip_output.c (ffffffff8175cd02)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/gre_offload.c (ffffffff817a5262)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff817afeb3)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_output.c (ffffffff817c7861)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff817e11b2)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff817fce44)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81800ed1)
Location: include/linux/skbuff.h:1815
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81651dec)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In net/core/skbuff.c (ffffffff817709fa)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:__skb_vlan_pop
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81783f2e)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/sock_reuseport.c (ffffffff817a00ba)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_output.c (ffffffff817c9aed)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp_offload.c (ffffffff817f8934)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81812ba6)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181cde3)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_output.c (ffffffff81834958)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff8184faed)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/icmp.c (ffffffff81856687)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff8186c764)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff818726a1)
Location: include/linux/skbuff.h:1916
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8119765e)
Location: include/linux/skbuff.h:1931
Inline: True
```
```
In net/core/skbuff.c (ffffffff817a024b)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817b153e)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff817cb7ea)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff817cea8a)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/ipv4/ip_output.c (ffffffff817f9a6e)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp_offload.c (ffffffff81829819)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff818440bb)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e6b3)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_output.c (ffffffff818663ee)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff81881a0d)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/icmp.c (ffffffff81888477)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff8189f574)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6ca1)
Location: include/linux/skbuff.h:1931
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8119f2f8)
Location: include/linux/skbuff.h:1970
Inline: True
```
```
In net/core/skbuff.c (ffffffff817bf0f6)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff817d19fc)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:netif_receive_skb_internal
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff817eafd1)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff817edf26)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/bpf/test_run.c (ffffffff8180ca0e)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81819e9d)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp_offload.c (ffffffff8184a848)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81865a1a)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff818720fc)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_output.c (ffffffff8188a85d)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff818a7b25)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/icmp.c (ffffffff818aeb4b)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff818c5a9c)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd6cd)
Location: include/linux/skbuff.h:1970
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811b24e0)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff81838a16)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8184bc4f)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:do_xdp_generic
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff81866645)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff8186a16f)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/bpf/test_run.c (ffffffff8188b9f3)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff818984d8)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp_offload.c (ffffffff818ca4ca)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff818e5b6e)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2adc)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_output.c (ffffffff8190ba62)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff8192a5d5)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/icmp.c (ffffffff8193180b)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948dac)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff819524bf)
Location: include/linux/skbuff.h:2057
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d1b69)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff81883118)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81895fd9)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff818b49f6)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff818b9e78)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/timestamping.c (ffffffff818c6dd9)
Location: include/linux/skbuff.h:2068
Inline: True
```
```
In net/bpf/test_run.c (ffffffff818df41d)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff818ec7a7)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/udp_offload.c (ffffffff81920814)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8193c37d)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8194942f)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_output.c (ffffffff819631fc)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/ndisc.c (ffffffff8198283d)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/icmp.c (ffffffff8198a2a4)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1e8f)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff819aba44)
Location: include/linux/skbuff.h:2068
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e188d)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff818a3b6d)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818b7dfa)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff818dc2ec)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff818e0bcc)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/timestamping.c (ffffffff818eff29)
Location: include/linux/skbuff.h:2146
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8190bf2b)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff8191992c)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193f77a)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff8194d12c)
Location: include/linux/skbuff.h:2146
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8194f645)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8196c078)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b0fa)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_output.c (ffffffff819981d3)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (ffffffff819b8eda)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff819bb41c)
Location: include/linux/skbuff.h:2146
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c0b4c)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8aea)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff819e25e6)
Location: include/linux/skbuff.h:2146
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f8976)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff818ee85a)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81903c7d)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff81929283)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff8192f274)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/timestamping.c (ffffffff81941815)
Location: include/linux/skbuff.h:2234
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8196d6f5)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff8197b1ca)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a3b4f)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff819b1917)
Location: include/linux/skbuff.h:2234
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff819b3e7b)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819d2dc8)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e45fc)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4b56)
Location: include/linux/skbuff.h:2234
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a01242)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (ffffffff81a27951)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81a2a047)
Location: include/linux/skbuff.h:2234
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a2f83f)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a4733d)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81a512ad)
Location: include/linux/skbuff.h:2234
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812059a6)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff81920957)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81936a0c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff8195b963)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff819614e4)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/timestamping.c (ffffffff81976725)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/bpf/test_run.c (ffffffff819a4160)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff819b1b3a)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819da851)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff819e8677)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff819eabab)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a09937)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b60c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b806)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a37e22)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (ffffffff81a5e3b1)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81a60b67)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a6638f)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7deed)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87ecd)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122cbc5)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff819f3fef)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a0b285)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff81a2ecbb)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff81a34b2f)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/timestamping.c (ffffffff81a4b487)
Location: include/linux/skbuff.h:2271
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81a7eca5)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a9c3ea)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac7a00)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff81ad6603)
Location: include/linux/skbuff.h:2271
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81ad87a9)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81afa0a7)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c6a9)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d699)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b2de27)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ndisc.c (ffffffff81b571a1)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81b59a43)
Location: include/linux/skbuff.h:2271
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5ed87)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b78a3b)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81b83381)
Location: include/linux/skbuff.h:2271
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81235041)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff819f4016)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81a0c4af)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff81a30261)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/sock_reuseport.c (ffffffff81a36e7d)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/timestamping.c (ffffffff81a510a7)
Location: include/linux/skbuff.h:2292
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81a885ef)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81aa624a)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad342e)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff81ae2be3)
Location: include/linux/skbuff.h:2292
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81ae4cdc)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81b0786d)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1a9c9)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2bebb)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c877)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ndisc.c (ffffffff81b65811)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81b680a3)
Location: include/linux/skbuff.h:2292
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b6d507)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b879ab)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92a31)
Location: include/linux/skbuff.h:2292
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81239726)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff819da1d4)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819f26d3)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff81a15c9d)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/sock_reuseport.c (ffffffff81a1df23)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/timestamping.c (ffffffff81a36927)
Location: include/linux/skbuff.h:2308
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81a7184f)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81a913e7)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe4be)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff81acdb03)
Location: include/linux/skbuff.h:2308
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81acfef9)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81af3011)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b08679)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19b29)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b29cdf)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ndisc.c (ffffffff81b53ac1)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81b563b3)
Location: include/linux/skbuff.h:2308
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5b8a0)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b7665b)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81b89)
Location: include/linux/skbuff.h:2308
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126ccc9)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
```
```
In kernel/bpf/cgroup.c (ffffffff81273f43)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff81a8a1df)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81aa45a3)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff81ac6ecd)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/core/sock_reuseport.c (ffffffff81ad19b0)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/timestamping.c (ffffffff81aec677)
Location: include/linux/skbuff.h:2337
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81b2af6e)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81b4c797)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7bfde)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff81b8c4d3)
Location: include/linux/skbuff.h:2337
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81b8e919)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81bb3521)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb589)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdddf9)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81bef8af)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (ffffffff81c1b001)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81c1ca23)
Location: include/linux/skbuff.h:2337
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81c22fb0)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c410eb)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dbd0)
Location: include/linux/skbuff.h:2337
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In kernel/bpf/devmap.c (ffffffff812bb9df)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
```
```
In kernel/bpf/cgroup.c (ffffffff812c2177)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff81bff615)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81c19f30)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81c43b0f)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/sock_reuseport.c (ffffffff81c4f637)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81c54563)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:skb_mac_gso_segment
```
```
In net/core/timestamping.c (ffffffff81c6efc2)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/bpf/test_run.c (ffffffff81cb5314)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81cd9e5a)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0beb7)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff81d1cb43)
Location: include/linux/skbuff.h:2696
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81d20077)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81d46d44)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d61039)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81d74f5c)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_beet_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81d8841a)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ndisc.c (ffffffff81db761a)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81db92f3)
Location: include/linux/skbuff.h:2696
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81dbfe20)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf87c)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee2a0)
Location: include/linux/skbuff.h:2696
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In kernel/bpf/devmap.c (ffffffff8131ed78)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
```
```
In kernel/bpf/cgroup.c (ffffffff81326977)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff81dadfab)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81dcafb0)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81df80bf)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/sock_reuseport.c (ffffffff81e045d2)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81e09cb3)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:skb_mac_gso_segment
```
```
In net/core/timestamping.c (ffffffff81e26d52)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/bpf/test_run.c (ffffffff81e73872)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81e9a5fa)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0dd9)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff81ee3c23)
Location: include/linux/skbuff.h:2593
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81ee7274)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f10594)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2b929)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81f42199)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/ipv6/ip6_output.c (ffffffff81f563da)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ndisc.c (ffffffff81f8730a)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81f89343)
Location: include/linux/skbuff.h:2593
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81f90580)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1b4c)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc2814)
Location: include/linux/skbuff.h:2593
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In kernel/bpf/devmap.c (ffffffff8134eb98)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
```
```
In kernel/bpf/cgroup.c (ffffffff81356cbb)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/virtio_net.c (ffffffff81c50d6e)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In net/core/skbuff.c (ffffffff81e1df71)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81e3bb3a)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81e6a6cf)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/sock_reuseport.c (ffffffff81e76e22)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81e7c478)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/core/gso.c (ffffffff81e7d591)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/core/gso.c:skb_mac_gso_segment
```
```
In net/core/timestamping.c (ffffffff81e9c2f2)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/bpf/test_run.c (ffffffff81ecf515)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81ef8f7a)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f3059a)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff81f43493)
Location: include/linux/skbuff.h:2636
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff81f46b16)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81f70280)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b783)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1981)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5dba)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ndisc.c (ffffffff81fe7644)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81fe8773)
Location: include/linux/skbuff.h:2636
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81ff0de0)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff82012236)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff82023792)
Location: include/linux/skbuff.h:2636
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In kernel/bpf/devmap.c (ffffffff81376095)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
```
```
In kernel/bpf/cgroup.c (ffffffff8137f7eb)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/virtio_net.c (ffffffff81d06db5)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:xmit_skb
```
```
In net/core/skbuff.c (ffffffff81edb67b)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81efa07a)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/filter.c (ffffffff81f2965f)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:neigh_hh_output
```
```
In net/core/sock_reuseport.c (ffffffff81f36de2)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/gro.c (ffffffff81f3c7c8)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
```
```
In net/core/gso.c (ffffffff81f3e511)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/core/gso.c:skb_mac_gso_segment
```
```
In net/core/timestamping.c (ffffffff81f5ea82)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/core/timestamping.c:skb_defer_rx_timestamp
```
```
In net/bpf/test_run.c (ffffffff81f92e65)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff81fbce9a)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:neigh_hh_output
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff649f)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff820093f3)
Location: include/linux/skbuff.h:2643
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8200cc56)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff820369b0)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff82053083)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff8206eca1)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/ipv6/ip6_output.c (ffffffff8208348a)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:neigh_hh_output
```
```
In net/ipv6/ndisc.c (ffffffff820b54a4)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff820b72c3)
Location: include/linux/skbuff.h:2643
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff820be9c0)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e13a6)
Location: include/linux/skbuff.h:2643
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028e940)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffff800010bbb2d0)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffff800010bd514c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffff800010bfcc94)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffff800010c04d48)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/timestamping.c (ffff800010c1cd18)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/bpf/test_run.c (ffff800010c5359c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffff800010c62750)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8dc00)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffff800010c9db10)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv4/udp_offload.c (ffff800010ca0668)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffff800010cc2d0c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd7888)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffff800010cea288)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cf8600)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (ffff800010d233e8)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffff800010d267b0)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/icmp.c (ffff800010d2c2fc)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffff800010d492b8)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffff800010d54a68)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bdb2c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (c0cd7acc)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c0cef524)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (c0d180d0)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (c0d1e22c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/timestamping.c (c0d34be0)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/bpf/test_run.c (c0d62eec)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (c0d71d20)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (c0d9c918)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (c0dab5b8)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv4/udp_offload.c (c0dad9f8)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (c0dce4e4)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (c0de13a0)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (c0df2660)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/ipv6/ip6_output.c (c0dffd18)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (c0e27a38)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (c0e29df8)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/icmp.c (c0e301a8)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (c0e4a67c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (c0e55080)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033b1a0)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (c000000000c9408c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (c000000000cb4510)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (c000000000ce5210)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (c000000000ceef24)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/timestamping.c (c000000000d0dcf0)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/bpf/test_run.c (c000000000d52c64)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (c000000000d65828)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9b4d8)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (c000000000daf46c)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv4/udp_offload.c (c000000000db2e6c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (c000000000ddeb70)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (c000000000df774c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (c000000000e0dd80)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e205dc)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (c000000000e53380)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (c000000000e5649c)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/icmp.c (c000000000e5db98)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e7d8)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (c000000000e8d5e0)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c1ac6)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffe00074a3d4)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffe00075ebec)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffe00077f104)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffe0007839ae)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/timestamping.c (ffffffe000796a8e)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/bpf/test_run.c (ffffffe0007bde70)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffe0007ca062)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee144)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffe0007fac26)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffe0007fcd2c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffe000818176)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffe000827f54)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffe000837ec2)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe000844332)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (ffffffe000864d62)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffe000866f82)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/icmp.c (ffffffe00086c63e)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffe0008827b2)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c3d2)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fdfc6)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff818c0957)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff818d69dc)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff818fb933)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff819014b4)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/bpf/test_run.c (ffffffff81943fd0)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff819519aa)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197a6c1)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff819884e7)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff8198aa1b)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819a96d7)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bac9c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff819cae96)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d74b2)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (ffffffff819fda41)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81a001f7)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a05a1f)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d57d)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81a2755d)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f0d16)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/vxlan.c (ffffffff8176bd9e)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_build_skb
```
```
In net/core/skbuff.c (ffffffff8187a897)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff8189081c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff818b5763)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff818bb2e4)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/bpf/test_run.c (ffffffff818fdac0)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff8190b49a)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934181)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff81941fa7)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff819444db)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81963197)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/udp_tunnel.c (ffffffff81971e35)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/udp_tunnel.c:udp_tunnel_xmit_skb
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977a8c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81987c86)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81994272)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (ffffffff819ba801)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff819bcfb7)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff819c27df)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da33d)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff819e431d)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/ip6_udp_tunnel.c (ffffffff819e59e5)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
  - net/ipv6/ip6_udp_tunnel.c:udp_tunnel6_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fbd96)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff81911957)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff81927a0c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff8194c963)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff819524e4)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/timestamping.c (ffffffff81967725)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/bpf/test_run.c (ffffffff81995160)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199a9b2)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
```
```
In net/ipv4/ip_output.c (ffffffff819bc17a)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e4e91)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff819f2cb7)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff819f51eb)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a13f77)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a2571c)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35916)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a41f32)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (ffffffff81a684c1)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81a6ac77)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a7049f)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a87ffd)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9310d)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8120a972)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/skbuff.c (ffffffff81932ab7)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
```
```
In net/core/dev.c (ffffffff819490dc)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:skb_mac_gso_segment
```
```
In net/core/filter.c (ffffffff8196e323)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:bpf_skb_change_head
```
```
In net/core/sock_reuseport.c (ffffffff81973f3b)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/timestamping.c (ffffffff819899b5)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/bpf/test_run.c (ffffffff819b7ce0)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv4/ip_output.c (ffffffff819c5a8a)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_fraglist_prepare
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ee1f1)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/udp.c (ffffffff819fd1c7)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv4/udp_offload.c (ffffffff819ff3e2)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a1e967)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gso_segment
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30b9e)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41281)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4dbc2)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_prepare
  - net/ipv6/ip6_output.c:ip6_fraglist_init
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/ndisc.c (ffffffff81a74ab1)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
```
```
In net/ipv6/udp.c (ffffffff81a77287)
Location: include/linux/skbuff.h:2248
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81a7cabf)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94c1d)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f2af)
Location: include/linux/skbuff.h:2248
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
</details>
</li>
</ul>

## Differences
