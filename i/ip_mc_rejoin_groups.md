# Function: <code>ip_mc_rejoin_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81797299)
Location: net/ipv4/igmp.c:1531
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818049cb)
Location: net/ipv4/igmp.c:1537
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8183599b)
Location: net/ipv4/igmp.c:1568
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81856edb)
Location: net/ipv4/igmp.c:1577
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff818d6d8b)
Location: net/ipv4/igmp.c:1605
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff8192d6ba)
Location: net/ipv4/igmp.c:1616
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff8195cb5a)
Location: net/ipv4/igmp.c:1625
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff819c185a)
Location: net/ipv4/igmp.c:1627
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff819f83fa)
Location: net/ipv4/igmp.c:1627
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip_mc_rejoin_groups(struct in_device *in_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae5f00)
Location: net/ipv4/igmp.c:1625
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
**Symbols:**

```
ffffffff81ae5f00-ffffffff81ae6027: ip_mc_rejoin_groups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_mc_rejoin_groups(struct in_device *in_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af2dd0)
Location: net/ipv4/igmp.c:1625
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_netdev_event
```
**Symbols:**

```
ffffffff81af2dd0-ffffffff81af2ef7: ip_mc_rejoin_groups (STB_LOCAL)
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
In net/ipv4/igmp.c (ffffffff81ade5da)
Location: net/ipv4/igmp.c:1632
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff81b9daaa)
Location: net/ipv4/igmp.c:1632
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff81d2fcda)
Location: net/ipv4/igmp.c:1639
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff81ef7dca)
Location: net/ipv4/igmp.c:1639
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff81f5785a)
Location: net/ipv4/igmp.c:1640
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff8201dcea)
Location: net/ipv4/igmp.c:1642
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffff800010cb0020)
Location: net/ipv4/igmp.c:1627
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (c0dbb9dc)
Location: net/ipv4/igmp.c:1627
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (c000000000dc6008)
Location: net/ipv4/igmp.c:1627
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffe000809100)
Location: net/ipv4/igmp.c:1627
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff8199819a)
Location: net/ipv4/igmp.c:1627
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff81951c5a)
Location: net/ipv4/igmp.c:1627
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff81a02a3a)
Location: net/ipv4/igmp.c:1627
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
In net/ipv4/igmp.c (ffffffff81a0cf6a)
Location: net/ipv4/igmp.c:1627
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_netdev_event
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
