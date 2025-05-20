# Function: <code>lwtunnel_input_redirect</code>

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
In net/ipv4/route.c (ffffffff81755bdf)
Location: include/net/lwtunnel.h:71
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d60af)
Location: include/net/lwtunnel.h:71
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
In net/ipv4/route.c (ffffffff817c1da4)
Location: include/net/lwtunnel.h:71
Inline: True
```
```
In net/ipv6/route.c (ffffffff8184465b)
Location: include/net/lwtunnel.h:71
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
In net/ipv4/route.c (ffffffff817f1d60)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:set_lwt_redirect
```
```
In net/ipv6/route.c (ffffffff818763d7)
Location: include/net/lwtunnel.h:80
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff8180ebd5)
Location: include/net/lwtunnel.h:81
Inline: True
Inline callers:
  - net/ipv4/route.c:set_lwt_redirect
```
```
In net/ipv6/route.c (ffffffff8189bae2)
Location: include/net/lwtunnel.h:81
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff8188e195)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:set_lwt_redirect
```
```
In net/ipv6/route.c (ffffffff8191e788)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff818e6025)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81973f31)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff81912f3d)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff819a9b49)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff81975134)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a16efc)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (ffffffff819abb54)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a4db4c)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (ffffffff81a93e08)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81b42907)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (ffffffff81a9dd13)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81b52687)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (ffffffff81a88de1)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81b401ee)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (ffffffff81b43551)
Location: include/net/lwtunnel.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81c067ef)
Location: include/net/lwtunnel.h:85
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
In net/ipv4/route.c (ffffffff81cd003a)
Location: include/net/lwtunnel.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81da0e42)
Location: include/net/lwtunnel.h:85
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
In net/ipv4/route.c (ffffffff81e901f2)
Location: include/net/lwtunnel.h:85
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81f70132)
Location: include/net/lwtunnel.h:85
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
In net/ipv4/route.c (ffffffff81eee8f0)
Location: include/net/lwtunnel.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81fd023d)
Location: include/net/lwtunnel.h:88
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
In net/ipv4/route.c (ffffffff81fb2a50)
Location: include/net/lwtunnel.h:88
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff8209dc3d)
Location: include/net/lwtunnel.h:88
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
In net/ipv4/route.c (ffff800010c5bcc8)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffff800010d0f174)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (c0d6b35c)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (c0e13054)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (c000000000d5dec0)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (c000000000e37c88)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (ffffffe0007c4e70)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffe000853d3c)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (ffffffff8194b9c4)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff819ed1dc)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (ffffffff819054b4)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff819a9f9c)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (ffffffff819b6194)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a57c5c)
Location: include/net/lwtunnel.h:82
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
In net/ipv4/route.c (ffffffff819bf994)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a63d5c)
Location: include/net/lwtunnel.h:82
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
```
</details>
</li>
</ul>

## Differences
