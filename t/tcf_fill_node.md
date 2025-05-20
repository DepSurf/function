# Function: <code>tcf_fill_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, long unsigned int fh, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81745fa0)
Location: net/sched/cls_api.c:354
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81745fa0-ffffffff81746127: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, long unsigned int fh, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff817b2fb0)
Location: net/sched/cls_api.c:383
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff817b2fb0-ffffffff817b3137: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, long unsigned int fh, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff817e2830)
Location: net/sched/cls_api.c:389
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff817e2830-ffffffff817e29b7: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, long unsigned int fh, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81802110)
Location: net/sched/cls_api.c:648
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81802110-ffffffff818022cb: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81880360)
Location: net/sched/cls_api.c:595
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81880360-ffffffff81880526: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d30c0)
Location: net/sched/cls_api.c:941
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff818d30c0-ffffffff818d32a5: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fe510)
Location: net/sched/cls_api.c:1387
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff818fe510-ffffffff818fe6ec: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1836
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff8195f210-ffffffff8195f400: tcf_fill_node (STB_LOCAL)
ffffffff81962cd4-ffffffff81962cef: tcf_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819955f0)
Location: net/sched/cls_api.c:1781
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff819955f0-ffffffff819957e0: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool terse_dump, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6d560)
Location: net/sched/cls_api.c:1794
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81a6d560-ffffffff81a6d772: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool terse_dump, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1796
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81a75f10-ffffffff81a76136: tcf_fill_node (STB_LOCAL)
ffffffff81c32217-ffffffff81c3222f: tcf_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool terse_dump, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1797
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81a5df70-ffffffff81a5e195: tcf_fill_node (STB_LOCAL)
ffffffff81c24500-ffffffff81c24518: tcf_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool terse_dump, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1795
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81b17130-ffffffff81b17355: tcf_fill_node (STB_LOCAL)
ffffffff81d390f6-ffffffff81d3910e: tcf_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool terse_dump, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1814
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81c9ecf0-ffffffff81c9ef27: tcf_fill_node (STB_LOCAL)
ffffffff81f05935-ffffffff81f0594d: tcf_fill_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool terse_dump, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5d790)
Location: net/sched/cls_api.c:1816
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81e5d790-ffffffff81e5d9df: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool terse_dump, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb7740)
Location: net/sched/cls_api.c:1964
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81eb7740-ffffffff81eb79d6: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool terse_dump, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7a4f0)
Location: net/sched/cls_api.c:2014
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tfilter_del_notify
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81f7a4f0-ffffffff81f7a786: tcf_fill_node (STB_LOCAL)
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
In net/sched/cls_api.c (ffff800010c42270)
Location: net/sched/cls_api.c:1781
Inline: True
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffff800010c42270-ffff800010c4246c: tcf_fill_node.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d55230)
Location: net/sched/cls_api.c:1781
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
c0d55230-c0d55438: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3fcf0)
Location: net/sched/cls_api.c:1781
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
c000000000d3fcf0-c000000000d3ffb0: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b29b4)
Location: net/sched/cls_api.c:1781
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffe0007b29b4-ffffffe0007b2b1a: tcf_fill_node (STB_LOCAL)
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
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81935460)
Location: net/sched/cls_api.c:1781
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff81935460-ffffffff81935650: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818eef60)
Location: net/sched/cls_api.c:1781
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff818eef60-ffffffff818ef150: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819865f0)
Location: net/sched/cls_api.c:1781
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff819865f0-ffffffff819867e0: tcf_fill_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcf_fill_node(struct net *net, struct sk_buff *skb, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, u32 portid, u32 seq, u16 flags, int event, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819aa850)
Location: net/sched/cls_api.c:1781
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_node_dump
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
```
**Symbols:**

```
ffffffff819aa850-ffffffff819aaa40: tcf_fill_node (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct Qdisc *q</code>
</li>
<li>
<b>Param added. </b>
<code>u32 parent</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, skb, tp, fh, portid, seq, flags, event</code> ➡️ <code>net, skb, tp, q, parent, fh, portid, seq, flags, event</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int fh</code> ➡️ <code>void *fh</code>
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
<code>struct tcf_block *block</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, skb, tp, q, parent, fh, portid, seq, flags, event</code> ➡️ <code>net, skb, tp, block, q, parent, fh, portid, seq, flags, event</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rtnl_held</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool terse_dump</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, skb, tp, block, q, parent, fh, portid, seq, flags, event, rtnl_held</code> ➡️ <code>net, skb, tp, block, q, parent, fh, portid, seq, flags, event, terse_dump, rtnl_held</code>
</li>
</ul>
</details>
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
