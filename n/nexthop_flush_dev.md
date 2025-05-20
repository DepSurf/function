# Function: <code>nexthop_flush_dev</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d5600)
Location: net/ipv4/nexthop.c:1052
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff819d5600-ffffffff819d566c: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0c170)
Location: net/ipv4/nexthop.c:1054
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81a0c170-ffffffff81a0c1dc: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afcc80)
Location: net/ipv4/nexthop.c:1150
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81afcc80-ffffffff81afccec: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0aa50)
Location: net/ipv4/nexthop.c:1367
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81b0aa50-ffffffff81b0aad3: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af82e0)
Location: net/ipv4/nexthop.c:2351
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81af82e0-ffffffff81af8363: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nexthop_flush_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2374
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81bb9060-ffffffff81bb9106: nexthop_flush_dev (STB_LOCAL)
ffffffff81d3e5ab-ffffffff81d3e5c0: nexthop_flush_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nexthop_flush_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2374
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81d4d010-ffffffff81d4d0bb: nexthop_flush_dev (STB_LOCAL)
ffffffff81f0aee2-ffffffff81f0aefd: nexthop_flush_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void nexthop_flush_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2374
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81f168e0-ffffffff81f1698b: nexthop_flush_dev (STB_LOCAL)
ffffffff820b2778-ffffffff820b2793: nexthop_flush_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void nexthop_flush_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2374
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81f76590-ffffffff81f7663b: nexthop_flush_dev (STB_LOCAL)
ffffffff82133930-ffffffff8213394b: nexthop_flush_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void nexthop_flush_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:2397
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff8203cd60-ffffffff8203ce0b: nexthop_flush_dev (STB_LOCAL)
ffffffff8221533c-ffffffff82215357: nexthop_flush_dev.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc5508)
Location: net/ipv4/nexthop.c:1054
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffff800010cc5508-ffff800010cc5588: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dd0f44)
Location: net/ipv4/nexthop.c:1054
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
c0dd0f44-c0dd0fc0: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de1ad0)
Location: net/ipv4/nexthop.c:1054
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
c000000000de1ad0-c000000000de1b80: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe00081935e)
Location: net/ipv4/nexthop.c:1054
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffe00081935e-ffffffe0008193c8: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819abf10)
Location: net/ipv4/nexthop.c:1054
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff819abf10-ffffffff819abf7c: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819659d0)
Location: net/ipv4/nexthop.c:1054
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff819659d0-ffffffff81965a3c: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a167b0)
Location: net/ipv4/nexthop.c:1054
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81a167b0-ffffffff81a1681c: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nexthop_flush_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a211f0)
Location: net/ipv4/nexthop.c:1054
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_netdev_event
```
**Symbols:**

```
ffffffff81a211f0-ffffffff81a2125c: nexthop_flush_dev (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int event</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
