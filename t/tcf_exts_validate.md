# Function: <code>tcf_exts_validate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81745ba0)
Location: net/sched/cls_api.c:518
Inline: False
```
**Symbols:**

```
ffffffff81745ba0-ffffffff81745c5b: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff817b2d90)
Location: net/sched/cls_api.c:554
Inline: True
```
**Symbols:**

```
ffffffff817b2d90-ffffffff817b2e95: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff817e2610)
Location: net/sched/cls_api.c:565
Inline: True
```
**Symbols:**

```
ffffffff817e2610-ffffffff817e2715: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81801b50)
Location: net/sched/cls_api.c:853
Inline: False
```
**Symbols:**

```
ffffffff81801b50-ffffffff81801c43: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187fbb0)
Location: net/sched/cls_api.c:1086
Inline: False
```
**Symbols:**

```
ffffffff8187fbb0-ffffffff8187fcb1: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d2880)
Location: net/sched/cls_api.c:1578
Inline: False
```
**Symbols:**

```
ffffffff818d2880-ffffffff818d299a: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fdd40)
Location: net/sched/cls_api.c:2377
Inline: False
```
**Symbols:**

```
ffffffff818fdd40-ffffffff818fde21: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195d6e0)
Location: net/sched/cls_api.c:3037
Inline: False
```
**Symbols:**

```
ffffffff8195d6e0-ffffffff8195d7bd: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81993ca0)
Location: net/sched/cls_api.c:3009
Inline: False
```
**Symbols:**

```
ffffffff81993ca0-ffffffff81993d7d: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6bb00)
Location: net/sched/cls_api.c:3045
Inline: False
```
**Symbols:**

```
ffffffff81a6bb00-ffffffff81a6bbdd: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a742f0)
Location: net/sched/cls_api.c:3036
Inline: False
```
**Symbols:**

```
ffffffff81a742f0-ffffffff81a74463: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5ce40)
Location: net/sched/cls_api.c:3037
Inline: False
```
**Symbols:**

```
ffffffff81a5ce40-ffffffff81a5cff0: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b15ff0)
Location: net/sched/cls_api.c:3036
Inline: False
```
**Symbols:**

```
ffffffff81b15ff0-ffffffff81b16185: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9d7e0)
Location: net/sched/cls_api.c:3110
Inline: False
```
**Symbols:**

```
ffffffff81c9d7e0-ffffffff81c9d807: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e59dd0)
Location: net/sched/cls_api.c:3110
Inline: False
```
**Symbols:**

```
ffffffff81e59dd0-ffffffff81e59df7: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb57c0)
Location: net/sched/cls_api.c:3317
Inline: False
```
**Symbols:**

```
ffffffff81eb57c0-ffffffff81eb57e7: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f784d0)
Location: net/sched/cls_api.c:3373
Inline: False
```
**Symbols:**

```
ffffffff81f784d0-ffffffff81f784f7: tcf_exts_validate (STB_GLOBAL)
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
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c400e0)
Location: net/sched/cls_api.c:3009
Inline: False
```
**Symbols:**

```
ffff800010c400e0-ffff800010c40220: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d52048)
Location: net/sched/cls_api.c:3009
Inline: False
```
**Symbols:**

```
c0d52048-c0d52184: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3ad20)
Location: net/sched/cls_api.c:3009
Inline: False
```
**Symbols:**

```
c000000000d3ad20-c000000000d3ae90: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007afc34)
Location: net/sched/cls_api.c:3009
Inline: False
```
**Symbols:**

```
ffffffe0007afc34-ffffffe0007afcfe: tcf_exts_validate (STB_GLOBAL)
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
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81933b10)
Location: net/sched/cls_api.c:3009
Inline: False
```
**Symbols:**

```
ffffffff81933b10-ffffffff81933bed: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ed610)
Location: net/sched/cls_api.c:3009
Inline: False
```
**Symbols:**

```
ffffffff818ed610-ffffffff818ed6ed: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81984ca0)
Location: net/sched/cls_api.c:3009
Inline: False
```
**Symbols:**

```
ffffffff81984ca0-ffffffff81984d7d: tcf_exts_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcf_exts_validate(struct net *net, struct tcf_proto *tp, struct nlattr **tb, struct nlattr *rate_tlv, struct tcf_exts *exts, bool ovr, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a7490)
Location: net/sched/cls_api.c:3009
Inline: False
```
**Symbols:**

```
ffffffff819a7490-ffffffff819a756d: tcf_exts_validate (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
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
<li>
<b>Param reordered. </b>
<code>net, tp, tb, rate_tlv, exts, ovr, extack</code> ➡️ <code>net, tp, tb, rate_tlv, exts, ovr, rtnl_held, extack</code>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool ovr</code>
</li>
<li>
<b>Param removed. </b>
<code>bool rtnl_held</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, tp, tb, rate_tlv, exts, ovr, rtnl_held, extack</code> ➡️ <code>net, tp, tb, rate_tlv, exts, flags, extack</code>
</li>
</ul>
</details>
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
