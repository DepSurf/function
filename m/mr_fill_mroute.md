# Function: <code>mr_fill_mroute</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff819443e0)
Location: net/ipv4/ipmr_base.c:207
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff819443e0-ffffffff81944618: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81974680)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81974680-ffffffff819748b8: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (0)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff819dec8f-ffffffff819deca9: mr_fill_mroute.cold (STB_LOCAL)
ffffffff819de1c0-ffffffff819de3f9: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a15260)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a15260-ffffffff81a15499: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b06250)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
**Symbols:**

```
ffffffff81b06250-ffffffff81b06489: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b14440)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
**Symbols:**

```
ffffffff81b14440-ffffffff81b14679: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b02240)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81b02240-ffffffff81b02473: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81bc40e0)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81bc40e0-ffffffff81bc43e5: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81d58f60)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81d58f60-ffffffff81d59294: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81f23560)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81f23560-ffffffff81f23885: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81f830b0)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81f830b0-ffffffff81f833d2: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff82049730)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_cache_resolve
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff82049730-ffffffff82049a52: mr_fill_mroute (STB_GLOBAL)
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
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffff800010cd09c8)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffff800010cd09c8-ffff800010cd0c1c: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (c0ddad24)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
c0ddad24-c0ddafb0: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (c000000000deeb30)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
c000000000deeb30-c000000000deeee4: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffe000822516)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffe000822516-ffffffe0008226f0: mr_fill_mroute (STB_GLOBAL)
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
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff819b48f0)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff819b48f0-ffffffff819b4b29: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81970f20)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81970f20-ffffffff81971159: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a1f190)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a1f190-ffffffff81a1f3c9: mr_fill_mroute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mr_fill_mroute(struct mr_table *mrt, struct sk_buff *skb, struct mr_mfc *c, struct rtmsg *rtm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a2a660)
Location: net/ipv4/ipmr_base.c:208
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_fill_mroute
  - net/ipv4/ipmr.c:ipmr_get_route
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_fill_mroute
  - net/ipv6/ip6mr.c:ip6mr_get_route
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a2a660-ffffffff81a2a899: mr_fill_mroute (STB_GLOBAL)
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
