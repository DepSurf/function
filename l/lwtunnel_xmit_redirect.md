# Function: <code>lwtunnel_xmit_redirect</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817efa45)
Location: include/net/lwtunnel.h:88
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817f90ec)
Location: include/net/lwtunnel.h:88
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81863cf1)
Location: include/net/lwtunnel.h:88
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81872826)
Location: include/net/lwtunnel.h:88
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff8180f572)
Location: include/net/lwtunnel.h:89
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81819504)
Location: include/net/lwtunnel.h:89
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff818892b7)
Location: include/net/lwtunnel.h:89
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81897616)
Location: include/net/lwtunnel.h:89
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff8188f3f4)
Location: include/net/lwtunnel.h:90
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81897b14)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff819096f7)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81918946)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff818e41bc)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffffffff818ebe44)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81960a0a)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81977a87)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
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
In net/ipv4/route.c (ffffffff819110cc)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffffffff81919be4)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81996d0a)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819ad677)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
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
In net/ipv4/route.c (ffffffff81973765)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffffffff8197bce0)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81a00b0a)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a1a769)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
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
In net/ipv4/route.c (ffffffff819aa0e5)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffffffff819b2680)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81a376da)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a513d9)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
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
In net/ipv4/route.c (ffffffff81a947d5)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffffffff81a9bd79)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d215)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b48b0a)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
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
In net/ipv4/route.c (ffffffff81a9e7cf)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffffffff81aa5bd9)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81b3bc25)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b5771a)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
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
In net/ipv4/route.c (ffffffff81a89731)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_mtu
```
```
In net/ipv4/ip_forward.c (ffffffff81a8eeb7)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a90ba9)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b9de)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b679)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81b45306)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76bed)
Location: include/net/lwtunnel.h:90
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
In net/ipv4/route.c (ffffffff81b44281)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81b49dd7)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4c000)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0377)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1adb)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81c0c446)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c41658)
Location: include/net/lwtunnel.h:93
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
In net/ipv4/route.c (ffffffff81cd0e0f)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81cd7312)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cd973f)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77242)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a50d)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81da7316)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfe75)
Location: include/net/lwtunnel.h:93
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
In net/ipv4/route.c (ffffffff81e9104f)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81e97933)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e99ebf)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43ac2)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81f5849d)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81f76936)
Location: include/net/lwtunnel.h:93
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb2195)
Location: include/net/lwtunnel.h:93
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
In net/ipv4/route.c (ffffffff81eef7ff)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6176)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81ef8835)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3295)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81fb80bb)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81fd6966)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/xfrm6_output.c (ffffffff820128a5)
Location: include/net/lwtunnel.h:96
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
In net/ipv4/route.c (ffffffff81fb395c)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81fba10f)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fbc76a)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/xfrm/xfrm_output.c (ffffffff82070926)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff820856aa)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff820a42e6)
Location: include/net/lwtunnel.h:96
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_default_advmss
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:rt6_insert_exception
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e1a06)
Location: include/net/lwtunnel.h:96
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
In net/ipv4/route.c (ffff800010c5a218)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffff800010c63590)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffff800010cfa2d4)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffff800010d15340)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
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
In net/ipv4/route.c (c0d69890)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (c0d72900)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (c0dff3e4)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (c0e1afc4)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
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
In net/ipv4/route.c (c000000000d5bce4)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (c000000000d6689c)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (c000000000e1f298)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (c000000000e42300)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
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
In net/ipv4/route.c (ffffffe0007c3812)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffffffe0007cabce)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffe000843ca6)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffe00085aa48)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
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
In net/ipv4/route.c (ffffffff81949f55)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffffffff819524f0)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff819d6d6a)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819f0a69)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
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
In net/ipv4/route.c (ffffffff81903a45)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffffffff8190bfe0)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81993b2a)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff819ad829)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
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
In net/ipv4/route.c (ffffffff819b4725)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffffffff819bccc0)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81a417ea)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a5b4e9)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
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
In net/ipv4/route.c (ffffffff819bde65)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
```
In net/ipv4/ip_output.c (ffffffff819c65d0)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d44a)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output2
```
```
In net/ipv6/route.c (ffffffff81a677f9)
Location: include/net/lwtunnel.h:90
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_mtu_from_fib6
  - net/ipv6/route.c:ip6_mtu
  - net/ipv6/route.c:rt6_insert_exception
```
</details>
</li>
</ul>

## Differences
