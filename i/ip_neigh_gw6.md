# Function: <code>ip_neigh_gw6</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81972a25)
Location: include/net/ndisc.h:440
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197c07d)
Location: include/net/ndisc.h:440
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff819a9398)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b2a23)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff81a92636)
Location: include/net/ndisc.h:442
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9c07b)
Location: include/net/ndisc.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81a2e951)
Location: include/net/ndisc.h:442
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9c4d6)
Location: include/net/ndisc.h:442
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5edb)
Location: include/net/ndisc.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81a15fa3)
Location: include/net/ndisc.h:442
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a87666)
Location: include/net/ndisc.h:442
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90ea5)
Location: include/net/ndisc.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81ac760c)
Location: include/net/ndisc.h:442
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81b428c0)
Location: include/net/ndisc.h:442
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c38e)
Location: include/net/ndisc.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81c43e96)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81ccf156)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd9a45)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81df81e6)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81e8f496)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e9a1c5)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81e6984f)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81eedb78)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81ef8b1f)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81f28ebc)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:bpf_out_neigh_v6
```
```
In net/ipv4/route.c (ffffffff81fb1cd8)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81fbca4d)
Location: include/net/ndisc.h:430
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffff800010c58dc0)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffff800010c63934)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (c0d68af8)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c0d72d6c)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (c000000000d5ab90)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c000000000d66da0)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffe0007c2db2)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007caf24)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff81949208)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81952893)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff81902cf8)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190c383)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff819b39d8)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bd063)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff819bd0a8)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c6973)
Location: include/net/ndisc.h:441
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
</details>
</li>
</ul>

## Differences
