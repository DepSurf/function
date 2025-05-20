# Function: <code>rt6_need_strict</code>

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
In net/ipv6/route.c (ffffffff817d486f)
Location: include/net/ip6_route.h:59
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817ef130)
Location: include/net/ip6_route.h:59
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv6/route.c (ffffffff81841e5f)
Location: include/net/ip6_route.h:60
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185da48)
Location: include/net/ip6_route.h:60
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv6/route.c (ffffffff81878ab8)
Location: include/net/ip6_route.h:61
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8188fa89)
Location: include/net/ip6_route.h:61
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv6/route.c (ffffffff8189dd8d)
Location: include/net/ip6_route.h:62
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b612b)
Location: include/net/ip6_route.h:62
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/ipv6/route.c (ffffffff81918f3c)
Location: include/net/ip6_route.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81938eaa)
Location: include/net/ip6_route.h:63
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff818b4aea)
Location: include/net/ip6_route.h:63
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81970c34)
Location: include/net/ip6_route.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199274a)
Location: include/net/ip6_route.h:63
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff818da6aa)
Location: include/net/ip6_route.h:63
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff819a6903)
Location: include/net/ip6_route.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c8e84)
Location: include/net/ip6_route.h:63
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff81929e3b)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81a12fc9)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a37844)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff8195c1cb)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81a49bb9)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6e36e)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff81a2ff6b)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81b45b96)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b68012)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff81a31c6b)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81b5453c)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b76834)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff81a18adb)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81b41ca2)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b651a8)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff81aca2eb)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81c099d2)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2d3e8)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff81c476fb)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81da4ba3)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dca7ef)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff81dfbdcb)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81f74053)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9b829)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff81e6f8bb)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81fd4133)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffbbf1)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff81f2f08b)
Location: include/net/ip6_route.h:64
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff820a1a45)
Location: include/net/ip6_route.h:64
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ca2ff)
Location: include/net/ip6_route.h:64
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffff800010bfe0cc)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffff800010d0ccc8)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d37cdc)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (c0d1880c)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (c0e13538)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (c0e38934)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (c000000000ce5b30)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (c000000000e38440)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (c000000000e69224)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffe00078016c)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffe00085446c)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffe00087412e)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff818fc19b)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff819e9249)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0d9fe)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff818b5fcb)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff819a6009)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca7be)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff8194d1cb)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81a53cc9)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7847e)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In net/core/filter.c (ffffffff8196eb8b)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/core/filter.c:bpf_ipv6_fib_lookup
  - net/core/filter.c:bpf_ipv6_fib_lookup
```
```
In net/ipv6/route.c (ffffffff81a5fcb9)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:ip6_rt_get_dev_rcu
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a84bee)
Location: include/net/ip6_route.h:65
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
</details>
</li>
</ul>

## Differences
