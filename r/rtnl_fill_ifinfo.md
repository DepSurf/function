# Function: <code>rtnl_fill_ifinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172e050)
Location: net/core/rtnetlink.c:1191
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
```
**Symbols:**

```
ffffffff8172e050-ffffffff8172ef6c: rtnl_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81797920)
Location: net/core/rtnetlink.c:1252
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff81797920-ffffffff817989be: rtnl_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c56a0)
Location: net/core/rtnetlink.c:1282
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff817c56a0-ffffffff817c6742: rtnl_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e4050)
Location: net/core/rtnetlink.c:1333
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff817e4050-ffffffff817e50a2: rtnl_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int tgt_netnsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8185f0f0)
Location: net/core/rtnetlink.c:1432
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff8185f0f0-ffffffff8185ffe7: rtnl_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1532
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff818ab250-ffffffff818ac102: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff818ad5aa-ffffffff818ad5c2: rtnl_fill_ifinfo.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1584
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff818cece0-ffffffff818cfb64: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff818d180a-ffffffff818d1822: rtnl_fill_ifinfo.cold.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1587
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff8191ba90-ffffffff8191c90c: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff8191e8ae-ffffffff8191e9c1: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1587
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff8194e0b0-ffffffff8194ef50: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff81950d16-ffffffff81950d2e: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1661
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff81a1fc40-ffffffff81a2066f: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff81a21bae-ffffffff81a21bc6: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1701
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff81a205a0-ffffffff81a210c7: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff81c316eb-ffffffff81c31703: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1703
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff81a07670-ffffffff81a083d9: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff81c239f4-ffffffff81c23a0c: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1692
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff81ab9ad0-ffffffff81aba8cf: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff81d36ea2-ffffffff81d36eea: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1732
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff81c33fe0-ffffffff81c35095: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff81f037fb-ffffffff81f03849: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1767
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff81de7460-ffffffff81de85cc: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff820abf49-ffffffff820abf7f: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1778
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff81e58ea0-ffffffff81e59e08: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff8212d6ae-ffffffff8212d6f0: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1807
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff81f181c0-ffffffff81f1919c: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff8220f3fb-ffffffff8220f43d: rtnl_fill_ifinfo.cold (STB_LOCAL)
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
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bf0008)
Location: net/core/rtnetlink.c:1587
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffff800010bf0008-ffff800010bf0d5c: rtnl_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d0865c)
Location: net/core/rtnetlink.c:1587
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
c0d0865c-c0d094dc: rtnl_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd4470)
Location: net/core/rtnetlink.c:1587
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
c000000000cd4470-c000000000cd5594: rtnl_fill_ifinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe0007721de)
Location: net/core/rtnetlink.c:1587
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffe0007721de-ffffffe000772c6e: rtnl_fill_ifinfo (STB_LOCAL)
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
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1587
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff818ee080-ffffffff818eef20: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff818f0ce6-ffffffff818f0cfe: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1587
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff818a7ec0-ffffffff818a8d60: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff818aab26-ffffffff818aab3e: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1587
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff8193f0b0-ffffffff8193ff50: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff81941d16-ffffffff81941d2e: rtnl_fill_ifinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rtnl_fill_ifinfo(struct sk_buff *skb, struct net_device *dev, struct net *src_net, int type, u32 pid, u32 seq, u32 change, unsigned int flags, u32 ext_filter_mask, u32 event, int *new_nsid, int new_ifindex, int tgt_netnsid, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1587
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtmsg_ifinfo_build_skb
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
```
**Symbols:**

```
ffffffff81960980-ffffffff81961851: rtnl_fill_ifinfo (STB_LOCAL)
ffffffff81963616-ffffffff8196362e: rtnl_fill_ifinfo.cold (STB_LOCAL)
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
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *src_net</code>
</li>
<li>
<b>Param added. </b>
<code>int *new_nsid</code>
</li>
<li>
<b>Param added. </b>
<code>int tgt_netnsid</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, dev, type, pid, seq, change, flags, ext_filter_mask, event</code> ➡️ <code>skb, dev, src_net, type, pid, seq, change, flags, ext_filter_mask, event, new_nsid, tgt_netnsid</code>
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
<li>
<b>Param reordered. </b>
<code>skb, dev, src_net, type, pid, seq, change, flags, ext_filter_mask, event, new_nsid, tgt_netnsid</code> ➡️ <code>skb, dev, src_net, type, pid, seq, change, flags, ext_filter_mask, event, new_nsid, new_ifindex, tgt_netnsid</code>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
