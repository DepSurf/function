# Function: <code>lwtunnel_output_redirect</code>

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
In net/ipv4/route.c (ffffffff81755bbc)
Location: include/net/lwtunnel.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv6/route.c (ffffffff817d6092)
Location: include/net/lwtunnel.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv4/route.c (ffffffff817c270b)
Location: include/net/lwtunnel.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv6/route.c (ffffffff8184463b)
Location: include/net/lwtunnel.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv4/route.c (ffffffff817eeaf0)
Location: include/net/lwtunnel.h:72
Inline: True
Inline callers:
  - net/ipv4/route.c:set_lwt_redirect
```
```
In net/ipv6/route.c (ffffffff818763b7)
Location: include/net/lwtunnel.h:72
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_mtu
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
In net/ipv4/route.c (ffffffff8180ebb0)
Location: include/net/lwtunnel.h:73
Inline: True
Inline callers:
  - net/ipv4/route.c:set_lwt_redirect
```
```
In net/ipv6/route.c (ffffffff8189bac2)
Location: include/net/lwtunnel.h:73
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_mtu
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
In net/ipv4/route.c (ffffffff8188e170)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:set_lwt_redirect
```
```
In net/ipv6/route.c (ffffffff8191e768)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_mtu
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
In net/ipv4/route.c (ffffffff818e5dfb)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffffffff81977a8c)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff81912d0d)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffffffff819ad67c)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff8197510e)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffffffff81a1a777)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff819abb2e)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffffffff81a513e7)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff81a93de6)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffffffff81b48b18)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff81a9dcf1)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffffffff81b57728)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff81a88c35)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_mtu
```
```
In net/ipv4/ip_forward.c (ffffffff81a8eec0)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a90aa9)
Location: include/net/lwtunnel.h:74
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b9e7)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b67e)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81b4530b)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76bf6)
Location: include/net/lwtunnel.h:74
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
In net/ipv4/route.c (ffffffff81b433a5)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81b49ddc)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4bc3f)
Location: include/net/lwtunnel.h:77
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0380)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1ae4)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/route.c (ffffffff81c0c44b)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c41661)
Location: include/net/lwtunnel.h:77
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
In net/ipv4/route.c (ffffffff81ccfe4c)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7317)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cd933f)
Location: include/net/lwtunnel.h:77
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81d7724b)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a516)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81da731b)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfe7e)
Location: include/net/lwtunnel.h:77
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
In net/ipv4/route.c (ffffffff81e9005c)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81e97938)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e99a8f)
Location: include/net/lwtunnel.h:77
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43acb)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81f584a6)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81f7693b)
Location: include/net/lwtunnel.h:77
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb219e)
Location: include/net/lwtunnel.h:77
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
In net/ipv4/route.c (ffffffff81eee783)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81ef617b)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81ef83fc)
Location: include/net/lwtunnel.h:80
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa329e)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81fb80c4)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff81fd696b)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
```
```
In net/ipv6/xfrm6_output.c (ffffffff820128ae)
Location: include/net/lwtunnel.h:80
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
In net/ipv4/route.c (ffffffff81fb28e3)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81fba114)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fbc31b)
Location: include/net/lwtunnel.h:80
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff8207092f)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff820856b3)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/route.c (ffffffff820a42eb)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e1a0f)
Location: include/net/lwtunnel.h:80
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
In net/ipv4/route.c (ffff800010c5bca4)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffff800010d1534c)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (c0d6b330)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (c0e1afd8)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (c000000000d5de94)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (c000000000e42314)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffe0007c4e52)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffffffe00085aa54)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff8194b99e)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffffffff819f0a77)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff8190548e)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffffffff819ad837)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff819b616e)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffffffff81a5b4f7)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff819bf96e)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv6/route.c (ffffffff81a67807)
Location: include/net/lwtunnel.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:ip6_rt_copy_init
```
</details>
</li>
</ul>

## Differences
