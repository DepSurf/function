# Function: <code>nla_get_be32</code>

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
In net/ipv4/fib_frontend.c (ffffffff81799e3f)
Location: include/net/netlink.h:1001
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a457f)
Location: include/net/netlink.h:1001
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
  - net/ipv4/ip_tunnel_core.c:ip_tun_build_state
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
In net/ipv4/fib_frontend.c (ffffffff81807ae4)
Location: include/net/netlink.h:1025
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8181796d)
Location: include/net/netlink.h:1025
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff81838b86)
Location: include/net/netlink.h:1025
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818491da)
Location: include/net/netlink.h:1025
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff81859ee9)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff8186c900)
Location: include/net/netlink.h:1037
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff818d9def)
Location: include/net/netlink.h:1080
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff818ed1ee)
Location: include/net/netlink.h:1080
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff81930865)
Location: include/net/netlink.h:1080
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff8194317e)
Location: include/net/netlink.h:1080
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff8195fc51)
Location: include/net/netlink.h:1223
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff81973137)
Location: include/net/netlink.h:1223
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff819c65f6)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff819d442a)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff819dcc38)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff819fd1a6)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81a0af9a)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a13d17)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff81aebb1a)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af9372)
Location: include/net/netlink.h:1548
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81afb7de)
Location: include/net/netlink.h:1548
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81b00a8e)
Location: include/net/netlink.h:1548
Inline: True
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
In net/ipv4/fib_frontend.c (ffffffff81af8a23)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b05fd7)
Location: include/net/netlink.h:1561
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81b08eae)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81b0eb6e)
Location: include/net/netlink.h:1561
Inline: True
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
In net/ipv4/fib_frontend.c (ffffffff81ae4183)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af1815)
Location: include/net/netlink.h:1561
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81af55d9)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81afc85e)
Location: include/net/netlink.h:1561
Inline: True
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
In net/ipv4/fib_frontend.c (ffffffff81ba3ad3)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb1d25)
Location: include/net/netlink.h:1561
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81bb5ed9)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81bbdf43)
Location: include/net/netlink.h:1561
Inline: True
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
In net/ipv4/fib_frontend.c (ffffffff81d3635a)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d4544a)
Location: include/net/netlink.h:1561
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff81d4974e)
Location: include/net/netlink.h:1561
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81d52a09)
Location: include/net/netlink.h:1561
Inline: True
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
In lib/nlattr.c (ffffffff8188ffc4)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe98b)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0da97)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
```
```
In net/ipv4/nexthop.c (ffffffff81f12d8e)
Location: include/net/netlink.h:1610
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81f1cd4e)
Location: include/net/netlink.h:1610
Inline: True
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
In lib/nlattr.c (ffffffff818d2482)
Location: include/net/netlink.h:1611
Inline: True
Inline callers:
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5e4ce)
Location: include/net/netlink.h:1611
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6d737)
Location: include/net/netlink.h:1611
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
```
```
In net/ipv4/nexthop.c (ffffffff81f72a55)
Location: include/net/netlink.h:1611
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81f7c714)
Location: include/net/netlink.h:1611
Inline: True
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
In lib/nlattr.c (ffffffff81924e6b)
Location: include/net/netlink.h:1687
Inline: True
Inline callers:
  - lib/nlattr.c:validate_nla
  - lib/nlattr.c:nla_validate_range_unsigned
```
```
In net/ipv4/fib_frontend.c (ffffffff82024a94)
Location: include/net/netlink.h:1687
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82033e87)
Location: include/net/netlink.h:1687
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
  - net/ipv4/ip_tunnel_core.c:ip_tunnel_netlink_parms
```
```
In net/ipv4/nexthop.c (ffffffff82038bf8)
Location: include/net/netlink.h:1687
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff82042e07)
Location: include/net/netlink.h:1687
Inline: True
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
In net/ipv4/fib_frontend.c (ffff800010cb5380)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffff800010cc4570)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffff800010cce3f0)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (c0dc0dd4)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (c0dcff38)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (c0dd94ec)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (c000000000dcccc8)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (c000000000de059c)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (c000000000deb038)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffe00080ccf0)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffe000819a92)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffe0008206f8)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff8199cf46)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff819aad3a)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff819b3428)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In drivers/net/vxlan.c (ffffffff8176eb0d)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
```
```
In net/ipv4/fib_frontend.c (ffffffff81956a06)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff819647fa)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff8196fa58)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/netfilter/nfnetlink.c (ffffffff81998fbc)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nfnetlink.c:nfnetlink_rcv
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199ad76)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_config
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict_batch
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199b9b2)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
  - net/netfilter/nfnetlink_log.c:nfulnl_recv_config
```
```
In net/netfilter/nf_conntrack_proto_generic.c (ffffffff819a4d40)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_generic.c:generic_timeout_nlattr_to_obj
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a4e4a)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_timeout_nlattr_to_obj
```
```
In net/netfilter/nf_conntrack_proto_udp.c (ffffffff819a6eb1)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_udp.c:udp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_udp.c:udp_timeout_nlattr_to_obj
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (ffffffff819a7593)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmp.c:icmp_timeout_nlattr_to_obj
```
```
In net/netfilter/nf_conntrack_proto_icmpv6.c (ffffffff819a85d0)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmpv6.c:icmpv6_timeout_nlattr_to_obj
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a985b)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_timeout_nlattr_to_obj
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aa59b)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:sctp_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_sctp.c:nlattr_to_sctp
  - net/netfilter/nf_conntrack_proto_sctp.c:nlattr_to_sctp
```
```
In net/netfilter/nf_conntrack_proto_gre.c (ffffffff819ab5f1)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_gre.c:gre_timeout_nlattr_to_obj
  - net/netfilter/nf_conntrack_proto_gre.c:gre_timeout_nlattr_to_obj
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b10d7)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_parse
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_parse
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_parse
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_glue_parse
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_new_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_synproxy
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_synproxy
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_synproxy
  - net/netfilter/nf_conntrack_netlink.c:change_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:change_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:change_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_status
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_del_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_alloc_filter
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_alloc_filter
```
```
In net/ipv4/fib_frontend.c (ffffffff81a077e6)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81a155da)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a1dcc8)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff81a11f26)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/nexthop.c (ffffffff81a2001a)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_to_nh_config
```
```
In net/ipv4/ipmr.c (ffffffff81a29007)
Location: include/net/netlink.h:1481
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
</details>
</li>
</ul>

## Differences
