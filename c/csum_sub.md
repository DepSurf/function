# Function: <code>csum_sub</code>

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
In net/core/skbuff.c (ffffffff81706b2e)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_vlan_pop
```
```
In net/core/dev.c (ffffffff81717c84)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/utils.c (ffffffff8172fdf7)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/core/filter.c (ffffffff817323ad)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ethernet/eth.c (ffffffff817400fb)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff8175dc5b)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff8175fb2d)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/tcp_output.c (ffffffff817754ae)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/udp_offload.c (ffffffff8178b546)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
```
```
In net/ipv4/gre_offload.c (ffffffff817a4e3c)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv4/inet_lro.c (ffffffff817abab5)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c64f3)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff817c88d0)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff817e696b)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/reassembly.c (ffffffff817ee79c)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/netfilter.c (ffffffff817fddea)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
```
```
In net/ipv6/ip6_offload.c (ffffffff81800df3)
Location: include/net/checksum.h:69
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
In net/core/utils.c (ffffffff8179a54a)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/core/filter.c (ffffffff8179c8bf)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff817ace41)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff817cb137)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cbdd6)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff817f85fe)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81812f21)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff818335dc)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81854cfa)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff8185cfda)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/netfilter.c (ffffffff8186d844)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/ip6_offload.c (ffffffff8187258f)
Location: include/net/checksum.h:69
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
In net/core/utils.c (ffffffff817c82ea)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/core/filter.c (ffffffff817cbb5f)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff817dc491)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff817fad8c)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fbacd)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff818294b7)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81844431)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff8186506c)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81886a62)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff8188ef36)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/netfilter.c (ffffffff818a0644)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6b7f)
Location: include/net/checksum.h:69
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
In net/core/utils.c (ffffffff817e6c3a)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/core/filter.c (ffffffff817eac3f)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff817fbbdf)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff8181b166)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181beaa)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff8184ac18)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81865c84)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff81888826)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/ipv6/raw.c (ffffffff818acf94)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff818b5434)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/netfilter.c (ffffffff818c6c88)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd645)
Location: include/net/checksum.h:69
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
In net/core/utils.c (ffffffff81861b7a)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/core/filter.c (ffffffff81866e4b)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff818795a1)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff8189a12d)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189ade3)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff818ca8bb)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff818e5db4)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff8190ab6c)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8192f91c)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff819381aa)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/netfilter.c (ffffffff8194a148)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/ip6_offload.c (ffffffff81952437)
Location: include/net/checksum.h:69
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
In net/core/skbuff.c (ffffffff81882416)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/utils.c (ffffffff818ad797)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/core/filter.c (ffffffff818b67e9)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff818caf31)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/ipv4/ip_output.c (ffffffff818ee5db)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef3b4)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff81920495)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8193c7ad)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff81961fc3)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8198858d)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff81990e08)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/netfilter.c (ffffffff819a3125)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
```
```
In net/ipv6/ip6_offload.c (ffffffff819abadc)
Location: include/net/checksum.h:69
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
In net/core/utils.c (ffffffff818d19f7)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/core/filter.c (ffffffff818db9f4)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff818f60cb)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff8190ea90)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff8191bd9c)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191cc18)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff8194f239)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff8196c48e)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv6/ip6_output.c (ffffffff819969ef)
Location: include/net/checksum.h:69
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819bef0f)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff819c753f)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff819e267e)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ec1ae)
Location: include/net/checksum.h:69
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (ffffffff8191ec87)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/core/filter.c (ffffffff81924b10)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff81955731)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81970651)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff8197e096)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197ef78)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff819b3a61)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819d31ec)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff819f4f9c)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a02f38)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a2de0b)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff81a365f0)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51346)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a5b33b)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (ffffffff81950ec7)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/core/filter.c (ffffffff81956f40)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff8198bbd1)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff819a7041)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff819b49b4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b6378)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff819ea791)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a09d5c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2bc4c)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a39b0d)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a64976)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff81a6d110)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87f66)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a91f6b)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (ffffffff81a21bfc)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a2f9f5)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/ethernet/eth.c (ffffffff81a637d1)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81a903a1)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81a9ec15)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa0be5)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff81ad849d)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81afa522)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1de1b)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f2d1)
Location: include/net/checksum.h:59
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b5b9e3)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81b65f77)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/ip6_offload.c (ffffffff81b83423)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8d12b)
Location: include/net/checksum.h:59
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (ffffffff81a21f7c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a322c5)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/ethernet/eth.c (ffffffff81a6b926)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81a9a271)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81aa8b53)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaa055)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff81ae5973)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81b07cc6)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c6e9)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b3dd1e)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b6a227)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81b746e3)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/ip6_offload.c (ffffffff81b92acd)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b9cd90)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (ffffffff81a092ac)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81a19422)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/ethernet/eth.c (ffffffff81a54092)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81a85564)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81a93c6f)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a951e5)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff81ad0c68)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81af34d4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a33d)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b1d9)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b58557)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81b63140)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81c2b)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81b8be80)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (ffffffff81abb777)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81aca1d2)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/ethernet/eth.c (ffffffff81b0cda2)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81b3fc54)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81b4f0b8)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b50645)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff81b8f688)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive_segment
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81bb39e4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde95d)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81bf12fc)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c1f8e7)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81c2abf0)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4dc7b)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81c58160)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (ffffffff81c36057)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81c46d0c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/netfilter/utils.c (ffffffff81ccc487)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81cdca15)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdebe0)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff81d1f4bf)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/xfrm/xfrm_input.c (ffffffff81d757c5)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81d89b19)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81dbc511)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81dc810d)
Location: include/net/checksum.h:65
Inline: True
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
In net/core/utils.c (ffffffff81de96e7)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81dfb24c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/netfilter/utils.c (ffffffff81e8c387)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81e9d475)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9eb00)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff81ee667f)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/xfrm/xfrm_input.c (ffffffff81f41de2)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81f579ce)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81f8d7e5)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81f98e89)
Location: include/net/checksum.h:65
Inline: True
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
In net/core/utils.c (ffffffff81e5aef6)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81e6d05f)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/netfilter/utils.c (ffffffff81eea497)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81efa9b5)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efd2ff)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff81f45ebf)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1673)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7496)
Location: include/net/checksum.h:67
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81fedd1e)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff81ff985d)
Location: include/net/checksum.h:67
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
In net/core/utils.c (ffffffff81f1a2b6)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (ffffffff81f2c8cf)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/netfilter/utils.c (ffffffff81fae247)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81fbe902)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc126f)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff8200bfff)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:__udpv4_gso_segment_csum
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e993)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm6_remove_tunnel_encap
```
```
In net/ipv6/ip6_output.c (ffffffff82084af6)
Location: include/net/checksum.h:67
Inline: True
```
```
In net/ipv6/raw.c (ffffffff820bb92e)
Location: include/net/checksum.h:67
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_push_pending_frames
```
```
In net/ipv6/reassembly.c (ffffffff820c74cd)
Location: include/net/checksum.h:67
Inline: True
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
In net/core/utils.c (ffff800010bf2b10)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/core/filter.c (ffff800010bf8728)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffff800010c36c28)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffff800010c56ac4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffff800010c651e0)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffff800010c65fd4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffff800010ca039c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffff800010cc30f4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffff800010cea8b8)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cf998c)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffff800010d2a7d0)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffff800010d356ec)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/ip6_offload.c (ffff800010d54ae8)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffff800010d5fc78)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (c0d0b328)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/core/filter.c (c0d1235c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (c0d49574)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (c0d6626c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (c0d74de0)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/ip_sockglue.c (c0d75c1c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (c0dad2b4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (c0dce90c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (c0df27d4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/ipv6/ip6_output.c (c0e0129c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/ipv6/raw.c (c0e2e7c8)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (c0e37944)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/ip6_offload.c (c0e550f4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c0e5f7d4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (c000000000cd7904)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
  - net/core/utils.c:inet_proto_csum_replace4
```
```
In net/core/filter.c (c000000000cdf668)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (c000000000d2f1dc)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (c000000000d576c4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (c000000000d695ec)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (c000000000d6a8a0)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (c000000000db3c0c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (c000000000dde7d8)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (c000000000e0e554)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e21898)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (c000000000e5b9cc)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (c000000000e677e0)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/ip6_offload.c (c000000000e8d698)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (c000000000e9aa08)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (ffffffe000774552)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/core/filter.c (ffffffe00077a40a)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffe0007a861a)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffe0007c0ac0)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffe0007cca6a)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd676)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffe0007fca60)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:__skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffe0008184f2)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffe0008384bc)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe00084573a)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffe00086af36)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffe000872a7e)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ip6_frag_queue
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c45e)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffe0008951fe)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (ffffffff818f0e97)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/core/filter.c (ffffffff818f6f10)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff8192ba41)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81946eb1)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff81954824)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff819561e8)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff8198a601)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819a9afc)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb2dc)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d919d)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a04006)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff81a0c7a0)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a275f6)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a315fb)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In drivers/net/vxlan.c (ffffffff81772e3a)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_rcv
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
  - drivers/net/vxlan.c:vxlan_gro_receive
