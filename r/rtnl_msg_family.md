# Function: <code>rtnl_msg_family</code>

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
In net/core/fib_rules.c (ffffffff8173a16c)
Location: include/net/rtnetlink.h:18
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff817a6f8c)
Location: include/net/rtnetlink.h:18
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff817d5acc)
Location: include/net/rtnetlink.h:18
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff817f4f59)
Location: include/net/rtnetlink.h:19
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818707b9)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818c1fd9)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818eae15)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8193a8b5)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8196d775)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
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
In net/core/fib_rules.c (ffffffff81a40a25)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeb2b6)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (ffffffff81b00596)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4c8f3)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81b73438)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
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
In net/core/fib_rules.c (ffffffff81a43ee5)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
```
In net/ipv4/fib_frontend.c (ffffffff81af81bc)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (ffffffff81b0e616)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5b53e)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81b82168)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
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
In net/core/fib_rules.c (ffffffff81a28d35)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae38cc)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (ffffffff81afc2f6)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/ip6_fib.c (ffffffff81b499ee)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81b70d88)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
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
In net/core/fib_rules.c (ffffffff81addb04)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba31de)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (ffffffff81bbdb67)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/ip6_fib.c (ffffffff81c10fb3)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81c3b79f)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
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
In net/core/fib_rules.c (ffffffff81c5e6c4)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
```
In net/ipv4/fib_frontend.c (ffffffff81d359e5)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (ffffffff81d5244d)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/ip6_fib.c (ffffffff81dac3b2)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81dd98f5)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
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
In net/core/fib_rules.c (ffffffff81e14f24)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
```
In net/ipv4/fib_frontend.c (ffffffff81efdf95)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (ffffffff81f1c70d)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7bda2)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff81fab545)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
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
In net/core/fib_rules.c (ffffffff81e88834)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5da28)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (ffffffff81f7c1ed)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdbfc0)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff8200bce5)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
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
In net/core/fib_rules.c (ffffffff81f4a844)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
```
In net/ipv4/fib_frontend.c (ffffffff82023fe8)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_dump_fib
```
```
In net/ipv4/ipmr.c (ffffffff820428dd)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
```
In net/ipv6/ip6_fib.c (ffffffff820a9b1f)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
```
In net/ipv6/ip6mr.c (ffffffff820dacb5)
Location: include/net/rtnetlink.h:37
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffff800010c13e40)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (c0d2b878)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (c000000000d01434)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffe00078f4ac)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8190d745)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff818c7505)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff8195e775)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/fib_rules.c (ffffffff819809d5)
Location: include/net/rtnetlink.h:23
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_dumprule
```
</details>
</li>
</ul>

## Differences
