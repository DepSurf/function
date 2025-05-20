# Function: <code>ip_neigh_gw4</code>

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
In net/ipv4/route.c (ffffffff819729aa)
Location: include/net/route.h:356
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8197bd0f)
Location: include/net/route.h:356
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff819a931d)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819b26b2)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff81a925a9)
Location: include/net/route.h:367
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a9bdbf)
Location: include/net/route.h:367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81a30aeb)
Location: include/net/route.h:367
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9c449)
Location: include/net/route.h:367
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81aa5c1f)
Location: include/net/route.h:367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81a17b4d)
Location: include/net/route.h:367
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a875da)
Location: include/net/route.h:367
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81a90bec)
Location: include/net/route.h:367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81acb138)
Location: include/net/route.h:367
Inline: True
```
```
In net/ipv4/route.c (ffffffff81b42825)
Location: include/net/route.h:367
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81b4c049)
Location: include/net/route.h:367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81c46e4d)
Location: include/net/route.h:380
Inline: True
```
```
In net/ipv4/route.c (ffffffff81ccf0c1)
Location: include/net/route.h:380
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81cd978b)
Location: include/net/route.h:380
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81dfb39d)
Location: include/net/route.h:375
Inline: True
```
```
In net/ipv4/route.c (ffffffff81e8f401)
Location: include/net/route.h:375
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81e99f0b)
Location: include/net/route.h:375
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81e6c2a7)
Location: include/net/route.h:367
Inline: True
```
```
In net/ipv4/route.c (ffffffff81eedae3)
Location: include/net/route.h:367
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81ef887b)
Location: include/net/route.h:367
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81f2bb94)
Location: include/net/route.h:361
Inline: True
```
```
In net/ipv4/route.c (ffffffff81fb1c43)
Location: include/net/route.h:361
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81fbc7ad)
Location: include/net/route.h:361
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffff800010c58d44)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffff800010c635d0)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (c0d68a78)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c0d72940)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (c000000000d5aad4)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (c000000000d668d4)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffe0007c2d3e)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffe0007cabf8)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff8194918d)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff81952522)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff81902c7d)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff8190c012)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff819b395d)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819bccf2)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/route.c (ffffffff819bd02d)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/ip_output.c (ffffffff819c6602)
Location: include/net/route.h:357
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
  - net/ipv4/ip_output.c:ip_finish_output2
```
</details>
</li>
</ul>

## Differences
