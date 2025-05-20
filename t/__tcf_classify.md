# Function: <code>__tcf_classify</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, const struct tcf_proto *orig_tp, struct tcf_result *res, bool compat_mode, u32 *last_executed_chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1525
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify_ingress
  - net/sched/cls_api.c:tcf_classify
```
**Symbols:**

```
ffffffff81a6bca0-ffffffff81a6bda7: __tcf_classify (STB_LOCAL)
ffffffff81a721b8-ffffffff81a721ea: __tcf_classify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, const struct tcf_proto *orig_tp, struct tcf_result *res, bool compat_mode, u32 *last_executed_chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1526
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify_ingress
```
**Symbols:**

```
ffffffff81a74530-ffffffff81a74637: __tcf_classify (STB_LOCAL)
ffffffff81c321e5-ffffffff81c32217: __tcf_classify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, const struct tcf_proto *orig_tp, struct tcf_result *res, bool compat_mode, u32 *last_executed_chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1526
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify_ingress
```
**Symbols:**

```
ffffffff81a5d0b0-ffffffff81a5d1b7: __tcf_classify (STB_LOCAL)
ffffffff81c244ce-ffffffff81c24500: __tcf_classify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, const struct tcf_proto *orig_tp, struct tcf_result *res, bool compat_mode, u32 *last_executed_chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1527
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
```
**Symbols:**

```
ffffffff81b16250-ffffffff81b16357: __tcf_classify (STB_LOCAL)
ffffffff81d390a7-ffffffff81d390d9: __tcf_classify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, const struct tcf_proto *orig_tp, struct tcf_result *res, bool compat_mode, u32 *last_executed_chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1544
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
```
**Symbols:**

```
ffffffff81c9daf0-ffffffff81c9dbfc: __tcf_classify (STB_LOCAL)
ffffffff81f058ac-ffffffff81f058d9: __tcf_classify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, const struct tcf_proto *orig_tp, struct tcf_result *res, bool compat_mode, u32 *last_executed_chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5a150)
Location: net/sched/cls_api.c:1546
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
```
**Symbols:**

```
ffffffff81e5a150-ffffffff81e5a2c0: __tcf_classify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, const struct tcf_proto *orig_tp, struct tcf_result *res, bool compat_mode, struct tcf_exts_miss_cookie_node *n, int act_index, u32 *last_executed_chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb6050)
Location: net/sched/cls_api.c:1652
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
```
**Symbols:**

```
ffffffff81eb6050-ffffffff81eb6249: __tcf_classify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __tcf_classify(struct sk_buff *skb, const struct tcf_proto *tp, const struct tcf_proto *orig_tp, struct tcf_result *res, bool compat_mode, struct tcf_exts_miss_cookie_node *n, int act_index, u32 *last_executed_chain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f78d60)
Location: net/sched/cls_api.c:1682
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
```
**Symbols:**

```
ffffffff81f78d60-ffffffff81f78f4a: __tcf_classify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>struct tcf_exts_miss_cookie_node *n</code>
</li>
<li>
<b>Param added. </b>
<code>int act_index</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, tp, orig_tp, res, compat_mode, last_executed_chain</code> ➡️ <code>skb, tp, orig_tp, res, compat_mode, n, act_index, last_executed_chain</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
