# Function: <code>from64to32</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/checksum.c (ffff8000106622b8)
Location: lib/checksum.c:180
Inline: True
Inline callers:
  - lib/checksum.c:csum_tcpudp_nofold
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/lib/checksum_wrappers.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In block/t10-pi.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In drivers/net/slip/slhc.c (c000000000aacd20)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/core/skbuff.c (c000000000c912cc)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/datagram.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/core/utils.c (c000000000cd86dc)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/core/netpoll.c (c000000000cfe424)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c000000000d11270)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/netfilter/utils.c (c000000000d577ac)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip_checksum
  - net/netfilter/utils.c:nf_ip_checksum
```
```
In net/ipv4/route.c (c000000000d5f628)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_input.c (c000000000d60d30)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (c000000000d651d0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d348)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_synack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_check
```
```
In net/ipv4/tcp_offload.c (c000000000da6124)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv4/tcp_offload.c:tcp4_gro_complete
  - net/ipv4/tcp_offload.c:tcp4_gro_receive
```
```
In net/ipv4/raw.c (c000000000da8c60)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv4/udp.c (c000000000db1518)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp_set_csum
  - net/ipv4/udp.c:udp4_hwcsum
  - net/ipv4/udp.c:udp4_hwcsum
```
```
In net/ipv4/udp_offload.c (c000000000db2b90)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv4/udp_offload.c:udp4_gro_complete
  - net/ipv4/udp_offload.c:udp4_gro_receive
  - net/ipv4/udp_offload.c:udp4_gro_receive
```
```
In net/ipv4/af_inet.c (c000000000dc032c)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (c000000000dc6a60)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ping.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/xfrm/xfrm_input.c (c000000000e0e06c)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/mcast.c (c000000000e612dc)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/reassembly.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/exthdrs.c (c000000000e6ee9c)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86c44)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/ip6_checksum.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/ip6_offload.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: arch/powerpc/include/asm/checksum.h:52
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/checksum.c (ffffffe00048ebca)
Location: lib/checksum.c:180
Inline: True
Inline callers:
  - lib/checksum.c:csum_tcpudp_nofold
```
</details>
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
