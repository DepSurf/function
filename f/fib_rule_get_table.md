# Function: <code>fib_rule_get_table</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_rules.c (ffffffff8181488f)
Location: include/net/fib_rules.h:109
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff8186ddf3)
Location: include/net/fib_rules.h:109
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff8184601f)
Location: include/net/fib_rules.h:116
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff818a0bd3)
Location: include/net/fib_rules.h:116
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff81867bef)
Location: include/net/fib_rules.h:117
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff818c7243)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff818e7cef)
Location: include/net/fib_rules.h:125
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff8194a763)
Location: include/net/fib_rules.h:125
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff8193e914)
Location: include/net/fib_rules.h:135
Inline: True
```
```
In net/ipv6/fib6_rules.c (ffffffff819a3a71)
Location: include/net/fib_rules.h:135
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff8196e7c4)
Location: include/net/fib_rules.h:135
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d2ce2)
Location: include/net/fib_rules.h:135
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff819da391)
Location: include/net/fib_rules.h:135
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff819d7fcc)
Location: include/net/fib_rules.h:136
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a41b54)
Location: include/net/fib_rules.h:136
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff81a48f62)
Location: include/net/fib_rules.h:136
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff81a0eabc)
Location: include/net/fib_rules.h:137
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a0ee74)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffffffff81a787b4)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7fb52)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff81aff745)
Location: include/net/fib_rules.h:137
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81affe3d)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffffffff81b7315d)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7aa52)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff81b0d6f9)
Location: include/net/fib_rules.h:138
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81b0de7d)
Location: include/net/fib_rules.h:138
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffffffff81b81e8d)
Location: include/net/fib_rules.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff81b899af)
Location: include/net/fib_rules.h:138
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff81afb4d0)
Location: include/net/fib_rules.h:138
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81afbc7d)
Location: include/net/fib_rules.h:138
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffffffff81b70aad)
Location: include/net/fib_rules.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff81b78809)
Location: include/net/fib_rules.h:138
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff81bbc910)
Location: include/net/fib_rules.h:138
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81bbd11d)
Location: include/net/fib_rules.h:138
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffffffff81c3ae0d)
Location: include/net/fib_rules.h:138
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff81c43349)
Location: include/net/fib_rules.h:138
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff81d50ef4)
Location: include/net/fib_rules.h:117
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81d517ec)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffffffff81dd8d5c)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff81de20df)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff81f1ad14)
Location: include/net/fib_rules.h:117
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f1b6cc)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffffffff81faa81c)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb460f)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff81f7a980)
Location: include/net/fib_rules.h:117
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f7b19b)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffffffff8200afbb)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff82014d92)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff82041080)
Location: include/net/fib_rules.h:117
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8204188b)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffffffff820d9fbb)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3ed2)
Location: include/net/fib_rules.h:117
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffff800010cc8828)
Location: include/net/fib_rules.h:137
Inline: True
```
```
In net/ipv4/ipmr.c (ffff800010cc8cf0)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffff800010d41e50)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b1cc)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (c0dd3ca4)
Location: include/net/fib_rules.h:137
Inline: True
```
```
In net/ipv4/ipmr.c (c0dd4128)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (c0e4478c)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (c0e4c528)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (c000000000de5c64)
Location: include/net/fib_rules.h:137
Inline: True
```
```
In net/ipv4/ipmr.c (c000000000de6248)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (c000000000e76c08)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (c000000000e81570)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffe00081cad4)
Location: include/net/fib_rules.h:137
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffe00081cf64)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffffffe00087d4bc)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffe000884230)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff819ae85c)
Location: include/net/fib_rules.h:137
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a17e44)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1f1e2)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff8196ae8c)
Location: include/net/fib_rules.h:137
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d4c04)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff819dbfa2)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff81a190fc)
Location: include/net/fib_rules.h:137
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a828c4)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89c62)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/fib_rules.c (ffffffff81a23b8a)
Location: include/net/fib_rules.h:137
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81a23f14)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rule_action
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f194)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_rule_action
```
```
In net/ipv6/fib6_rules.c (ffffffff81a968c2)
Location: include/net/fib_rules.h:137
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
```
</details>
</li>
</ul>

## Differences
