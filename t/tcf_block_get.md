# Function: <code>tcf_block_get</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81801f60)
Location: net/sched/cls_api.c:264
Inline: False
```
**Symbols:**

```
ffffffff81801f60-ffffffff81801fcf: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81880290)
Location: net/sched/cls_api.c:323
Inline: False
```
**Symbols:**

```
ffffffff81880290-ffffffff818802ee: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d4e20)
Location: net/sched/cls_api.c:647
Inline: False
```
**Symbols:**

```
ffffffff818d4e20-ffffffff818d4e86: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ff790)
Location: net/sched/cls_api.c:1102
Inline: False
```
**Symbols:**

```
ffffffff818ff790-ffffffff818ff7f6: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1480
Inline: False
```
**Symbols:**

```
ffffffff81962d02-ffffffff81962d1d: tcf_block_get.cold (STB_LOCAL)
ffffffff8195fff0-ffffffff81960068: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819970e0)
Location: net/sched/cls_api.c:1394
Inline: False
```
**Symbols:**

```
ffffffff819970e0-ffffffff81997146: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6f460)
Location: net/sched/cls_api.c:1357
Inline: False
```
**Symbols:**

```
ffffffff81a6f460-ffffffff81a6f4c6: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a77e50)
Location: net/sched/cls_api.c:1358
Inline: False
```
**Symbols:**

```
ffffffff81a77e50-ffffffff81a77eb6: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a63a80)
Location: net/sched/cls_api.c:1358
Inline: False
```
**Symbols:**

```
ffffffff81a63a80-ffffffff81a63ae6: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b1ce00)
Location: net/sched/cls_api.c:1359
Inline: False
```
**Symbols:**

```
ffffffff81b1ce00-ffffffff81b1ce66: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca1050)
Location: net/sched/cls_api.c:1376
Inline: False
```
**Symbols:**

```
ffffffff81ca1050-ffffffff81ca10c2: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5d0a0)
Location: net/sched/cls_api.c:1378
Inline: False
```
**Symbols:**

```
ffffffff81e5d0a0-ffffffff81e5d112: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb9c50)
Location: net/sched/cls_api.c:1483
Inline: False
```
**Symbols:**

```
ffffffff81eb9c50-ffffffff81eb9cc2: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7cec0)
Location: net/sched/cls_api.c:1503
Inline: False
```
**Symbols:**

```
ffffffff81f7cec0-ffffffff81f7cf32: tcf_block_get (STB_GLOBAL)
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
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c441e0)
Location: net/sched/cls_api.c:1394
Inline: False
```
**Symbols:**

```
ffff800010c441e0-ffff800010c4427c: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d54d70)
Location: net/sched/cls_api.c:1394
Inline: False
```
**Symbols:**

```
c0d54d70-c0d54e20: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3f6a0)
Location: net/sched/cls_api.c:1394
Inline: False
```
**Symbols:**

```
c000000000d3f6a0-c000000000d3f72c: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b262c)
Location: net/sched/cls_api.c:1394
Inline: False
```
**Symbols:**

```
ffffffe0007b262c-ffffffe0007b268e: tcf_block_get (STB_GLOBAL)
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
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81936f50)
Location: net/sched/cls_api.c:1394
Inline: False
```
**Symbols:**

```
ffffffff81936f50-ffffffff81936fb6: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f0a50)
Location: net/sched/cls_api.c:1394
Inline: False
```
**Symbols:**

```
ffffffff818f0a50-ffffffff818f0ab6: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819880e0)
Location: net/sched/cls_api.c:1394
Inline: False
```
**Symbols:**

```
ffffffff819880e0-ffffffff81988146: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcf_block_get(struct tcf_block **p_block, struct tcf_proto **p_filter_chain, struct Qdisc *q, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819aa350)
Location: net/sched/cls_api.c:1394
Inline: False
```
**Symbols:**

```
ffffffff819aa350-ffffffff819aa3b6: tcf_block_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct Qdisc *q</code>
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
<code>struct netlink_ext_ack *extack</code>
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
