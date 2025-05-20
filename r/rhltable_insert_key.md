# Function: <code>rhltable_insert_key</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8186c224)
Location: include/linux/rhashtable.h:855
Inline: True
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
In net/ipv4/ipmr.c (ffffffff818ecaf1)
Location: include/linux/rhashtable.h:857
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff8194289f)
Location: include/linux/rhashtable.h:871
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff8199f0aa)
Location: include/linux/rhashtable.h:871
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff8197296f)
Location: include/linux/rhashtable.h:739
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff819d5bca)
Location: include/linux/rhashtable.h:739
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff819dc3fa)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff81a44c76)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81a133ea)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b866)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81b0392b)
Location: include/linux/rhashtable.h:848
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff81b7673a)
Location: include/linux/rhashtable.h:848
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81b11aa0)
Location: include/linux/rhashtable.h:848
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff81b854ff)
Location: include/linux/rhashtable.h:848
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81b0034f)
Location: include/linux/rhashtable.h:848
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff81b7406f)
Location: include/linux/rhashtable.h:848
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81bc243f)
Location: include/linux/rhashtable.h:848
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff81c3e91e)
Location: include/linux/rhashtable.h:848
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81d5721f)
Location: include/linux/rhashtable.h:848
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff81ddd0c0)
Location: include/linux/rhashtable.h:848
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/events/hw_breakpoint.c (ffffffff8134de03)
Location: include/linux/rhashtable.h:857
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f208bc)
Location: include/linux/rhashtable.h:857
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff81fae543)
Location: include/linux/rhashtable.h:857
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/events/hw_breakpoint.c (ffffffff8137ee88)
Location: include/linux/rhashtable.h:857
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81f810dc)
Location: include/linux/rhashtable.h:857
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff8200f9c3)
Location: include/linux/rhashtable.h:857
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In kernel/events/hw_breakpoint.c (ffffffff813a80e8)
Location: include/linux/rhashtable.h:857
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8204775c)
Location: include/linux/rhashtable.h:857
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff820de953)
Location: include/linux/rhashtable.h:857
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffff800010ccd964)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffff800010d453a8)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (c0dd8a68)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (c0e47fb4)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (c000000000dea388)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (c000000000e7aeec)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffe00081fe42)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffe0008806d0)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff819b2bea)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff81a1aef6)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff8196f21a)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff819d7cb6)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81a1d48a)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff81a85976)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
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
In net/ipv4/ipmr.c (ffffffff81a285ef)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/ipv6/ip6mr.c (ffffffff81a923e3)
Location: include/linux/rhashtable.h:855
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
</details>
</li>
</ul>

## Differences
