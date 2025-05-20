# Function: <code>ip_fast_csum_nofold</code>

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
In <code>arm64</code>: Absent ⚠️
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
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In block/t10-pi.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In drivers/net/slip/slhc.c (c000000000aacd04)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/core/skbuff.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/core/datagram.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/core/dev.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/core/utils.c (c000000000cd86c8)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
Inline callers:
  - net/core/utils.c:inet_proto_csum_replace16
  - net/core/utils.c:inet_proto_csum_replace16
```
```
In net/core/filter.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/core/netpoll.c (c000000000cfe4ec)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/lwt_bpf.c (c000000000d11244)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ethernet/eth.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv4/ip_input.c (c000000000d60cf4)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_core
```
```
In net/ipv4/ip_output.c (c000000000d6519c)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_check
```
```
In net/ipv4/tcp_offload.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv4/raw.c (c000000000da8c2c)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv4/af_inet.c (c000000000dc030c)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_gro_receive
```
```
In net/ipv4/igmp.c (c000000000dc6a38)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv4/ping.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/xfrm/xfrm_input.c (c000000000e0e03c)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/mcast.c (c000000000e612c0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
```
```
In net/ipv6/reassembly.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/exthdrs.c (c000000000e6ee78)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86c2c)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_inline
```
```
In net/ipv6/seg6_local.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/ip6_checksum.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/ip6_offload.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/ipv6/tcpv6_offload.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: arch/powerpc/include/asm/checksum.h:121
Inline: True
```
</details>
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
