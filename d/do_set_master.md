# Function: <code>do_set_master</code>

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
In net/core/rtnetlink.c (ffffffff8172c097)
Location: net/core/rtnetlink.c:1641
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
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
In net/core/rtnetlink.c (ffffffff8179564c)
Location: net/core/rtnetlink.c:1806
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
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
In net/core/rtnetlink.c (ffffffff817c2edd)
Location: net/core/rtnetlink.c:1868
Inline: True
Inline callers:
  - net/core/rtnetlink.c:do_setlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e1000)
Location: net/core/rtnetlink.c:1937
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff817e1000-ffffffff817e1092: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185b760)
Location: net/core/rtnetlink.c:2108
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8185b760-ffffffff8185b804: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a7060)
Location: net/core/rtnetlink.c:2222
Inline: True
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff818a7060-ffffffff818a7104: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ca7a0)
Location: net/core/rtnetlink.c:2338
Inline: True
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff818ca7a0-ffffffff818ca844: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819177e0)
Location: net/core/rtnetlink.c:2343
Inline: True
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff819177e0-ffffffff81917888: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81949e20)
Location: net/core/rtnetlink.c:2364
Inline: True
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81949e20-ffffffff81949ed8: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a19350)
Location: net/core/rtnetlink.c:2450
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81a19350-ffffffff81a193f8: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a19540)
Location: net/core/rtnetlink.c:2493
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81a19540-ffffffff81a195e8: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a00450)
Location: net/core/rtnetlink.c:2487
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81a00450-ffffffff81a004f8: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81ab25a0)
Location: net/core/rtnetlink.c:2497
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81ab25a0-ffffffff81ab2648: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2b610)
Location: net/core/rtnetlink.c:2551
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81c2b610-ffffffff81c2b6c8: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81dde240)
Location: net/core/rtnetlink.c:2591
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81dde240-ffffffff81dde2f8: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e4f180)
Location: net/core/rtnetlink.c:2649
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81e4f180-ffffffff81e4f238: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f0e050)
Location: net/core/rtnetlink.c:2681
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:rtnl_newlink_create
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff81f0e050-ffffffff81f0e102: do_set_master (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bebaa0)
Location: net/core/rtnetlink.c:2364
Inline: True
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffff800010bebaa0-ffff800010bebb6c: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d045d8)
Location: net/core/rtnetlink.c:2364
Inline: True
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
c0d045d8-c0d0468c: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccedb0)
Location: net/core/rtnetlink.c:2364
Inline: True
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
c000000000ccedb0-c000000000cceef8: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076f14a)
Location: net/core/rtnetlink.c:2364
Inline: True
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffe00076f14a-ffffffe00076f1f0: do_set_master (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e9df0)
Location: net/core/rtnetlink.c:2364
Inline: True
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff818e9df0-ffffffff818e9ea8: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a3c30)
Location: net/core/rtnetlink.c:2364
Inline: True
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff818a3c30-ffffffff818a3ce8: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8193ae20)
Location: net/core/rtnetlink.c:2364
Inline: True
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8193ae20-ffffffff8193aed8: do_set_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int do_set_master(struct net_device *dev, int ifindex, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195c660)
Location: net/core/rtnetlink.c:2364
Inline: True
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:do_setlink
```
**Symbols:**

```
ffffffff8195c660-ffffffff8195c718: do_set_master (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
