# Function: <code>addrconf_timeout_fixup</code>

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
In net/ipv4/devinet.c (0)
Location: include/net/addrconf.h:125
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817cb4c7)
Location: include/net/addrconf.h:125
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff817d7ef3)
Location: include/net/addrconf.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff817fdc6e)
Location: include/net/addrconf.h:138
Inline: True
Inline callers:
  - net/ipv4/devinet.c:set_ifa_lifetime
  - net/ipv4/devinet.c:set_ifa_lifetime
```
```
In net/ipv6/addrconf.c (ffffffff8183dc1a)
Location: include/net/addrconf.h:138
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81842dbd)
Location: include/net/addrconf.h:138
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff8182ebce)
Location: include/net/addrconf.h:139
Inline: True
Inline callers:
  - net/ipv4/devinet.c:set_ifa_lifetime
  - net/ipv4/devinet.c:set_ifa_lifetime
```
```
In net/ipv6/addrconf.c (ffffffff8186f82a)
Location: include/net/addrconf.h:139
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81874b44)
Location: include/net/addrconf.h:139
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff8184ef2e)
Location: include/net/addrconf.h:157
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff818945f0)
Location: include/net/addrconf.h:157
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81898480)
Location: include/net/addrconf.h:157
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff818cec9e)
Location: include/net/addrconf.h:156
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81915a77)
Location: include/net/addrconf.h:156
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81919830)
Location: include/net/addrconf.h:156
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff819250f1)
Location: include/net/addrconf.h:169
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8196d12b)
Location: include/net/addrconf.h:169
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81971320)
Location: include/net/addrconf.h:169
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff81953f01)
Location: include/net/addrconf.h:170
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819a2c60)
Location: include/net/addrconf.h:170
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff819a7f24)
Location: include/net/addrconf.h:170
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff819b8811)
Location: include/net/addrconf.h:171
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a0dc53)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a14d02)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff819ef511)
Location: include/net/addrconf.h:171
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a44934)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a4b8f2)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff81add461)
Location: include/net/addrconf.h:172
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b3b224)
Location: include/net/addrconf.h:172
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b41942)
Location: include/net/addrconf.h:172
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff81aea181)
Location: include/net/addrconf.h:175
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b49f34)
Location: include/net/addrconf.h:175
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b50402)
Location: include/net/addrconf.h:175
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff81ad58e1)
Location: include/net/addrconf.h:175
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b37b24)
Location: include/net/addrconf.h:175
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b3e8d9)
Location: include/net/addrconf.h:175
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff81b947a1)
Location: include/net/addrconf.h:175
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81bfe314)
Location: include/net/addrconf.h:175
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81c05229)
Location: include/net/addrconf.h:175
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff81d260c1)
Location: include/net/addrconf.h:177
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d97cf5)
Location: include/net/addrconf.h:177
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81d9f2af)
Location: include/net/addrconf.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff81eed901)
Location: include/net/addrconf.h:177
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f66975)
Location: include/net/addrconf.h:177
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81f6e2bf)
Location: include/net/addrconf.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff81f4d2c1)
Location: include/net/addrconf.h:177
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fc6a85)
Location: include/net/addrconf.h:177
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81fce37f)
Location: include/net/addrconf.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff820133d1)
Location: include/net/addrconf.h:185
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff820941a5)
Location: include/net/addrconf.h:185
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff8209bbdb)
Location: include/net/addrconf.h:185
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffff800010ca5368)
Location: include/net/addrconf.h:171
Inline: True
```
```
In net/ipv6/addrconf.c (ffff800010d06d48)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffff800010d0e730)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (c0db1bb8)
Location: include/net/addrconf.h:171
Inline: True
```
```
In net/ipv6/addrconf.c (c0e0d914)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (c0e15444)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (c000000000db90f4)
Location: include/net/addrconf.h:171
Inline: True
```
```
In net/ipv6/addrconf.c (c000000000e31140)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (c000000000e3b034)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffe000800bd4)
Location: include/net/addrconf.h:171
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffe00084ebd6)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffe000856754)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff8198f2b1)
Location: include/net/addrconf.h:171
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819e3fc4)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff819eaf82)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff81948d71)
Location: include/net/addrconf.h:171
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819a0d84)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff819a7d42)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff819f9b51)
Location: include/net/addrconf.h:171
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a4ea44)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a55a02)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/devinet.c (ffffffff81a03e41)
Location: include/net/addrconf.h:171
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a5a9e4)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a61a02)
Location: include/net/addrconf.h:171
Inline: True
Inline callers:
  - net/ipv6/route.c:rtm_to_fib6_config
  - net/ipv6/route.c:rt6_route_rcv
```
</details>
</li>
</ul>

## Differences
