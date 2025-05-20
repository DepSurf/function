# Function: <code>tc_chain_fill_node</code>

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
int tc_chain_fill_node(struct tcf_chain *chain, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fea50)
Location: net/sched/cls_api.c:2031
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
```
**Symbols:**

```
ffffffff818fea50-ffffffff818fec05: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2641
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff8195e450-ffffffff8195e609: tc_chain_fill_node (STB_LOCAL)
ffffffff81962ca6-ffffffff81962cc1: tc_chain_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81994d20)
Location: net/sched/cls_api.c:2605
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff81994d20-ffffffff81994ed9: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6da50)
Location: net/sched/cls_api.c:2641
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff81a6da50-ffffffff81a6dc09: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2642
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff81a76410-ffffffff81a765de: tc_chain_fill_node (STB_LOCAL)
ffffffff81c3222f-ffffffff81c32247: tc_chain_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2643
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff81a5e310-ffffffff81a5e4d9: tc_chain_fill_node (STB_LOCAL)
ffffffff81c24518-ffffffff81c24530: tc_chain_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2643
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff81b174f0-ffffffff81b176b9: tc_chain_fill_node (STB_LOCAL)
ffffffff81d39127-ffffffff81d3913f: tc_chain_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2662
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff81c9f2a0-ffffffff81c9f475: tc_chain_fill_node (STB_LOCAL)
ffffffff81f05966-ffffffff81f0597e: tc_chain_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5b4d0)
Location: net/sched/cls_api.c:2666
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff81e5b4d0-ffffffff81e5b6bd: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb7bf0)
Location: net/sched/cls_api.c:2822
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff81eb7bf0-ffffffff81eb7e18: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7ac00)
Location: net/sched/cls_api.c:2875
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff81f7ac00-ffffffff81f7ae28: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (ffff800010c41890)
Location: net/sched/cls_api.c:2605
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffff800010c41890-ffff800010c41a50: tc_chain_fill_node.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d536d0)
Location: net/sched/cls_api.c:2605
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
c0d536d0-c0d53884: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3d530)
Location: net/sched/cls_api.c:2605
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
c000000000d3d530-c000000000d3d788: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b1276)
Location: net/sched/cls_api.c:2605
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffe0007b1276-ffffffe0007b13b6: tc_chain_fill_node (STB_LOCAL)
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
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81934b90)
Location: net/sched/cls_api.c:2605
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff81934b90-ffffffff81934d49: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ee690)
Location: net/sched/cls_api.c:2605
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff818ee690-ffffffff818ee849: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81985d20)
Location: net/sched/cls_api.c:2605
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff81985d20-ffffffff81985ed9: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tc_chain_fill_node(const struct tcf_proto_ops *tmplt_ops, void *tmplt_priv, u32 chain_index, struct net *net, struct sk_buff *skb, struct tcf_block *block, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a8d20)
Location: net/sched/cls_api.c:2605
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:__tcf_chain_put
```
**Symbols:**

```
ffffffff819a8d20-ffffffff819a8ed9: tc_chain_fill_node (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct tcf_proto_ops *tmplt_ops</code>
</li>
<li>
<b>Param added. </b>
<code>void *tmplt_priv</code>
</li>
<li>
<b>Param added. </b>
<code>u32 chain_index</code>
</li>
<li>
<b>Param removed. </b>
<code>struct tcf_chain *chain</code>
</li>
<li>
<b>Param reordered. </b>
<code>chain, net, skb, block, portid, seq, flags, event</code> ➡️ <code>tmplt_ops, tmplt_priv, chain_index, net, skb, block, portid, seq, flags, event</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
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
