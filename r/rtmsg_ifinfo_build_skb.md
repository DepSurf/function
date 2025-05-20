# Function: <code>rtmsg_ifinfo_build_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172fa70)
Location: net/core/rtnetlink.c:2515
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8172fa70-ffffffff8172fb3e: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8179a1c0)
Location: net/core/rtnetlink.c:2709
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8179a1c0-ffffffff8179a28e: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c7f60)
Location: net/core/rtnetlink.c:2782
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff817c7f60-ffffffff817c802e: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e6840)
Location: net/core/rtnetlink.c:2870
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff817e6840-ffffffff817e6907: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81861730)
Location: net/core/rtnetlink.c:3099
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81861730-ffffffff8186180a: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ad2f0)
Location: net/core/rtnetlink.c:3254
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818ad2f0-ffffffff818ad3ce: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818d1550)
Location: net/core/rtnetlink.c:3397
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818d1550-ffffffff818d162e: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:3458
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8191eaac-ffffffff8191eabf: rtmsg_ifinfo_build_skb.cold (STB_LOCAL)
ffffffff8191e410-ffffffff8191e4eb: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81950a40)
Location: net/core/rtnetlink.c:3489
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81950a40-ffffffff81950b1f: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a21890)
Location: net/core/rtnetlink.c:3692
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81a21890-ffffffff81a2196f: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a21cd0)
Location: net/core/rtnetlink.c:3784
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81a21cd0-ffffffff81a21daf: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a09010)
Location: net/core/rtnetlink.c:3782
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81a09010-ffffffff81a090ef: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81abb4e0)
Location: net/core/rtnetlink.c:3803
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81abb4e0-ffffffff81abb5bf: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c35d10)
Location: net/core/rtnetlink.c:3895
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81c35d10-ffffffff81c35e04: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex, u32 portid, u32 seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de92c0)
Location: net/core/rtnetlink.c:3939
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81de92c0-ffffffff81de93b6: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex, u32 portid, const struct nlmsghdr *nlh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e5ab00)
Location: net/core/rtnetlink.c:4021
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81e5ab00-ffffffff81e5ac17: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex, u32 portid, const struct nlmsghdr *nlh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f19ec0)
Location: net/core/rtnetlink.c:4061
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
```
**Symbols:**

```
ffffffff81f19ec0-ffffffff81f19fd7: rtmsg_ifinfo_build_skb (STB_GLOBAL)
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
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bf2500)
Location: net/core/rtnetlink.c:3489
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffff800010bf2500-ffff800010bf2618: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d0adf4)
Location: net/core/rtnetlink.c:3489
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
c0d0adf4-c0d0af04: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd73f0)
Location: net/core/rtnetlink.c:3489
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
c000000000cd73f0-c000000000cd7588: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00077405c)
Location: net/core/rtnetlink.c:3489
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffe00077405c-ffffffe000774136: rtmsg_ifinfo_build_skb (STB_GLOBAL)
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
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818f0a10)
Location: net/core/rtnetlink.c:3489
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818f0a10-ffffffff818f0aef: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818aa850)
Location: net/core/rtnetlink.c:3489
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818aa850-ffffffff818aa92f: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81941a40)
Location: net/core/rtnetlink.c:3489
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81941a40-ffffffff81941b1f: rtmsg_ifinfo_build_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *rtmsg_ifinfo_build_skb(int type, struct net_device *dev, unsigned int change, u32 event, gfp_t flags, int *new_nsid, int new_ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81963340)
Location: net/core/rtnetlink.c:3489
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81963340-ffffffff8196341f: rtmsg_ifinfo_build_skb (STB_GLOBAL)
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
<code>u32 event</code>
</li>
<li>
<b>Param reordered. </b>
<code>type, dev, change, flags</code> ➡️ <code>type, dev, change, event, flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *new_nsid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int new_ifindex</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 portid</code>
</li>
<li>
<b>Param added. </b>
<code>u32 seq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct nlmsghdr *nlh</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 seq</code>
</li>
</ul>
</details>
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
