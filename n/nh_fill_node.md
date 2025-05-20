# Function: <code>nh_fill_node</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819d36b0)
Location: net/ipv4/nexthop.c:208
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff819d36b0-ffffffff819d391c: nh_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0a220)
Location: net/ipv4/nexthop.c:208
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff81a0a220-ffffffff81a0a48c: nh_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afad80)
Location: net/ipv4/nexthop.c:227
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff81afad80-ffffffff81afb063: nh_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b08450)
Location: net/ipv4/nexthop.c:355
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff81b08450-ffffffff81b08733: nh_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af6d80)
Location: net/ipv4/nexthop.c:692
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff81af6d80-ffffffff81af709d: nh_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:692
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff81bb66b0-ffffffff81bb6a39: nh_fill_node (STB_LOCAL)
ffffffff81d3e11a-ffffffff81d3e1b9: nh_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:693
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff81d4a2e0-ffffffff81d4a648: nh_fill_node (STB_LOCAL)
ffffffff81f0a9f8-ffffffff81f0aa97: nh_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:693
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff81f13980-ffffffff81f13ce8: nh_fill_node (STB_LOCAL)
ffffffff820b22ad-ffffffff820b234c: nh_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:693
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff81f73650-ffffffff81f739b8: nh_fill_node (STB_LOCAL)
ffffffff8213345d-ffffffff821334fc: nh_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:693
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff82039e40-ffffffff8203a1a8: nh_fill_node (STB_LOCAL)
ffffffff82214e69-ffffffff82214f08: nh_fill_node.cold (STB_LOCAL)
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
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc3710)
Location: net/ipv4/nexthop.c:208
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffff800010cc3710-ffff800010cc3994: nh_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dceee4)
Location: net/ipv4/nexthop.c:208
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
c0dceee4-c0dcf17c: nh_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000ddf390)
Location: net/ipv4/nexthop.c:208
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
c000000000ddf390-c000000000ddf6dc: nh_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe0008189d0)
Location: net/ipv4/nexthop.c:208
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffe0008189d0-ffffffe000818bb4: nh_fill_node (STB_LOCAL)
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
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819a9fc0)
Location: net/ipv4/nexthop.c:208
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff819a9fc0-ffffffff819aa22c: nh_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81963a80)
Location: net/ipv4/nexthop.c:208
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff81963a80-ffffffff81963cec: nh_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a14860)
Location: net/ipv4/nexthop.c:208
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff81a14860-ffffffff81a14acc: nh_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nh_fill_node(struct sk_buff *skb, struct nexthop *nh, int event, u32 portid, u32 seq, unsigned int nlflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a1f270)
Location: net/ipv4/nexthop.c:208
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:rtm_dump_nexthop
  - net/ipv4/nexthop.c:rtm_get_nexthop
  - net/ipv4/nexthop.c:nexthop_notify
```
**Symbols:**

```
ffffffff81a1f270-ffffffff81a1f4dc: nh_fill_node (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
