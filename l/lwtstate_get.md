# Function: <code>lwtstate_get</code>

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
In net/ipv4/route.c (ffffffff81754442)
Location: include/net/lwtunnel.h:46
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_set_nexthop
```
```
In net/ipv4/fib_semantics.c (ffffffff8179ce37)
Location: include/net/lwtunnel.h:46
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff817d3808)
Location: include/net/lwtunnel.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff817c05ca)
Location: include/net/lwtunnel.h:46
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8180adf3)
Location: include/net/lwtunnel.h:46
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff8184133b)
Location: include/net/lwtunnel.h:46
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff817f1d4b)
Location: include/net/lwtunnel.h:55
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/fib_semantics.c (ffffffff8183bf01)
Location: include/net/lwtunnel.h:55
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff8187303b)
Location: include/net/lwtunnel.h:55
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv4/route.c (ffffffff818107eb)
Location: include/net/lwtunnel.h:56
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8185d648)
Location: include/net/lwtunnel.h:56
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff8189a6ac)
Location: include/net/lwtunnel.h:56
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv4/route.c (ffffffff8188fc72)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff818dd681)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff8191b002)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv4/route.c (ffffffff818e51cb)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_semantics.c (ffffffff81933f5d)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff81976c0e)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv4/route.c (ffffffff819120d5)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_semantics.c (ffffffff819635a3)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff819ac7fb)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv4/route.c (ffffffff819747fd)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff819c79c4)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a16ede)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff819ab21c)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff819fe574)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4db2e)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff81a95386)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff81aece3d)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b428de)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff81a9f372)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff81af9a4d)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b5265e)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff81a8a2b4)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae50fb)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b40001)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff81b45153)
Location: include/net/lwtunnel.h:60
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba4dcb)
Location: include/net/lwtunnel.h:60
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c065f5)
Location: include/net/lwtunnel.h:60
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff81cd1ea3)
Location: include/net/lwtunnel.h:60
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff81d37765)
Location: include/net/lwtunnel.h:60
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_init
```
```
In net/ipv6/route.c (ffffffff81da0c35)
Location: include/net/lwtunnel.h:60
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff81e923c8)
Location: include/net/lwtunnel.h:60
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff81efffa5)
Location: include/net/lwtunnel.h:60
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_init
```
```
In net/ipv6/route.c (ffffffff81f6ff25)
Location: include/net/lwtunnel.h:60
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff81ef0b58)
Location: include/net/lwtunnel.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff81f5fa25)
Location: include/net/lwtunnel.h:63
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_init
```
```
In net/ipv6/route.c (ffffffff81fd0035)
Location: include/net/lwtunnel.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffffffff81fb4ca5)
Location: include/net/lwtunnel.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff82025ff5)
Location: include/net/lwtunnel.h:63
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_init
```
```
In net/ipv6/route.c (ffffffff8209da35)
Location: include/net/lwtunnel.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/ipv4/route.c (ffff800010c5b424)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffff800010cb6690)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0f00c)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
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
In net/ipv4/route.c (c0d6aa18)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (c0dc2210)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (c0e13014)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
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
In net/ipv4/route.c (c000000000d5d274)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (c000000000dce94c)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (c000000000e37c4c)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffe0007c4726)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffe00080de04)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (ffffffe000853d22)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff8194b08c)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff8199e314)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ed1be)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff81904b7c)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff81957dd4)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a9f7e)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff819b585c)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff81a08bb4)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a57c3e)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff819bed36)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:rt_dst_clone
```
```
In net/ipv4/fib_semantics.c (ffffffff81a13314)
Location: include/net/lwtunnel.h:57
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a63d3e)
Location: include/net/lwtunnel.h:57
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
```
</details>
</li>
</ul>

## Differences
