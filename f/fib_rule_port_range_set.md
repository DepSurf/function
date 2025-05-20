# Function: <code>fib_rule_port_range_set</code>

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
In net/core/fib_rules.c (ffffffff818c1b87)
Location: include/net/fib_rules.h:155
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (ffffffff8193e66b)
Location: include/net/fib_rules.h:155
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff819a324a)
Location: include/net/fib_rules.h:155
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/core/fib_rules.c (ffffffff818ea9f7)
Location: include/net/fib_rules.h:155
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (ffffffff8196e50b)
Location: include/net/fib_rules.h:155
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff819d9d5a)
Location: include/net/fib_rules.h:155
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/core/fib_rules.c (ffffffff8193a462)
Location: include/net/fib_rules.h:156
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (ffffffff819d7cc8)
Location: include/net/fib_rules.h:156
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81a48917)
Location: include/net/fib_rules.h:156
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff8196d322)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (ffffffff81a0e7b8)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7f4f7)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff81a40522)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/ipv4/fib_rules.c (ffffffff81affad3)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a5b3)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff81a43222)
Location: include/net/fib_rules.h:158
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/ipv4/fib_rules.c (ffffffff81b0db53)
Location: include/net/fib_rules.h:158
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81b89503)
Location: include/net/fib_rules.h:158
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff81a27f82)
Location: include/net/fib_rules.h:158
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/ipv4/fib_rules.c (ffffffff81afb953)
Location: include/net/fib_rules.h:158
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81b78343)
Location: include/net/fib_rules.h:158
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff81adcd22)
Location: include/net/fib_rules.h:158
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/ipv4/fib_rules.c (ffffffff81bbcdf3)
Location: include/net/fib_rules.h:158
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81c42e73)
Location: include/net/fib_rules.h:158
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff81c5e29d)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/ipv4/fib_rules.c (ffffffff81d51463)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81de1ac3)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff81e14abd)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/ipv4/fib_rules.c (ffffffff81f1b2d3)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb3fb3)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff81e883cd)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/ipv4/fib_rules.c (ffffffff81f7af43)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff82014753)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff81f4a3dd)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:rule_find
  - net/core/fib_rules.c:rule_find
```
```
In net/ipv4/fib_rules.c (ffffffff82041643)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3893)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffff800010c13ad4)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (ffff800010cc88c8)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffff800010d4afb8)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/core/fib_rules.c (c0d2a87c)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_fill_rule
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (c0dd3f14)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (c0e4c328)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (c000000000d00f64)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (c000000000de5798)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (c000000000e808e8)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffe00078f22c)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (ffffffe00081cb64)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffe00088406e)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
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
In net/core/fib_rules.c (ffffffff8190d2f2)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (ffffffff819ae558)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1eb87)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff818c70b2)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (ffffffff8196ab88)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff819db947)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff8195e322)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (ffffffff81a18df8)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89607)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/core/fib_rules.c (ffffffff81980572)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_nl_delrule
```
```
In net/ipv4/fib_rules.c (ffffffff81a23878)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_delete
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv6/fib6_rules.c (ffffffff81a96267)
Location: include/net/fib_rules.h:157
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_delete
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_configure
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
</details>
</li>
</ul>

## Differences
