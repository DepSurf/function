# Function: <code>ipv6_mc_netdev_event</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff818b1f10)
Location: net/ipv6/mcast.c:2615
Inline: False
```
**Symbols:**

```
ffffffff818b1f10-ffffffff818b1faa: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81934270)
Location: net/ipv6/mcast.c:2617
Inline: False
```
**Symbols:**

```
ffffffff81934270-ffffffff8193430a: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff8198ce70)
Location: net/ipv6/mcast.c:2643
Inline: False
```
**Symbols:**

```
ffffffff8198ce70-ffffffff8198cf1e: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c36e0)
Location: net/ipv6/mcast.c:2643
Inline: False
```
**Symbols:**

```
ffffffff819c36e0-ffffffff819c378e: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a32530)
Location: net/ipv6/mcast.c:2642
Inline: False
```
**Symbols:**

```
ffffffff81a32530-ffffffff81a325e8: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a69080)
Location: net/ipv6/mcast.c:2642
Inline: False
```
**Symbols:**

```
ffffffff81a69080-ffffffff81a69138: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b626a0)
Location: net/ipv6/mcast.c:2640
Inline: False
```
**Symbols:**

```
ffffffff81b626a0-ffffffff81b626ca: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b71410)
Location: net/ipv6/mcast.c:2640
Inline: False
```
**Symbols:**

```
ffffffff81b71410-ffffffff81b7143a: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b5f290)
Location: net/ipv6/mcast.c:2830
Inline: False
```
**Symbols:**

```
ffffffff81b5f290-ffffffff81b5f38e: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:2829
Inline: False
```
**Symbols:**

```
ffffffff81c26a40-ffffffff81c26b4a: ipv6_mc_netdev_event (STB_LOCAL)
ffffffff81d409fb-ffffffff81d40a0f: ipv6_mc_netdev_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:2831
Inline: False
```
**Symbols:**

```
ffffffff81dc35b0-ffffffff81dc368c: ipv6_mc_netdev_event (STB_LOCAL)
ffffffff81f0d3e4-ffffffff81f0d3f9: ipv6_mc_netdev_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:2831
Inline: False
```
**Symbols:**

```
ffffffff81f94740-ffffffff81f9481c: ipv6_mc_netdev_event (STB_LOCAL)
ffffffff820b482d-ffffffff820b4842: ipv6_mc_netdev_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:2831
Inline: False
```
**Symbols:**

```
ffffffff81ff50c0-ffffffff81ff519c: ipv6_mc_netdev_event (STB_LOCAL)
ffffffff82135886-ffffffff8213589b: ipv6_mc_netdev_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:2832
Inline: False
```
**Symbols:**

```
ffffffff820c2c90-ffffffff820c2d6c: ipv6_mc_netdev_event (STB_LOCAL)
ffffffff82217393-ffffffff822173a8: ipv6_mc_netdev_event.cold (STB_LOCAL)
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
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffff800010d309d0)
Location: net/ipv6/mcast.c:2642
Inline: False
```
**Symbols:**

```
ffff800010d309d0-ffff800010d30b14: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c0e34004)
Location: net/ipv6/mcast.c:2642
Inline: False
```
**Symbols:**

```
c0e34004-c0e340f8: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (c000000000e62600)
Location: net/ipv6/mcast.c:2642
Inline: False
```
**Symbols:**

```
c000000000e62600-c000000000e62740: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffe0008701c4)
Location: net/ipv6/mcast.c:2642
Inline: False
```
**Symbols:**

```
ffffffe0008701c4-ffffffe000870290: ipv6_mc_netdev_event (STB_LOCAL)
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
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a08710)
Location: net/ipv6/mcast.c:2642
Inline: False
```
**Symbols:**

```
ffffffff81a08710-ffffffff81a087c8: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff819c54d0)
Location: net/ipv6/mcast.c:2642
Inline: False
```
**Symbols:**

```
ffffffff819c54d0-ffffffff819c5588: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a73190)
Location: net/ipv6/mcast.c:2642
Inline: False
```
**Symbols:**

```
ffffffff81a73190-ffffffff81a73248: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipv6_mc_netdev_event(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81a7f810)
Location: net/ipv6/mcast.c:2642
Inline: False
```
**Symbols:**

```
ffffffff81a7f810-ffffffff81a7f8c8: ipv6_mc_netdev_event (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
