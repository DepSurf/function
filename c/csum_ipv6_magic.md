# Function: <code>csum_ipv6_magic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, short unsigned int proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81817b10)
Location: arch/x86/lib/csum-wrappers_64.c:136
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
**Symbols:**

```
ffffffff81817b10-ffffffff81817b6c: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818915c0)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff818915c0-ffffffff81891622: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818c5ed0)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff818c5ed0-ffffffff818c5f32: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff818fbaa0)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff818fbaa0-ffffffff818fbb02: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff819828f0)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff819828f0-ffffffff81982952: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff819dee20)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/netfilter.c:nf_ip6_checksum_partial
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/netfilter.c:nf_ip6_checksum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff819dee20-ffffffff819dee7f: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a19d50)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81a19d50-ffffffff81a19daf: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a89a70)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81a89a70-ffffffff81a89acf: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ac0d10)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81ac0d10-ffffffff81ac0d6f: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff815fd160)
Location: arch/x86/lib/csum-wrappers_64.c:138
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff815fd160-ffffffff815fd1bf: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81621f50)
Location: arch/x86/lib/csum-wrappers_64.c:78
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81621f50-ffffffff81621faf: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81605860)
Location: arch/x86/lib/csum-wrappers_64.c:78
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81605860-ffffffff816058b5: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81674150)
Location: arch/x86/lib/csum-wrappers_64.c:78
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81674150-ffffffff816741a5: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8178e800)
Location: arch/x86/lib/csum-wrappers_64.c:76
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff8178e800-ffffffff8178e864: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff8204c110)
Location: arch/x86/lib/csum-wrappers_64.c:76
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff8204c110-ffffffff8204c174: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff820caa00)
Location: arch/x86/lib/csum-wrappers_64.c:76
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff820caa00-ffffffff820caa64: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff821a5240)
Location: arch/x86/lib/csum-wrappers_64.c:71
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup_ipv6
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff821a5240-ffffffff821a52a4: csum_ipv6_magic (STB_GLOBAL)
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
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_checksum.c (ffff800010d535b0)
Location: net/ipv6/ip6_checksum.c:8
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffff800010d535b0-ffff800010d53684: csum_ipv6_magic (STB_GLOBAL)
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
In net/core/skbuff.c (c0cd57c4)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_checksum_setup
```
```
In net/core/netpoll.c (c0d295e0)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/netfilter/utils.c (c0d6626c)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
```
```
In net/ipv6/ndisc.c (c0e25014)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_skb
```
```
In net/ipv6/udp.c (c0e283e8)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp_v6_send_skb
  - net/ipv6/udp.c:udp6_unicast_rcv_skb
```
```
In net/ipv6/raw.c (c0e2e6c0)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/icmp.c (c0e30a88)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
```
```
In net/ipv6/mcast.c (c0e33858)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
```
```
In net/ipv6/tcp_ipv6.c (c0e3ba7c)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
```
```
In net/ipv6/udp_offload.c (c0e435d8)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
```
```
In net/ipv6/ip6mr.c (c0e47bf8)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
```
In net/ipv6/ip6_checksum.c (c0e53fe8)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
```
```
In net/ipv6/tcpv6_offload.c (c0e55598)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
Inline callers:
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c0e567a0)
Location: arch/arm/include/asm/checksum.h:148
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
c0000000000a9d50-c0000000000a9d50: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum csum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_checksum.c (ffffffe00088b28a)
Location: net/ipv6/ip6_checksum.c:8
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffe00088b28a-ffffffe00088b3a0: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a5fb60)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81a5fb60-ffffffff81a5fbbf: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81a1cc30)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - drivers/net/vxlan.c:neigh_reduce
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81a1cc30-ffffffff81a1cc8f: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81acbf50)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81acbf50-ffffffff81acbfaf: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__sum16 csum_ipv6_magic(const struct in6_addr *saddr, const struct in6_addr *daddr, __u32 len, __u8 proto, __wsum sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81ad84a0)
Location: arch/x86/lib/csum-wrappers_64.c:137
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_checksum_setup
  - net/core/netpoll.c:netpoll_send_udp
  - net/netfilter/utils.c:nf_checksum_partial
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/netfilter/utils.c:nf_ip6_checksum
  - net/ipv6/ndisc.c:ndisc_send_skb
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/raw.c:rawv6_rcv
  - net/ipv6/icmp.c:icmpv6_rcv
  - net/ipv6/icmp.c:icmpv6_push_pending_frames
  - net/ipv6/mcast.c:igmp6_send
  - net/ipv6/mcast.c:mld_sendpack
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_check
  - net/ipv6/udp_offload.c:udp6_gro_complete
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/udp_offload.c:udp6_gro_receive
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_set_csum
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/ip6_checksum.c:udp6_csum_init
  - net/ipv6/tcpv6_offload.c:tcp6_gro_complete
  - net/ipv6/tcpv6_offload.c:tcp6_gro_receive
```
**Symbols:**

```
ffffffff81ad84a0-ffffffff81ad84ff: csum_ipv6_magic (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>short unsigned int proto</code> ➡️ <code>__u8 proto</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>__wsum csum</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum sum</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>__wsum csum</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum sum</code>
</li>
</ul>
</details>
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
