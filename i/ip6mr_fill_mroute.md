# Function: <code>ip6mr_fill_mroute</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr6_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff817f9220)
Location: net/ipv6/ip6mr.c:2355
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
**Symbols:**

```
ffffffff817f9220-ffffffff817f93c6: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr6_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81868a60)
Location: net/ipv6/ip6mr.c:2366
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
**Symbols:**

```
ffffffff81868a60-ffffffff81868c04: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr6_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8189b8b0)
Location: net/ipv6/ip6mr.c:2366
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
**Symbols:**

```
ffffffff8189b8b0-ffffffff8189ba54: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr6_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff818c1c70)
Location: net/ipv6/ip6mr.c:2372
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
**Symbols:**

```
ffffffff818c1c70-ffffffff818c1e03: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr6_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819455b0)
Location: net/ipv6/ip6mr.c:2377
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
  - net/ipv6/ip6mr.c:mr6_netlink_event
```
**Symbols:**

```
ffffffff819455b0-ffffffff81945743: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8199d0a0)
Location: net/ipv6/ip6mr.c:2270
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff8199d0a0-ffffffff8199d234: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d3c00)
Location: net/ipv6/ip6mr.c:2302
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff819d3c00-ffffffff819d3d91: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:2320
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81a41e80-ffffffff81a42010: ip6mr_fill_mroute (STB_LOCAL)
ffffffff81a46894-ffffffff81a468af: ip6mr_fill_mroute.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a78ae0)
Location: net/ipv6/ip6mr.c:2320
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81a78ae0-ffffffff81a78c6e: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b74080)
Location: net/ipv6/ip6mr.c:2325
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81b74080-ffffffff81b74210: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b82df0)
Location: net/ipv6/ip6mr.c:2326
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81b82df0-ffffffff81b82f80: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b71a80)
Location: net/ipv6/ip6mr.c:2326
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81b71a80-ffffffff81b71c0e: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81c3bf30)
Location: net/ipv6/ip6mr.c:2327
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81c3bf30-ffffffff81c3c0be: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81dda270)
Location: net/ipv6/ip6mr.c:2348
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81dda270-ffffffff81dda418: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81fabf40)
Location: net/ipv6/ip6mr.c:2353
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81fabf40-ffffffff81fac0e8: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8200c6e0)
Location: net/ipv6/ip6mr.c:2345
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff8200c6e0-ffffffff8200c886: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff820db6b0)
Location: net/ipv6/ip6mr.c:2343
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_rtm_getroute
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff820db6b0-ffffffff820db856: ip6mr_fill_mroute (STB_LOCAL)
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
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffff800010d42238)
Location: net/ipv6/ip6mr.c:2320
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffff800010d42238-ffff800010d423ec: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c0e44b90)
Location: net/ipv6/ip6mr.c:2320
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
c0e44b90-c0e44d3c: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c000000000e77030)
Location: net/ipv6/ip6mr.c:2320
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
c000000000e77030-c000000000e7727c: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffe00087d948)
Location: net/ipv6/ip6mr.c:2320
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffe00087d948-ffffffe00087da7e: ip6mr_fill_mroute (STB_LOCAL)
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
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a18170)
Location: net/ipv6/ip6mr.c:2320
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81a18170-ffffffff81a182fe: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d4f30)
Location: net/ipv6/ip6mr.c:2320
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff819d4f30-ffffffff819d50be: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a82bf0)
Location: net/ipv6/ip6mr.c:2320
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81a82bf0-ffffffff81a82d7e: ip6mr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc6_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a8f4c0)
Location: net/ipv6/ip6mr.c:2320
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:mr6_netlink_event
  - net/ipv6/ip6mr.c:_ip6mr_fill_mroute
```
**Symbols:**

```
ffffffff81a8f4c0-ffffffff81a8f64e: ip6mr_fill_mroute (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mr6_table *mrt</code> ➡️ <code>struct mr_table *mrt</code>
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