```
```
In net/core/utils.c (ffffffff818aacd7)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/core/filter.c (ffffffff818b0d40)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff818e57f1)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff819009a1)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff8190e314)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190fcd8)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff819440c1)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff819635bc)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/ipv4/ip_tunnel.c (ffffffff81967e5d)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
```
In net/xfrm/xfrm_input.c (ffffffff819880cc)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81995f5d)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819c0dc6)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff819c9560)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff819e43b6)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff819ee7eb)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (ffffffff81941ec7)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/core/filter.c (ffffffff81947f40)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff8197cbd1)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff81998041)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff819beff4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c09b8)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff819f4dd1)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a1439c)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35d5c)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a43c1d)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a6ea86)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff81a77220)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90c65)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/ipv6/ip6_offload.c (ffffffff81a931a6)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81a9d1ab)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
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
In net/core/utils.c (ffffffff819637c7)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/core/filter.c (ffffffff81969850)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_l3_csum_replace
```
```
In net/ethernet/eth.c (ffffffff8199f13f)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_gro_receive
```
```
In net/netfilter/utils.c (ffffffff819bad21)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv4/ip_output.c (ffffffff819c8977)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_append_page
```
```
In net/ipv4/ip_sockglue.c (ffffffff819ca398)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/udp_offload.c (ffffffff819fefb6)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:udp_gro_receive
  - net/ipv4/udp_offload.c:skb_udp_tunnel_segment
```
```
In net/ipv4/gre_offload.c (ffffffff81a1eda4)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv4/gre_offload.c:gre_gro_receive
```
```
In net/xfrm/xfrm_input.c (ffffffff81a416cc)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f8bd)
Location: include/net/checksum.h:65
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a7b0bb)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/ipv6/reassembly.c (ffffffff81a8383e)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f2f3)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/8021q/vlan_core.c (ffffffff81aa93a9)
Location: include/net/checksum.h:65
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_gro_receive
```
</details>
</li>
</ul>

## Differences
