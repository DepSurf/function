# Function: <code>mr_rtm_dumproute</code>

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
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff819441b0)
Location: net/ipv4/ipmr_base.c:270
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff819441b0-ffffffff8194437e: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81974550)
Location: net/ipv4/ipmr_base.c:346
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81974550-ffffffff8197461d: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff819de080)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff819de080-ffffffff819de15f: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a15120)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81a15120-ffffffff81a151ff: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b06ae0)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81b06ae0-ffffffff81b06bc1: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b14cd0)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81b14cd0-ffffffff81b14db6: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b02ad0)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81b02ad0-ffffffff81b02bb6: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (0)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81d3ebe5-ffffffff81d3ec01: mr_rtm_dumproute.cold (STB_LOCAL)
ffffffff81bc4c50-ffffffff81bc4d49: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (0)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81f0b526-ffffffff81f0b54a: mr_rtm_dumproute.cold (STB_LOCAL)
ffffffff81d59d20-ffffffff81d59e38: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (0)
Location: net/ipv4/ipmr_base.c:353
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff820b2dab-ffffffff820b2dcf: mr_rtm_dumproute.cold (STB_LOCAL)
ffffffff81f240a0-ffffffff81f241b8: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (0)
Location: net/ipv4/ipmr_base.c:353
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff82133f53-ffffffff82133f77: mr_rtm_dumproute.cold (STB_LOCAL)
ffffffff81f83c30-ffffffff81f83d48: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (0)
Location: net/ipv4/ipmr_base.c:353
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff8221595f-ffffffff82215983: mr_rtm_dumproute.cold (STB_LOCAL)
ffffffff8204a2e0-ffffffff8204a3f8: mr_rtm_dumproute (STB_GLOBAL)
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
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffff800010cd10d0)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffff800010cd10d0-ffff800010cd11dc: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (c0ddaad4)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
c0ddaad4-c0ddabd8: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (c000000000dee8f0)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
c000000000dee8f0-c000000000deea94: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffe0008223ce)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffe0008223ce-ffffffe00082249c: mr_rtm_dumproute (STB_GLOBAL)
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
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff819b47b0)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff819b47b0-ffffffff819b488f: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81970de0)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81970de0-ffffffff81970ebf: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a1f050)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81a1f050-ffffffff81a1f12f: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mr_rtm_dumproute(struct sk_buff *skb, struct netlink_callback *cb, struct mr_table * (*iter)(struct net *, struct mr_table *), int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a2a570)
Location: net/ipv4/ipmr_base.c:344
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81a2a570-ffffffff81a2a65c: mr_rtm_dumproute (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fib_dump_filter *filter</code>
</li>
</ul>
</details>
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
