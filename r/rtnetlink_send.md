# Function: <code>rtnetlink_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8172fa00)
Location: net/core/rtnetlink.c:620
Inline: False
Direct callers:
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tca_action_flush
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tc_ctl_action
```
**Symbols:**

```
ffffffff8172fa00-ffffffff8172fa6f: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8179a150)
Location: net/core/rtnetlink.c:642
Inline: False
Direct callers:
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff8179a150-ffffffff8179a1bf: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817c7ef0)
Location: net/core/rtnetlink.c:643
Inline: False
Direct callers:
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff817c7ef0-ffffffff817c7f5f: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff817e67d0)
Location: net/core/rtnetlink.c:645
Inline: False
Direct callers:
  - net/sched/sch_api.c:tclass_notify
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff817e67d0-ffffffff817e683f: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818616b0)
Location: net/core/rtnetlink.c:618
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tc_ctl_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff818616b0-ffffffff81861729: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818ad270)
Location: net/core/rtnetlink.c:701
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tc_ctl_action
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff818ad270-ffffffff818ad2e9: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818d14d0)
Location: net/core/rtnetlink.c:711
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff818d14d0-ffffffff818d1549: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8191e390)
Location: net/core/rtnetlink.c:706
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff8191e390-ffffffff8191e40e: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819509c0)
Location: net/core/rtnetlink.c:706
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff819509c0-ffffffff81950a3e: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a217d0)
Location: net/core/rtnetlink.c:706
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff81a217d0-ffffffff81a2188f: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a21c10)
Location: net/core/rtnetlink.c:708
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff81a21c10-ffffffff81a21ccf: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a08f50)
Location: net/core/rtnetlink.c:710
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff81a08f50-ffffffff81a0900f: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81abb4b0)
Location: net/core/rtnetlink.c:710
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff81abb4b0-ffffffff81abb4d3: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c35cd0)
Location: net/core/rtnetlink.c:747
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff81c35cd0-ffffffff81c35d05: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de9270)
Location: net/core/rtnetlink.c:748
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tcf_del_notify
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff81de9270-ffffffff81de92a5: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e5aab0)
Location: net/core/rtnetlink.c:751
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff81e5aab0-ffffffff81e5aae5: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f19e70)
Location: net/core/rtnetlink.c:746
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tfilter_del_notify
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tcf_action_reoffload_cb
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
ffffffff81f19e70-ffffffff81f19ea5: rtnetlink_send (STB_GLOBAL)
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
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bf2448)
Location: net/core/rtnetlink.c:706
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffff800010bf2448-ffff800010bf24fc: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d0ad5c)
Location: net/core/rtnetlink.c:706
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_flush
```
**Symbols:**

```
c0d0ad5c-c0d0adf4: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000cd7320)
Location: net/core/rtnetlink.c:706
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
c000000000cd7320-c000000000cd73f0: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe000773fcc)
Location: net/core/rtnetlink.c:706
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffe000773fcc-ffffffe00077405c: rtnetlink_send (STB_GLOBAL)
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
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818f0990)
Location: net/core/rtnetlink.c:706
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff818f0990-ffffffff818f0a0e: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818aa7d0)
Location: net/core/rtnetlink.c:706
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff818aa7d0-ffffffff818aa84e: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819419c0)
Location: net/core/rtnetlink.c:706
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff819419c0-ffffffff81941a3e: rtnetlink_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtnetlink_send(struct sk_buff *skb, struct net *net, u32 pid, unsigned int group, int echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819632c0)
Location: net/core/rtnetlink.c:706
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/cls_api.c:tc_chain_notify
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tfilter_notify
  - net/sched/cls_api.c:__tcf_chain_put
  - net/sched/act_api.c:tcf_action_add
  - net/sched/act_api.c:tca_action_gd
  - net/sched/act_api.c:tca_action_gd
```
**Symbols:**

```
ffffffff819632c0-ffffffff8196333e: rtnetlink_send (STB_GLOBAL)
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
