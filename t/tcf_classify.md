# Function: <code>tcf_classify</code>

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
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81801960)
Location: net/sched/cls_api.c:309
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81801960-ffffffff81801aa6: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8187f910)
Location: net/sched/cls_api.c:485
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff8187f910-ffffffff8187fa5b: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:830
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff818d507c-ffffffff818d50ae: tcf_classify.cold.43 (STB_LOCAL)
ffffffff818d25f0-ffffffff818d271a: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1277
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81901be4-ffffffff81901c14: tcf_classify.cold.65 (STB_LOCAL)
ffffffff818fdb90-ffffffff818fdc8b: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1636
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81962c48-ffffffff81962c78: tcf_classify.cold (STB_LOCAL)
ffffffff8195d530-ffffffff8195d62b: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1562
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81999841-ffffffff81999874: tcf_classify.cold (STB_LOCAL)
ffffffff81993aa0-ffffffff81993bd2: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6bdb0)
Location: net/sched/cls_api.c:1579
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81a6bdb0-ffffffff81a6bdfc: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a74640)
Location: net/sched/cls_api.c:1580
Inline: True
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81a74640-ffffffff81a7468c: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5d1c0)
Location: net/sched/cls_api.c:1580
Inline: True
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81a5d1c0-ffffffff81a5d20c: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_block *block, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b16850)
Location: net/sched/cls_api.c:1581
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81b16850-ffffffff81b169d1: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_block *block, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9df60)
Location: net/sched/cls_api.c:1598
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/cls_api.c:tcf_qevent_handle
```
**Symbols:**

```
ffffffff81c9df60-ffffffff81c9e100: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_block *block, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5a670)
Location: net/sched/cls_api.c:1600
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/cls_api.c:tcf_qevent_handle
```
**Symbols:**

```
ffffffff81e5a670-ffffffff81e5a810: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_block *block, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb6260)
Location: net/sched/cls_api.c:1734
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/sched/cls_api.c:tcf_qevent_handle
```
**Symbols:**

```
ffffffff81eb6260-ffffffff81eb64a6: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_block *block, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f78f60)
Location: net/sched/cls_api.c:1775
Inline: False
Direct callers:
  - net/core/dev.c:tc_run
  - net/sched/cls_api.c:tcf_qevent_handle
```
**Symbols:**

```
ffffffff81f78f60-ffffffff81f791be: tcf_classify (STB_GLOBAL)
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
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c3fe98)
Location: net/sched/cls_api.c:1562
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffff800010c3fe98-ffff800010c40020: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d51dfc)
Location: net/sched/cls_api.c:1562
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
c0d51dfc-c0d51f80: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3a9b0)
Location: net/sched/cls_api.c:1562
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
c000000000d3a9b0-c000000000d3ac04: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007afa4e)
Location: net/sched/cls_api.c:1562
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffe0007afa4e-ffffffe0007afb92: tcf_classify (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1562
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff819396b1-ffffffff819396e4: tcf_classify.cold (STB_LOCAL)
ffffffff81933910-ffffffff81933a42: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1562
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff818f31b1-ffffffff818f31e4: tcf_classify.cold (STB_LOCAL)
ffffffff818ed410-ffffffff818ed542: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1562
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff8198a841-ffffffff8198a874: tcf_classify.cold (STB_LOCAL)
ffffffff81984aa0-ffffffff81984bd2: tcf_classify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, struct tcf_result *res, bool compat_mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1562
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff819ad080-ffffffff819ad0b3: tcf_classify.cold (STB_LOCAL)
ffffffff819a7290-ffffffff819a73c2: tcf_classify (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct tcf_block *block</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, tp, res, compat_mode</code> ➡️ <code>skb, block, tp, res, compat_mode</code>
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
