# Function: <code>inet_validate_dscp</code>

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
In net/ipv4/fib_frontend.c (ffffffff81d36291)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_rules.c (ffffffff81d51207)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81de18c4)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/fib_frontend.c (ffffffff81efe8c1)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_rules.c (ffffffff81f1b067)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb3da4)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/fib_frontend.c (ffffffff81f5e351)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_rules.c (ffffffff81f7acd5)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff82014544)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/ipv4/fib_frontend.c (ffffffff82024911)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/fib_rules.c (ffffffff820413d5)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3684)
Location: include/net/inet_dscp.h:52
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
