# Function: <code>dst_mtu</code>

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
In net/ipv4/ip_forward.c (ffffffff8175aace)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8175c3cf)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81760089)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81775925)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_current_mss
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177cc68)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff8178e8af)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff817a943f)
Location: include/net/dst.h:222
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff817b0243)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b152d)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/ip6_output.c (ffffffff817c4dd0)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/route.c (ffffffff817d3136)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff817dc2b6)
Location: include/net/dst.h:222
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817efd0b)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd067)
Location: include/net/dst.h:222
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff817c6e76)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817cb452)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cc31c)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff817e4a03)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eac24)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
  - net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced
```
```
In net/ipv4/icmp.c (ffffffff817fbef6)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81816c7f)
Location: include/net/dst.h:219
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff8181d173)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181fd45)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/ip6_output.c (ffffffff818329c1)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff8184291f)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8184a1fd)
Location: include/net/dst.h:219
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185fce8)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186c997)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff817f6977)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817fb0b2)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fbe85)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81814e53)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181b574)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff8182ce46)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff8184844c)
Location: include/net/dst.h:219
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff8184ea33)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff818515a5)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/ip6_output.c (ffffffff81864449)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81874696)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8187c08d)
Location: include/net/dst.h:219
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81891c48)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189f787)
Location: include/net/dst.h:219
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff81816b31)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8181b478)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181c20d)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81835047)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183bdf1)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff8184e22b)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81869b41)
Location: include/net/dst.h:223
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff818724ec)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8187321c)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_mtu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/ip6_output.c (ffffffff818899ea)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81898a1c)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff818a1a5b)
Location: include/net/dst.h:223
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b814a)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5d36)
Location: include/net/dst.h:223
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff81895cf1)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8189a3a8)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189b163)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff818b44d6)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b985b)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff818cdf51)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff818ea1f0)
Location: include/net/dst.h:225
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f2edc)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f3c2c)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_mtu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/ip6_output.c (ffffffff81909fe2)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff8191a4be)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819243d1)
Location: include/net/dst.h:225
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193afca)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff819490c5)
Location: include/net/dst.h:225
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff818e9fae)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818ee87d)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff818ef685)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81909aec)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81910107)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff8192465d)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff819408f0)
Location: include/net/dst.h:208
Inline: True
```
```
In net/ipv4/xfrm4_output.c (ffffffff8194980a)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194ac20)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/ip6_output.c (ffffffff81961350)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81972b53)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff8197c853)
Location: include/net/dst.h:208
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993a4a)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a215c)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff819173d0)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8191c015)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191d241)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81937d98)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193e587)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff81953275)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff8197079d)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b4ca)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197ed0f)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/ip6_output.c (ffffffff81995cf6)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff819a84f3)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b27f8)
Location: include/net/dst.h:208
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca15e)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d8dbc)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff8197930d)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8197e33a)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197f414)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff819994f7)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a29db)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff819b7dc2)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff819d9ff4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e49eb)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e7c41)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/ip6_output.c (ffffffff81a01959)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81a148e1)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a20f65)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38d85)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a47631)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff819afca8)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819b4cea)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b5954)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff819cfed7)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d95c0)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff819eeac2)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81a10ee4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1ba0b)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1ec3f)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/ip6_output.c (ffffffff81a3851b)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81a4b4d1)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a579d5)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6f8f5)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e1b1)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff81a99b4d)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9eeda)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a9ff02)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81abcf35)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac648c)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff81adc84f)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81b02730)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f18f)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f01c)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e3ae)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81b3f9d1)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4fc1b)
Location: include/net/dst.h:196
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b697dd)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b78e79)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/ipv4/ip_forward.c (ffffffff81aa3a9d)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa8e1a)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aaa79b)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81ac8697)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad37b0)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff81ae9563)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06b6f)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81b10af7)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1d47f)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d8dc)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b3cdfe)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81b4e4b1)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b5ecaa)
Location: include/net/dst.h:196
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78247)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87df9)
Location: include/net/dst.h:196
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/ipv4/ip_forward.c (ffffffff81a8eb8b)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a94129)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a95d4a)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81ab33bf)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe83f)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff81ad4c44)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81afe6f1)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0bddb)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b928)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a32b)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81b3e5a5)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81b4d4ec)
Location: include/net/dst.h:199
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67184)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76ab9)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81b4f592)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b511aa)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81b701f3)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7c36f)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff81b9393c)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81bbff06)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bced97)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
```
```
In net/xfrm/xfrm_output.c (ffffffff81be01b4)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81beff06)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81c056e2)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81c14805)
Location: include/net/dst.h:199
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2ed7d)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c41520)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81cdcf2d)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cddf47)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81cff791)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c29b)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff81d24765)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81d548d8)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d64d67)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
```
```
In net/xfrm/xfrm_output.c (ffffffff81d770c6)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81d87fc3)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81d9fcd2)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db014f)
Location: include/net/dst.h:200
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc165)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfcbc)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81e9d99d)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
```
```
In net/ipv4/ip_sockglue.c (ffffffff81ea1841)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81ec4831)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed1cdb)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff81eebf45)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81f1eaf0)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2fc07)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43946)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81f55d5f)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81f6eea2)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f81d4c)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d277)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb1fdc)
Location: include/net/dst.h:200
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81efc110)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81f00678)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81f231a1)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f309b0)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff81f4bd3b)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff81f7e5f0)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f90697)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3124)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5737)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81fcefb2)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe1af8)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffdd49)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff820126f6)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/ipv4/ip_output.c (ffffffff81fc0070)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc44c4)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81fe7613)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff68c0)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff82011e4b)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff82044ca4)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205e3fa)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff820707a4)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff82082df8)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff8209c812)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820afa18)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ccbd6)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e18c4)
Location: include/net/dst.h:214
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/ipv4/ip_forward.c (ffff800010c60354)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c65474)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffff800010c66894)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffff800010c8259c)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8cba4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffff800010ca4c98)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (0)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7ca4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdb058)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/ip6_output.c (ffff800010cf8ab4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffff800010d11a34)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffff800010d1cc24)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d382d4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffff800010d495c0)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (c0d6fc90)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c0d750a8)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (c0d763a8)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv4/tcp_output.c (c0d91c10)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (c0d9ccc8)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (c0db0dd4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (c0dd7258)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (c0de1784)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (c0de4e98)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/ip6_output.c (c0e001d8)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (c0e14e60)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (c0e21904)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c0e3b5d4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (c0e4a9c0)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (c000000000d633e0)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d69a04)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (c000000000d6b020)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (c000000000d8e0fc)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9ba6c)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (c000000000db8094)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (c000000000de8850)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (c000000000df7d14)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (c000000000e00028)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/ip6_output.c (c000000000e21c80)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (c000000000e3b550)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4afb0)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6ba44)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (c000000000e7ebf0)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffe0007c85ea)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffe0007ccc74)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd98e)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e48ca)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ebfa0)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffe0007fff04)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffe00081ed4a)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffe0008282ba)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082cb32)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/ip6_output.c (ffffffe0008447e0)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffe000856418)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe00086029c)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008754ce)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882a64)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff8194fb18)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81954b5a)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff819557c4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff8196fd47)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81979430)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff8198e862)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff819b0874)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb09b)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff819be2cf)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/ip6_output.c (ffffffff819d7bab)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff819eab61)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819f7065)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ef85)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1d841)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In drivers/net/vxlan.c (ffffffff81772145)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_xmit_one
```
```
In net/ipv4/ip_forward.c (ffffffff81909608)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8190e64a)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190f2b4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff81929817)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81932ef0)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff81948322)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ip_tunnel.c (ffffffff81966c47)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
```
```
In net/ipv4/ipmr.c (ffffffff8196cea4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977e8b)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197b0bf)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/ip6_output.c (ffffffff8199496b)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff819a7921)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff819b3e25)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbd45)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da601)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff819ba2e8)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819bf32a)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff819bff94)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff819da517)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e3c00)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff819f9102)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81a1b114)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25b1b)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a28d4f)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/ip6_output.c (ffffffff81a4262b)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81a555e1)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a61ae5)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a79a05)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a882c1)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv4/ip_forward.c (ffffffff819c3bd8)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819c8caa)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
  - net/ipv4/ip_output.c:ip_setup_cork
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c996d)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_getsockopt
```
```
In net/ipv4/tcp_output.c (ffffffff819e4197)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_current_mss
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819edd20)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/icmp.c (ffffffff81a02fd5)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv4/ipmr.c (ffffffff81a25ff4)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a30fbb)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3435c)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/ip6_output.c (ffffffff81a4e2bb)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_xmit
```
```
In net/ipv6/route.c (ffffffff81a615e1)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:ip6_default_advmss
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81a6dfaa)
Location: include/net/dst.h:197
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a861f8)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a94f11)
Location: include/net/dst.h:197
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
</details>
</li>
</ul>

## Differences
