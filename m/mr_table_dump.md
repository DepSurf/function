# Function: <code>mr_table_dump</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81974300)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81974300-ffffffff8197454f: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff819dde30)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff819dde30-ffffffff819de074: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a14ed0)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81a14ed0-ffffffff81a15114: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b06890)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81b06890-ffffffff81b06ada: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b14a80)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81b14a80-ffffffff81b14cca: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81b02880)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81b02880-ffffffff81b02aca: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (0)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81d3ebc9-ffffffff81d3ebe5: mr_table_dump.cold (STB_LOCAL)
ffffffff81bc4850-ffffffff81bc4c4f: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (0)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81f0b509-ffffffff81f0b526: mr_table_dump.cold (STB_LOCAL)
ffffffff81d598a0-ffffffff81d59d20: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (0)
Location: net/ipv4/ipmr_base.c:298
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff820b2d96-ffffffff820b2dab: mr_table_dump.cold (STB_LOCAL)
ffffffff81f23d20-ffffffff81f24085: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (0)
Location: net/ipv4/ipmr_base.c:298
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff82133f3e-ffffffff82133f53: mr_table_dump.cold (STB_LOCAL)
ffffffff81f838b0-ffffffff81f83c15: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr_base.c (0)
Location: net/ipv4/ipmr_base.c:298
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff8221594a-ffffffff8221595f: mr_table_dump.cold (STB_LOCAL)
ffffffff82049f60-ffffffff8204a2c5: mr_table_dump (STB_GLOBAL)
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
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffff800010cd0e00)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffff800010cd0e00-ffff800010cd10d0: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (c0dda86c)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
c0dda86c-c0ddaad4: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (c000000000dee5a0)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
c000000000dee5a0-c000000000dee8ec: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffe0008221e6)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffe0008221e6-ffffffe0008223ce: mr_table_dump (STB_GLOBAL)
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
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff819b4560)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff819b4560-ffffffff819b47a4: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81970b90)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81970b90-ffffffff81970dd4: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a1ee00)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81a1ee00-ffffffff81a1f044: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mr_table_dump(struct mr_table *mrt, struct sk_buff *skb, struct netlink_callback *cb, int (*fill)(struct mr_table *, struct sk_buff *, u32, u32, struct mr_mfc *, int, int), spinlock_t *lock, struct fib_dump_filter *filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr_base.c (ffffffff81a2a2c0)
Location: net/ipv4/ipmr_base.c:289
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumproute
  - net/ipv4/ipmr_base.c:mr_rtm_dumproute
  - net/ipv6/ip6mr.c:ip6mr_rtm_dumproute
```
**Symbols:**

```
ffffffff81a2a2c0-ffffffff81a2a504: mr_table_dump (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
