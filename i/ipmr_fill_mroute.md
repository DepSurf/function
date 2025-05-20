# Function: <code>ipmr_fill_mroute</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff817a86d0)
Location: net/ipv4/ipmr.c:2260
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
```
**Symbols:**

```
ffffffff817a86d0-ffffffff817a8884: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81815e00)
Location: net/ipv4/ipmr.c:2192
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:mroute_netlink_event
```
**Symbols:**

```
ffffffff81815e00-ffffffff81815fb2: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818475b0)
Location: net/ipv4/ipmr.c:2203
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:mroute_netlink_event
```
**Symbols:**

```
ffffffff818475b0-ffffffff81847762: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8186a1b0)
Location: net/ipv4/ipmr.c:2256
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
```
**Symbols:**

```
ffffffff8186a1b0-ffffffff8186a351: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818ea930)
Location: net/ipv4/ipmr.c:2421
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
```
**Symbols:**

```
ffffffff818ea930-ffffffff818eaad1: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819410d0)
Location: net/ipv4/ipmr.c:2295
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff819410d0-ffffffff81941272: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81971760)
Location: net/ipv4/ipmr.c:2308
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff81971760-ffffffff819718ff: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:2320
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff819daed0-ffffffff819db06e: ipmr_fill_mroute (STB_LOCAL)
ffffffff819ddd14-ffffffff819ddd2f: ipmr_fill_mroute.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a11db0)
Location: net/ipv4/ipmr.c:2321
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff81a11db0-ffffffff81a11f4c: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b033b0)
Location: net/ipv4/ipmr.c:2289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff81b033b0-ffffffff81b0354e: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b11510)
Location: net/ipv4/ipmr.c:2296
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff81b11510-ffffffff81b116ae: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81aff140)
Location: net/ipv4/ipmr.c:2296
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff81aff140-ffffffff81aff2dc: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bc0bd0)
Location: net/ipv4/ipmr.c:2298
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff81bc0bd0-ffffffff81bc0d6c: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d55500)
Location: net/ipv4/ipmr.c:2292
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff81d55500-ffffffff81d556b6: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f1f830)
Location: net/ipv4/ipmr.c:2299
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff81f1f830-ffffffff81f1f9e6: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f7f330)
Location: net/ipv4/ipmr.c:2314
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff81f7f330-ffffffff81f7f4e4: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff820459b0)
Location: net/ipv4/ipmr.c:2312
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff820459b0-ffffffff82045b64: ipmr_fill_mroute (STB_LOCAL)
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
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010cca780)
Location: net/ipv4/ipmr.c:2321
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffff800010cca780-ffff800010cca944: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd63b4)
Location: net/ipv4/ipmr.c:2321
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
c0dd63b4-c0dd6570: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000de9980)
Location: net/ipv4/ipmr.c:2321
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
c000000000de9980-c000000000de9bdc: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081f7ec)
Location: net/ipv4/ipmr.c:2321
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffe00081f7ec-ffffffe00081f932: ipmr_fill_mroute (STB_LOCAL)
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
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819b16d0)
Location: net/ipv4/ipmr.c:2321
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff819b16d0-ffffffff819b186c: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196dd00)
Location: net/ipv4/ipmr.c:2321
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff8196dd00-ffffffff8196de9c: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a1bf70)
Location: net/ipv4/ipmr.c:2321
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff81a1bf70-ffffffff81a1c10c: ipmr_fill_mroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipmr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, u32 portid, u32 seq, struct mfc_cache *c, int cmd, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a26ec0)
Location: net/ipv4/ipmr.c:2321
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_getroute
  - net/ipv4/ipmr.c:mroute_netlink_event
  - net/ipv4/ipmr.c:_ipmr_fill_mroute
```
**Symbols:**

```
ffffffff81a26ec0-ffffffff81a2705c: ipmr_fill_mroute (STB_LOCAL)
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
