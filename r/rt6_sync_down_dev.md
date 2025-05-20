# Function: <code>rt6_sync_down_dev</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819788c2)
Location: net/ipv6/route.c:4067
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81978830-ffffffff81978881: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ae430)
Location: net/ipv6/route.c:4046
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff819ae430-ffffffff819ae491: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a1c290)
Location: net/ipv6/route.c:4711
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff81a1c290-ffffffff81a1c2f1: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a52f10)
Location: net/ipv6/route.c:4724
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff81a52f10-ffffffff81a52f71: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4a605)
Location: net/ipv6/route.c:4765
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff81b4a570-ffffffff81b4a5d1: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b59285)
Location: net/ipv6/route.c:4749
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff81b591f0-ffffffff81b59251: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4717c)
Location: net/ipv6/route.c:4764
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff81b470e0-ffffffff81b47141: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4894
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff81d40152-ffffffff81d40166: rt6_sync_down_dev.cold (STB_LOCAL)
ffffffff81c0e330-ffffffff81c0e3ac: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4881
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff81f0cad3-ffffffff81f0cae7: rt6_sync_down_dev.cold (STB_LOCAL)
ffffffff81da9410-ffffffff81da9498: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:4881
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff820b4102-ffffffff820b4116: rt6_sync_down_dev.cold (STB_LOCAL)
ffffffff81f78b80-ffffffff81f78c08: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd8e1c)
Location: net/ipv6/route.c:4879
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff81fd8d70-ffffffff81fd8ddd: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a67ac)
Location: net/ipv6/route.c:4879
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff820a6700-ffffffff820a676d: rt6_sync_down_dev (STB_GLOBAL)
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
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d16f90)
Location: net/ipv6/route.c:4724
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffff800010d16f90-ffff800010d1701c: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1cb90)
Location: net/ipv6/route.c:4724
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
c0e1cb90-c0e1cc14: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e44830)
Location: net/ipv6/route.c:4724
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
c000000000e44830-c000000000e448c4: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085c1cc)
Location: net/ipv6/route.c:4724
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffe00085c1cc-ffffffe00085c22c: rt6_sync_down_dev (STB_GLOBAL)
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
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819f25a0)
Location: net/ipv6/route.c:4724
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff819f25a0-ffffffff819f2601: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819af360)
Location: net/ipv6/route.c:4724
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff819af360-ffffffff819af3c1: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5d020)
Location: net/ipv6/route.c:4724
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff81a5d020-ffffffff81a5d081: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt6_sync_down_dev(struct net_device *dev, long unsigned int event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a69400)
Location: net/ipv6/route.c:4724
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/route.c:rt6_disable_ip
```
**Symbols:**

```
ffffffff81a69400-ffffffff81a69461: rt6_sync_down_dev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
