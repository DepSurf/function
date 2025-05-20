# Function: <code>nlmsg_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8174ee40)
Location: net/netlink/af_netlink.c:3040
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff8174ee40-ffffffff8174eefb: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817bae10)
Location: net/netlink/af_netlink.c:2308
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff817bae10-ffffffff817baecb: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff817ea7b0)
Location: net/netlink/af_netlink.c:2326
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff817ea7b0-ffffffff817ea86b: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8180a710)
Location: net/netlink/af_netlink.c:2425
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff8180a710-ffffffff8180a7d5: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81889640)
Location: net/netlink/af_netlink.c:2442
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff81889640-ffffffff8188970f: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818dd0d0)
Location: net/netlink/af_netlink.c:2483
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff818dd0d0-ffffffff818dd19d: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81909a90)
Location: net/netlink/af_netlink.c:2505
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff81909a90-ffffffff81909b51: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8196ad90)
Location: net/netlink/af_netlink.c:2505
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff8196ad90-ffffffff8196ae6e: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819a1830)
Location: net/netlink/af_netlink.c:2506
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff819a1830-ffffffff819a190e: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a7b1e0)
Location: net/netlink/af_netlink.c:2497
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff81a7b1e0-ffffffff81a7b315: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a84060)
Location: net/netlink/af_netlink.c:2522
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff81a84060-ffffffff81a84195: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6d1a0)
Location: net/netlink/af_netlink.c:2532
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff81a6d1a0-ffffffff81a6d2b8: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b26810)
Location: net/netlink/af_netlink.c:2543
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtnetlink_send
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff81b26810-ffffffff81b26939: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81caf510)
Location: net/netlink/af_netlink.c:2529
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtnetlink_send
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff81caf510-ffffffff81caf61e: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e6cb20)
Location: net/netlink/af_netlink.c:2602
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtnetlink_send
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff81e6cb20-ffffffff81e6cc2e: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec8b80)
Location: net/netlink/af_netlink.c:2577
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtnetlink_send
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff81ec8b80-ffffffff81ec8c9b: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f8be00)
Location: net/netlink/af_netlink.c:2571
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnetlink_event
  - net/core/rtnetlink.c:rtnl_offload_xstats_notify
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/core/rtnetlink.c:rtmsg_ifinfo_newnet
  - net/core/rtnetlink.c:rtmsg_ifinfo
  - net/core/rtnetlink.c:rtnetlink_send
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff81f8be00-ffffffff81f8bf22: nlmsg_notify (STB_GLOBAL)
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
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4fe60)
Location: net/netlink/af_netlink.c:2506
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffff800010c4fe60-ffff800010c4ff70: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c0d60090)
Location: net/netlink/af_netlink.c:2506
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
c0d60090-c0d6017c: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d4ea80)
Location: net/netlink/af_netlink.c:2506
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
c000000000d4ea80-c000000000d4ebf8: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffe0007bb97c)
Location: net/netlink/af_netlink.c:2506
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffe0007bb97c-ffffffe0007bba66: nlmsg_notify (STB_GLOBAL)
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
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819416a0)
Location: net/netlink/af_netlink.c:2506
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff819416a0-ffffffff8194177e: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818fb190)
Location: net/netlink/af_netlink.c:2506
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff818fb190-ffffffff818fb26e: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81992830)
Location: net/netlink/af_netlink.c:2506
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
  - net/netfilter/nfnetlink.c:nfnetlink_send
```
**Symbols:**

```
ffffffff81992830-ffffffff8199290e: nlmsg_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nlmsg_notify(struct sock *sk, struct sk_buff *skb, u32 portid, unsigned int group, int report, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b5320)
Location: net/netlink/af_netlink.c:2506
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_bridge_notify
  - net/core/rtnetlink.c:rtnl_fdb_notify
  - net/netlink/genetlink.c:genl_notify
```
**Symbols:**

```
ffffffff819b5320-ffffffff819b53fe: nlmsg_notify (STB_GLOBAL)
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
