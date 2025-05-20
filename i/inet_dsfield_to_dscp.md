# Function: <code>inet_dsfield_to_dscp</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd3723)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/fib_frontend.c (ffffffff81d3629e)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3878c)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
```
```
In net/ipv4/fib_rules.c (ffffffff81d51224)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81de18e8)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/route.c (ffffffff81e9391f)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe8ce)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f00d2c)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
```
```
In net/ipv4/fib_rules.c (ffffffff81f1b084)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb3dc8)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/route.c (ffffffff81ef20cc)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5e35e)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff81f607ac)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
```
```
In net/ipv4/fib_rules.c (ffffffff81f7ace9)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff82014568)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/route.c (ffffffff81fb621c)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/fib_frontend.c (ffffffff8202491e)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_semantics.c (ffffffff82026d7c)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_select_default
```
```
In net/ipv4/fib_rules.c (ffffffff820413e9)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff820e36a8)
Location: include/net/inet_dscp.h:42
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
