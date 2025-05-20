# Function: <code>nla_get_be64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8173a525)
Location: include/net/netlink.h:1068
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
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
In net/core/fib_rules.c (ffffffff817a6cdf)
Location: include/net/netlink.h:1092
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81812317)
Location: include/net/netlink.h:1092
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff817d57e9)
Location: include/net/netlink.h:1092
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843827)
Location: include/net/netlink.h:1092
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff817f4c62)
Location: include/net/netlink.h:1104
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81865082)
Location: include/net/netlink.h:1104
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff8187045c)
Location: include/net/netlink.h:1147
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_newrule
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e51e2)
Location: include/net/netlink.h:1147
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff818c0758)
Location: include/net/netlink.h:1147
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193baba)
Location: include/net/netlink.h:1147
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff818e96a8)
Location: include/net/netlink.h:1290
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196b7aa)
Location: include/net/netlink.h:1290
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff819390cb)
Location: include/net/netlink.h:1548
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2355)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff8196bf8b)
Location: include/net/netlink.h:1548
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a08ec5)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff81a3fe97)
Location: include/net/netlink.h:1615
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af9460)
Location: include/net/netlink.h:1615
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff81a42b97)
Location: include/net/netlink.h:1628
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b060d0)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff81a27767)
Location: include/net/netlink.h:1628
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af192d)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff81adc507)
Location: include/net/netlink.h:1628
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1e3d)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff81c5d97d)
Location: include/net/netlink.h:1628
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d4556c)
Location: include/net/netlink.h:1628
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff81e1415d)
Location: include/net/netlink.h:1677
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0e90c)
Location: include/net/netlink.h:1677
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff81e87a6d)
Location: include/net/netlink.h:1678
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6e5cc)
Location: include/net/netlink.h:1678
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff81f49a83)
Location: include/net/netlink.h:1765
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82034cef)
Location: include/net/netlink.h:1765
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffff800010c12644)
Location: include/net/netlink.h:1548
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2210)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (c0d2a190)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl2rule
```
```
In net/ipv4/ip_tunnel_core.c (c0dcd8d0)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (c000000000cff694)
Location: include/net/netlink.h:1548
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (c000000000ddd838)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffe00078e4cc)
Location: include/net/netlink.h:1548
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe0008176c6)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff8190bf5b)
Location: include/net/netlink.h:1548
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a8c65)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff818c5d1b)
Location: include/net/netlink.h:1548
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962725)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff8195cf8b)
Location: include/net/netlink.h:1548
Inline: True
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9a03)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nlattr_to_dccp
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13505)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/core/fib_rules.c (ffffffff8197f1db)
Location: include/net/netlink.h:1548
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1ded5)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
```
</details>
</li>
</ul>

## Differences
