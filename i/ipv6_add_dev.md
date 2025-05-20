# Function: <code>ipv6_add_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cbbb0)
Location: net/ipv6/addrconf.c:333
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:ipv6_find_idev
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_init
```
**Symbols:**

```
ffffffff817cbbb0-ffffffff817cc01b: ipv6_add_dev.part.39 (STB_LOCAL)
ffffffff817cc020-ffffffff817cc073: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183a1e0)
Location: net/ipv6/addrconf.c:335
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff8183a1e0-ffffffff8183a685: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186bc10)
Location: net/ipv6/addrconf.c:367
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff8186bc10-ffffffff8186c08a: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81890740)
Location: net/ipv6/addrconf.c:374
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81890740-ffffffff81890bb8: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81911e90)
Location: net/ipv6/addrconf.c:375
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81911e90-ffffffff81912309: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:366
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff819692c0-ffffffff81969772: ipv6_add_dev (STB_LOCAL)
ffffffff8196f395-ffffffff8196f3bb: ipv6_add_dev.cold.76 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199ebdd)
Location: net/ipv6/addrconf.c:366
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff8199eba0-ffffffff8199f037: ipv6_add_dev (STB_LOCAL)
ffffffff819a4f45-ffffffff819a4f6b: ipv6_add_dev.cold.78 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0b110)
Location: net/ipv6/addrconf.c:363
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81a0acb0-ffffffff81a0b104: ipv6_add_dev.part.0 (STB_LOCAL)
ffffffff81a1132c-ffffffff81a11353: ipv6_add_dev.part.0.cold (STB_LOCAL)
ffffffff81a0b110-ffffffff81a0b174: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a41dc0)
Location: net/ipv6/addrconf.c:363
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81a41960-ffffffff81a41db4: ipv6_add_dev.part.0 (STB_LOCAL)
ffffffff81a47fcf-ffffffff81a47ff6: ipv6_add_dev.part.0.cold (STB_LOCAL)
ffffffff81a41dc0-ffffffff81a41e24: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:364
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81b37320-ffffffff81b3772c: ipv6_add_dev (STB_LOCAL)
ffffffff81b3ead7-ffffffff81b3eafe: ipv6_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:364
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81b46050-ffffffff81b4645c: ipv6_add_dev (STB_LOCAL)
ffffffff81c32b81-ffffffff81c32ba8: ipv6_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:366
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81b33ea0-ffffffff81b3434a: ipv6_add_dev (STB_LOCAL)
ffffffff81c24e90-ffffffff81c24eb7: ipv6_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:373
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81bfa510-ffffffff81bfaa0b: ipv6_add_dev (STB_LOCAL)
ffffffff81d3f882-ffffffff81d3f8d0: ipv6_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:368
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81d93950-ffffffff81d93e82: ipv6_add_dev (STB_LOCAL)
ffffffff81f0c1f4-ffffffff81f0c241: ipv6_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:368
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81f62110-ffffffff81f625ae: ipv6_add_dev (STB_LOCAL)
ffffffff820b39ff-ffffffff820b3a28: ipv6_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:367
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81fc1f00-ffffffff81fc239b: ipv6_add_dev (STB_LOCAL)
ffffffff82134af0-ffffffff82134b19: ipv6_add_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:371
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff8208f480-ffffffff8208f91b: ipv6_add_dev (STB_LOCAL)
ffffffff822165b4-ffffffff822165dd: ipv6_add_dev.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d033f8)
Location: net/ipv6/addrconf.c:363
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffff800010d033f8-ffff800010d03828: ipv6_add_dev.part.0 (STB_LOCAL)
ffff800010d03828-ffff800010d038a4: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (c0e0a87c)
Location: net/ipv6/addrconf.c:363
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
c0e0a87c-c0e0acd8: ipv6_add_dev.part.0 (STB_LOCAL)
c0e0acd8-c0e0ad60: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2cdf0)
Location: net/ipv6/addrconf.c:363
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
c000000000e2cdf0-c000000000e2d384: ipv6_add_dev.part.0 (STB_LOCAL)
c000000000e2d390-c000000000e2d450: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084c6ba)
Location: net/ipv6/addrconf.c:363
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffe00084c6ba-ffffffe00084cadc: ipv6_add_dev.part.0 (STB_LOCAL)
ffffffe00084cadc-ffffffe00084cb52: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e1450)
Location: net/ipv6/addrconf.c:363
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff819e0ff0-ffffffff819e1444: ipv6_add_dev.part.0 (STB_LOCAL)
ffffffff819e765f-ffffffff819e7686: ipv6_add_dev.part.0.cold (STB_LOCAL)
ffffffff819e1450-ffffffff819e14b4: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199e210)
Location: net/ipv6/addrconf.c:363
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff8199ddb0-ffffffff8199e204: ipv6_add_dev.part.0 (STB_LOCAL)
ffffffff819a441f-ffffffff819a4446: ipv6_add_dev.part.0.cold (STB_LOCAL)
ffffffff8199e210-ffffffff8199e274: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4bed0)
Location: net/ipv6/addrconf.c:363
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81a4ba70-ffffffff81a4bec4: ipv6_add_dev.part.0 (STB_LOCAL)
ffffffff81a520df-ffffffff81a52106: ipv6_add_dev.part.0.cold (STB_LOCAL)
ffffffff81a4bed0-ffffffff81a4bf34: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inet6_dev *ipv6_add_dev(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a57e40)
Location: net/ipv6/addrconf.c:363
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_init
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:ipv6_find_idev
```
**Symbols:**

```
ffffffff81a579e0-ffffffff81a57e34: ipv6_add_dev.part.0 (STB_LOCAL)
ffffffff81a5e02f-ffffffff81a5e056: ipv6_add_dev.part.0.cold (STB_LOCAL)
ffffffff81a57e40-ffffffff81a57ea4: ipv6_add_dev (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
