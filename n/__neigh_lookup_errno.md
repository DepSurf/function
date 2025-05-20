# Function: <code>__neigh_lookup_errno</code>

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
In net/core/neighbour.c (ffffffff8172962d)
Location: include/net/neighbour.h:484
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/ipv4/arp.c (ffffffff8178c86a)
Location: include/net/neighbour.h:484
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/core/neighbour.c (ffffffff81793114)
Location: include/net/neighbour.h:484
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/ipv4/arp.c (ffffffff817f9e6a)
Location: include/net/neighbour.h:484
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/core/neighbour.c (ffffffff817c09e4)
Location: include/net/neighbour.h:484
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/ipv4/arp.c (ffffffff8182ad3a)
Location: include/net/neighbour.h:484
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/core/neighbour.c (ffffffff817df0a3)
Location: include/net/neighbour.h:497
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/ipv4/arp.c (ffffffff8184bf7e)
Location: include/net/neighbour.h:497
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/core/neighbour.c (ffffffff81859949)
Location: include/net/neighbour.h:498
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/ipv4/arp.c (ffffffff818cbc1e)
Location: include/net/neighbour.h:498
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/core/neighbour.c (ffffffff818a4ed7)
Location: include/net/neighbour.h:499
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
```
```
In net/ipv4/arp.c (ffffffff819220fd)
Location: include/net/neighbour.h:499
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/ipv4/arp.c (ffffffff81950f2d)
Location: include/net/neighbour.h:524
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/ipv4/arp.c (ffffffff819b580d)
Location: include/net/neighbour.h:527
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/ipv4/arp.c (ffffffff819ec52d)
Location: include/net/neighbour.h:526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ada48d)
Location: include/net/neighbour.h:525
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ae6f2d)
Location: include/net/neighbour.h:526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ad21ed)
Location: include/net/neighbour.h:526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81b90e3d)
Location: include/net/neighbour.h:532
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81d22174)
Location: include/net/neighbour.h:565
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ee95f4)
Location: include/net/neighbour.h:562
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81f48f24)
Location: include/net/neighbour.h:560
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8200f0b4)
Location: include/net/neighbour.h:558
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/ipv4/arp.c (ffff800010ca2070)
Location: include/net/neighbour.h:526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/ipv4/arp.c (c0daee5c)
Location: include/net/neighbour.h:526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/ipv4/arp.c (c000000000db5450)
Location: include/net/neighbour.h:526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/ipv4/arp.c (ffffffe0007fe00c)
Location: include/net/neighbour.h:526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/ipv4/arp.c (ffffffff8198c35d)
Location: include/net/neighbour.h:526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/ipv4/arp.c (ffffffff81945e1d)
Location: include/net/neighbour.h:526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/ipv4/arp.c (ffffffff819f6b6d)
Location: include/net/neighbour.h:526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
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
In net/ipv4/arp.c (ffffffff81a00d8d)
Location: include/net/neighbour.h:526
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
```
</details>
</li>
</ul>

## Differences
