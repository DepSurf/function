# Function: <code>skb_ext_add</code>

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
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189d1c0)
Location: net/core/skbuff.c:5656
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
```
**Symbols:**

```
ffffffff8189d1c0-ffffffff8189d32e: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e7a40)
Location: net/core/skbuff.c:6016
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
```
**Symbols:**

```
ffffffff818e7a40-ffffffff818e7baf: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81919f10)
Location: net/core/skbuff.c:6033
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
```
**Symbols:**

```
ffffffff81919f10-ffffffff8191a086: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f42c0)
Location: net/core/skbuff.c:6176
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify_ingress
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff819f42c0-ffffffff819f4481: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f42e0)
Location: net/core/skbuff.c:6313
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify_ingress
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff819f42e0-ffffffff819f44a1: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819da4a0)
Location: net/core/skbuff.c:6401
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify_ingress
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
  - net/mptcp/subflow.c:subflow_add_reset_reason
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff819da4a0-ffffffff819da65c: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6476
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
  - net/mptcp/subflow.c:subflow_add_reset_reason
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81d3542b-ffffffff81d35444: skb_ext_add.cold (STB_LOCAL)
ffffffff81a8a4b0-ffffffff81a8a747: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6389
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
  - net/mptcp/subflow.c:subflow_add_reset_reason
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81f01947-ffffffff81f01960: skb_ext_add.cold (STB_LOCAL)
ffffffff81bff910-ffffffff81bffbb6: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6590
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
  - net/mptcp/subflow.c:subflow_add_reset_reason
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff820aad7f-ffffffff820aada0: skb_ext_add.cold (STB_LOCAL)
ffffffff81daedc0-ffffffff81daef2c: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6635
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
  - net/mptcp/subflow.c:subflow_add_reset_reason
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff8212c381-ffffffff8212c3a2: skb_ext_add.cold (STB_LOCAL)
ffffffff81e1efb0-ffffffff81e1f11c: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6782
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
  - net/mptcp/subflow.c:subflow_add_reset_reason
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff8220e057-ffffffff8220e078: skb_ext_add.cold (STB_LOCAL)
ffffffff81edc610-ffffffff81edc77c: skb_ext_add (STB_GLOBAL)
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
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb2648)
Location: net/core/skbuff.c:6033
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
```
**Symbols:**

```
ffff800010bb2648-ffff800010bb27d8: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd08b8)
Location: net/core/skbuff.c:6033
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
```
**Symbols:**

```
c0cd08b8-c0cd0a18: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8a1c0)
Location: net/core/skbuff.c:6033
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
```
**Symbols:**

```
c000000000c8a1c0-c000000000c8a3e0: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000744594)
Location: net/core/skbuff.c:6033
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
```
**Symbols:**

```
ffffffe000744594-ffffffe0007446fe: skb_ext_add (STB_GLOBAL)
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
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b9f10)
Location: net/core/skbuff.c:6033
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
```
**Symbols:**

```
ffffffff818b9f10-ffffffff818ba086: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81873e60)
Location: net/core/skbuff.c:6033
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
```
**Symbols:**

```
ffffffff81873e60-ffffffff81873fd6: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190af10)
Location: net/core/skbuff.c:6033
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
```
**Symbols:**

```
ffffffff8190af10-ffffffff8190b086: skb_ext_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *skb_ext_add(struct sk_buff *skb, enum skb_ext_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192c010)
Location: net/core/skbuff.c:6033
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_classify
  - net/xfrm/xfrm_input.c:secpath_set
  - net/xfrm/xfrm_input.c:secpath_set
```
**Symbols:**

```
ffffffff8192c010-ffffffff8192c186: skb_ext_add (STB_GLOBAL)
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
