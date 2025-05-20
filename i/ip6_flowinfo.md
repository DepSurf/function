# Function: <code>ip6_flowinfo</code>

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
In net/ipv4/ping.c (0)
Location: include/net/ipv6.h:805
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff817c29b3)
Location: include/net/ipv6.h:805
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (0)
Location: include/net/ipv6.h:805
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f09d3)
Location: include/net/ipv6.h:805
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
```
In net/ipv6/datagram.c (ffffffff817f510e)
Location: include/net/ipv6.h:805
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
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
In net/ipv4/ping.c (ffffffff81810595)
Location: include/net/ipv6.h:837
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff8182fa1a)
Location: include/net/ipv6.h:837
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81846423)
Location: include/net/ipv6.h:837
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f74d)
Location: include/net/ipv6.h:837
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff818641be)
Location: include/net/ipv6.h:837
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/ipv4/ping.c (ffffffff81841a95)
Location: include/net/ipv6.h:842
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff8186149a)
Location: include/net/ipv6.h:842
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81878183)
Location: include/net/ipv6.h:842
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81891692)
Location: include/net/ipv6.h:842
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff8189686e)
Location: include/net/ipv6.h:842
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a4712)
Location: include/net/ipv6.h:842
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv4/ping.c (ffffffff818631df)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81885bda)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff8189d37c)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7cd4)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff818bcdf3)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818cafad)
Location: include/net/ipv6.h:843
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
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
In net/ipv4/ping.c (ffffffff818e330f)
Location: include/net/ipv6.h:884
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81906d8a)
Location: include/net/ipv6.h:884
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff8191ccec)
Location: include/net/ipv6.h:884
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193ab42)
Location: include/net/ipv6.h:884
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff8193ff13)
Location: include/net/ipv6.h:884
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e8f3)
Location: include/net/ipv6.h:884
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
```
```
In net/ipv6/seg6_local.c (ffffffff8194f277)
Location: include/net/ipv6.h:884
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:lookup_nexthop
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
In net/ipv4/ping.c (ffffffff81939caf)
Location: include/net/ipv6.h:883
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff8195dd73)
Location: include/net/ipv6.h:883
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81975426)
Location: include/net/ipv6.h:883
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819941c4)
Location: include/net/ipv6.h:883
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81998d49)
Location: include/net/ipv6.h:883
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a7c18)
Location: include/net/ipv6.h:883
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819a8cfa)
Location: include/net/ipv6.h:883
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/ipv4/ping.c (ffffffff8196993c)
Location: include/net/ipv6.h:882
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff819928b3)
Location: include/net/ipv6.h:882
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff819ab06b)
Location: include/net/ipv6.h:882
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819caae6)
Location: include/net/ipv6.h:882
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff819cf699)
Location: include/net/ipv6.h:882
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de773)
Location: include/net/ipv6.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819df81a)
Location: include/net/ipv6.h:882
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/lwt_bpf.c (ffffffff8194334c)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff819d05ad)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff819fe1d3)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81a1837e)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3972b)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81a3e3f9)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d2ed)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e3cd)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/lwt_bpf.c (ffffffff81978323)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff81a070fd)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81a34dc3)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81a4efde)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a702bb)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81a75069)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83ebd)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8502d)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/lwt_bpf.c (ffffffff81a4ce23)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff81af76fd)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b29c33)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81b4691e)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69ecb)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81b6f2a5)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b794f7)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7ec73)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f003)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/filter.c (ffffffff81a31124)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81a52aea)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff81b045dd)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b38573)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81b5545e)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b789ab)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81b7ddd5)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b8848e)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8dc8d)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b8df93)
Location: include/net/ipv6.h:944
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/filter.c (ffffffff81a18164)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81a382ea)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff81aef5ed)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81b26213)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81b42ece)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66cb5)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81b6c9d9)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81b771be)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7cb5f)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ceb5)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/filter.c (ffffffff81acb874)
Location: include/net/ipv6.h:956
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81aee153)
Location: include/net/ipv6.h:956
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff81bb0b79)
Location: include/net/ipv6.h:956
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81beccd0)
Location: include/net/ipv6.h:956
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81c0861e)
Location: include/net/ipv6.h:956
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e872)
Location: include/net/ipv6.h:956
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81c348e5)
Location: include/net/ipv6.h:956
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81c41c5e)
Location: include/net/ipv6.h:956
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47ccc)
Location: include/net/ipv6.h:956
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81c49515)
Location: include/net/ipv6.h:956
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
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
In net/core/filter.c (ffffffff81c474bd)
Location: include/net/ipv6.h:1010
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81c70f9d)
Location: include/net/ipv6.h:1010
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff81d440ec)
Location: include/net/ipv6.h:1010
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81d851a0)
Location: include/net/ipv6.h:1010
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81da3431)
Location: include/net/ipv6.h:1010
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb4c9)
Location: include/net/ipv6.h:1010
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81dd2245)
Location: include/net/ipv6.h:1010
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81de052a)
Location: include/net/ipv6.h:1010
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de7134)
Location: include/net/ipv6.h:1010
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81de8ccb)
Location: include/net/ipv6.h:1010
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81dec367)
Location: include/net/ipv6.h:1010
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/core/filter.c (ffffffff81dfba1d)
Location: include/net/ipv6.h:1043
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81e2901d)
Location: include/net/ipv6.h:1043
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff81f0d5bb)
Location: include/net/ipv6.h:1043
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81f52be0)
Location: include/net/ipv6.h:1043
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81f72851)
Location: include/net/ipv6.h:1043
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c559)
Location: include/net/ipv6.h:1043
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81fa36c5)
Location: include/net/ipv6.h:1043
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff81fb28ba)
Location: include/net/ipv6.h:1043
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9fc4)
Location: include/net/ipv6.h:1043
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81fbc33b)
Location: include/net/ipv6.h:1043
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbffb7)
Location: include/net/ipv6.h:1043
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/core/filter.c (ffffffff81e6c91d)
Location: include/net/ipv6.h:1040
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81e9e663)
Location: include/net/ipv6.h:1040
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff81f6d21d)
Location: include/net/ipv6.h:1040
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81fb25d3)
Location: include/net/ipv6.h:1040
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81fd2941)
Location: include/net/ipv6.h:1040
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffcfa9)
Location: include/net/ipv6.h:1040
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff82003f63)
Location: include/net/ipv6.h:1040
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff82012fcf)
Location: include/net/ipv6.h:1040
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a6f7)
Location: include/net/ipv6.h:1040
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff8201cc3b)
Location: include/net/ipv6.h:1040
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020f35)
Location: include/net/ipv6.h:1040
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/core/filter.c (ffffffff81f2c1f7)
Location: include/net/ipv6.h:1041
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_neigh
```
```
In net/core/lwt_bpf.c (ffffffff81f60ddc)
Location: include/net/ipv6.h:1041
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff82033971)
Location: include/net/ipv6.h:1041
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff8207fd63)
Location: include/net/ipv6.h:1041
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff8209fed1)
Location: include/net/ipv6.h:1041
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc0b9)
Location: include/net/ipv6.h:1041
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff820d2d23)
Location: include/net/ipv6.h:1041
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/xfrm6_protocol.c (ffffffff820e212f)
Location: include/net/ipv6.h:1041
Inline: True
Inline callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e96b4)
Location: include/net/ipv6.h:1041
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output_core
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff820ebc1b)
Location: include/net/ipv6.h:1041
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
```
In net/ipv6/ioam6_iptunnel.c (ffffffff820f0062)
Location: include/net/ipv6.h:1041
Inline: True
Inline callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
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
In net/core/lwt_bpf.c (ffff800010c1eb70)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffff800010cc0024)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffff800010cf5730)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffff800010d12c80)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38c04)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffff800010d3dab4)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4fc08)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffff800010d510b0)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/lwt_bpf.c (c0d36bd8)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (c0dcc528)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (c0dfc178)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (c0e18a98)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (c0e3afac)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (c0e40cd4)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (c0e50960)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c0e51c2c)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/lwt_bpf.c (c000000000d10d90)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (c000000000ddb3b8)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (c000000000e1b8e8)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (c000000000e3f544)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b5e4)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (c000000000e71f34)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e8749c)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (c000000000e89044)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/lwt_bpf.c (ffffffe000798782)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffe000816ab8)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffe000841142)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffe000859094)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875e30)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffe00087a18a)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe00088832a)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffe000889352)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/lwt_bpf.c (ffffffff81918193)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff819a6e9d)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff819d4453)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff819ee66e)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f94b)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81a146f9)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a2354d)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a246bd)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/lwt_bpf.c (ffffffff818d1f43)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff8196095d)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81991213)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff819ab42e)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc70b)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff819d14b9)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e030d)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff819e147d)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/lwt_bpf.c (ffffffff81969323)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff81a1173d)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81a3eed3)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81a590ee)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a3cb)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81a7f179)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8dfcd)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f13d)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
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
In net/core/lwt_bpf.c (ffffffff8198b703)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_xmit_reroute
```
```
In net/ipv4/ping.c (ffffffff81a1c0ad)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/af_inet6.c (ffffffff81a4a993)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:ipv6_opt_accepted
```
```
In net/ipv6/route.c (ffffffff81a652ee)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86c0b)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/datagram.c (ffffffff81a8ba39)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/datagram.c:ipv6_recv_error
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9ad11)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_output
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bebd)
Location: include/net/ipv6.h:940
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
</details>
</li>
</ul>

## Differences
