# Function: <code>do_setlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172ba50)
Location: net/core/rtnetlink.c:1679
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_setlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
```
**Symbols:**

```
ffffffff8172ba50-ffffffff8172c5c8: do_setlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81795300)
Location: net/core/rtnetlink.c:1844
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff81795300-ffffffff81795fa7: do_setlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c2b90)
Location: net/core/rtnetlink.c:1906
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff817c2b90-ffffffff817c38ae: do_setlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e1340)
Location: net/core/rtnetlink.c:1975
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff817e1340-ffffffff817e2199: do_setlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185be90)
Location: net/core/rtnetlink.c:2147
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff8185be90-ffffffff8185ccec: do_setlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2261
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff818a7e00-ffffffff818a8c03: do_setlink (STB_LOCAL)
ffffffff818ad58a-ffffffff818ad5aa: do_setlink.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2377
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff818cbf70-ffffffff818ccd9b: do_setlink (STB_LOCAL)
ffffffff818d17ea-ffffffff818d180a: do_setlink.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2382
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff819190b0-ffffffff81919a23: do_setlink (STB_LOCAL)
ffffffff8191e781-ffffffff8191e7a3: do_setlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2404
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff8194b6d0-ffffffff8194c043: do_setlink (STB_LOCAL)
ffffffff81950ce8-ffffffff81950d0a: do_setlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2489
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff81a1c310-ffffffff81a1cdde: do_setlink (STB_LOCAL)
ffffffff81a21b80-ffffffff81a21ba2: do_setlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2593
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff81a1c6b0-ffffffff81a1d2d9: do_setlink (STB_LOCAL)
ffffffff81c316a5-ffffffff81c316c7: do_setlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2587
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff81a03460-ffffffff81a0409c: do_setlink (STB_LOCAL)
ffffffff81c239ae-ffffffff81c239d0: do_setlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2597
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff81ab5a40-ffffffff81ab6685: do_setlink (STB_LOCAL)
ffffffff81d36e12-ffffffff81d36e34: do_setlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2650
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff81c2f560-ffffffff81c30380: do_setlink (STB_LOCAL)
ffffffff81f03728-ffffffff81f03748: do_setlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de2850)
Location: net/core/rtnetlink.c:2690
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff81de2850-ffffffff81de3688: do_setlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e53d20)
Location: net/core/rtnetlink.c:2748
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff81e53d20-ffffffff81e54b75: do_setlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f13080)
Location: net/core/rtnetlink.c:2780
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff81f13080-ffffffff81f13eee: do_setlink (STB_LOCAL)
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
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010becc58)
Location: net/core/rtnetlink.c:2404
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffff800010becc58-ffff800010bed520: do_setlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d05190)
Location: net/core/rtnetlink.c:2404
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
c0d05190-c0d05a94: do_setlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd0ce0)
Location: net/core/rtnetlink.c:2404
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
c000000000cd0ce0-c000000000cd171c: do_setlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076f2fc)
Location: net/core/rtnetlink.c:2404
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffe00076f2fc-ffffffe00076f9de: do_setlink (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2404
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff818eb6a0-ffffffff818ec013: do_setlink (STB_LOCAL)
ffffffff818f0cb8-ffffffff818f0cda: do_setlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2404
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff818a54e0-ffffffff818a5e53: do_setlink (STB_LOCAL)
ffffffff818aaaf8-ffffffff818aab1a: do_setlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2404
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff8193c6d0-ffffffff8193d043: do_setlink (STB_LOCAL)
ffffffff81941ce8-ffffffff81941d0a: do_setlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_setlink(const struct sk_buff *skb, struct net_device *dev, struct ifinfomsg *ifm, struct netlink_ext_ack *extack, struct nlattr **tb, char *ifname, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:2404
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_setlink
```
**Symbols:**

```
ffffffff8195df40-ffffffff8195e8d4: do_setlink (STB_LOCAL)
ffffffff819635e8-ffffffff8196360a: do_setlink.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, dev, ifm, tb, ifname, status</code> ➡️ <code>skb, dev, ifm, extack, tb, ifname, status</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>char *ifname</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, dev, ifm, extack, tb, ifname, status</code> ➡️ <code>skb, dev, ifm, extack, tb, status</code>
</li>
</ul>
</details>
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
