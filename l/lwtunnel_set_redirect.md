# Function: <code>lwtunnel_set_redirect</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e5df6)
Location: include/net/lwtunnel.h:130
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81973db0)
Location: include/net/lwtunnel.h:130
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
In net/ipv4/route.c (ffffffff81912d08)
Location: include/net/lwtunnel.h:130
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff819a99c0)
Location: include/net/lwtunnel.h:130
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
In net/ipv4/route.c (ffffffff81975105)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a16ee6)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (ffffffff819abb25)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a4db36)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (ffffffff81a93ddd)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81b428e6)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (ffffffff81a9dce7)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81b52666)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (ffffffff81a88c2b)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81b40009)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (ffffffff81b4339b)
Location: include/net/lwtunnel.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81c065fd)
Location: include/net/lwtunnel.h:135
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
In net/ipv4/route.c (ffffffff81ccfe43)
Location: include/net/lwtunnel.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81da0c3d)
Location: include/net/lwtunnel.h:135
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
In net/ipv4/route.c (ffffffff81e90053)
Location: include/net/lwtunnel.h:135
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81f6ff2d)
Location: include/net/lwtunnel.h:135
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
In net/ipv4/route.c (ffffffff81eee77c)
Location: include/net/lwtunnel.h:138
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff81fd0040)
Location: include/net/lwtunnel.h:138
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
In net/ipv4/route.c (ffffffff81fb28dc)
Location: include/net/lwtunnel.h:138
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv6/route.c (ffffffff8209da40)
Location: include/net/lwtunnel.h:138
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
In net/ipv4/route.c (ffff800010c5bca0)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffff800010d0f158)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (c0d6b328)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (c0e13034)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (c000000000d5de8c)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (c000000000e37c64)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (ffffffe0007c4e4c)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffe000853d2e)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (ffffffff8194b995)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff819ed1c6)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (ffffffff81905485)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff819a9f86)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (ffffffff819b6165)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a57c46)
Location: include/net/lwtunnel.h:132
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
In net/ipv4/route.c (ffffffff819bf965)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv6/route.c (ffffffff81a63d46)
Location: include/net/lwtunnel.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
```
</details>
</li>
</ul>

## Differences
