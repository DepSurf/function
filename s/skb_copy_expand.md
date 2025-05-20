# Function: <code>skb_copy_expand</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81707400)
Location: net/core/skbuff.c:1306
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
```
**Symbols:**

```
ffffffff81707400-ffffffff817074e2: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176d6b0)
Location: net/core/skbuff.c:1311
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
```
**Symbols:**

```
ffffffff8176d6b0-ffffffff8176d78b: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179a840)
Location: net/core/skbuff.c:1311
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
```
**Symbols:**

```
ffffffff8179a840-ffffffff8179a91b: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817ba7e0)
Location: net/core/skbuff.c:1321
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
```
**Symbols:**

```
ffffffff817ba7e0-ffffffff817ba8bb: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81832bd0)
Location: net/core/skbuff.c:1567
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
```
**Symbols:**

```
ffffffff81832bd0-ffffffff81832cab: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187d0f0)
Location: net/core/skbuff.c:1569
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8187d0f0-ffffffff8187d1c9: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189dcf0)
Location: net/core/skbuff.c:1579
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8189dcf0-ffffffff8189ddbd: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e84b0)
Location: net/core/skbuff.c:1738
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff818e84b0-ffffffff818e8581: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191a6f0)
Location: net/core/skbuff.c:1738
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8191a6f0-ffffffff8191a7c1: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ecc10)
Location: net/core/skbuff.c:1737
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_broadcast
  - net/core/skbuff.c:skb_cow_data
```
**Symbols:**

```
ffffffff819ecc10-ffffffff819ecce1: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ec8d0)
Location: net/core/skbuff.c:1748
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_broadcast
  - net/core/skbuff.c:skb_cow_data
```
**Symbols:**

```
ffffffff819ec8d0-ffffffff819ec9a1: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d2dc0)
Location: net/core/skbuff.c:1790
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - net/core/skbuff.c:skb_cow_data
```
**Symbols:**

```
ffffffff819d2dc0-ffffffff819d2e90: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1862
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - net/core/skbuff.c:skb_cow_data
```
**Symbols:**

```
ffffffff81d351ae-ffffffff81d351c1: skb_copy_expand.cold (STB_LOCAL)
ffffffff81a82a70-ffffffff81a82b6e: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1887
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
  - net/core/skbuff.c:skb_cow_data
```
**Symbols:**

```
ffffffff81f0170b-ffffffff81f0171e: skb_copy_expand.cold (STB_LOCAL)
ffffffff81bf7460-ffffffff81bf755c: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da64c0)
Location: net/core/skbuff.c:2090
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81da64c0-ffffffff81da65ce: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e155b0)
Location: net/core/skbuff.c:2254
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81e155b0-ffffffff81e156c4: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed2950)
Location: net/core/skbuff.c:2342
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81ed2950-ffffffff81ed2a64: skb_copy_expand (STB_GLOBAL)
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
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb4a30)
Location: net/core/skbuff.c:1738
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffff800010bb4a30-ffff800010bb4b2c: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd1580)
Location: net/core/skbuff.c:1738
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
c0cd1580-c0cd165c: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8b500)
Location: net/core/skbuff.c:1738
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
c000000000c8b500-c000000000c8b640: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000743a1c)
Location: net/core/skbuff.c:1738
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffe000743a1c-ffffffe000743af4: skb_copy_expand (STB_GLOBAL)
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
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ba6f0)
Location: net/core/skbuff.c:1738
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff818ba6f0-ffffffff818ba7c1: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81874640)
Location: net/core/skbuff.c:1738
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81874640-ffffffff81874711: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190b6f0)
Location: net/core/skbuff.c:1738
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - net/netfilter/nfnetlink_queue.c:nfqnl_recv_verdict
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8190b6f0-ffffffff8190b7c1: skb_copy_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *skb_copy_expand(const struct sk_buff *skb, int newheadroom, int newtailroom, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192c810)
Location: net/core/skbuff.c:1738
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_cow_data
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff8192c810-ffffffff8192c8e1: skb_copy_expand (STB_GLOBAL)
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
