# Function: <code>nexthop_add</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d58da)
Location: net/ipv4/nexthop.c:1257
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff81a0c44a)
Location: net/ipv4/nexthop.c:1259
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nexthop *nexthop_add(struct net *net, struct nh_config *cfg, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afd520)
Location: net/ipv4/nexthop.c:1380
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
**Symbols:**

```
ffffffff81afd520-ffffffff81afd80b: nexthop_add (STB_LOCAL)
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
In net/ipv4/nexthop.c (ffffffff81b0b70e)
Location: net/ipv4/nexthop.c:1603
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff81af933e)
Location: net/ipv4/nexthop.c:2608
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff81bb9e8e)
Location: net/ipv4/nexthop.c:2637
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff81d4de97)
Location: net/ipv4/nexthop.c:2637
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff81f177d7)
Location: net/ipv4/nexthop.c:2637
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff81f774b7)
Location: net/ipv4/nexthop.c:2637
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff8203dc87)
Location: net/ipv4/nexthop.c:2660
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffff800010cc5904)
Location: net/ipv4/nexthop.c:1259
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (c0dd1418)
Location: net/ipv4/nexthop.c:1259
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (c000000000de2120)
Location: net/ipv4/nexthop.c:1259
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffe00081a50a)
Location: net/ipv4/nexthop.c:1259
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff819ac1ea)
Location: net/ipv4/nexthop.c:1259
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff81965caa)
Location: net/ipv4/nexthop.c:1259
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff81a16a8a)
Location: net/ipv4/nexthop.c:1259
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
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
In net/ipv4/nexthop.c (ffffffff81a214ba)
Location: net/ipv4/nexthop.c:1259
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
