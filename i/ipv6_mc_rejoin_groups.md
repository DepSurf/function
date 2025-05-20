# Function: <code>ipv6_mc_rejoin_groups</code>

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
In net/ipv6/mcast.c (ffffffff818b1f38)
Location: net/ipv6/mcast.c:2600
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff81934298)
Location: net/ipv6/mcast.c:2602
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff8198ce98)
Location: net/ipv6/mcast.c:2628
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff819c3708)
Location: net/ipv6/mcast.c:2628
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff81a3255a)
Location: net/ipv6/mcast.c:2627
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff81a690aa)
Location: net/ipv6/mcast.c:2627
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipv6_mc_rejoin_groups(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b625b0)
Location: net/ipv6/mcast.c:2625
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
**Symbols:**

```
ffffffff81b625b0-ffffffff81b62693: ipv6_mc_rejoin_groups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipv6_mc_rejoin_groups(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b71320)
Location: net/ipv6/mcast.c:2625
Inline: False
Direct callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
**Symbols:**

```
ffffffff81b71320-ffffffff81b71403: ipv6_mc_rejoin_groups (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff81b5f2bc)
Location: net/ipv6/mcast.c:2814
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff81c26a6c)
Location: net/ipv6/mcast.c:2813
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff81dc35e2)
Location: net/ipv6/mcast.c:2815
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff81f94772)
Location: net/ipv6/mcast.c:2815
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff81ff50f2)
Location: net/ipv6/mcast.c:2815
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff820c2cc2)
Location: net/ipv6/mcast.c:2816
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffff800010d30a1c)
Location: net/ipv6/mcast.c:2627
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (c0e3404c)
Location: net/ipv6/mcast.c:2627
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (c000000000e62648)
Location: net/ipv6/mcast.c:2627
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffe000870202)
Location: net/ipv6/mcast.c:2627
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff81a0873a)
Location: net/ipv6/mcast.c:2627
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff819c54fa)
Location: net/ipv6/mcast.c:2627
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff81a731ba)
Location: net/ipv6/mcast.c:2627
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
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
In net/ipv6/mcast.c (ffffffff81a7f83a)
Location: net/ipv6/mcast.c:2627
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_netdev_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
