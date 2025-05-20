# Function: <code>qdisc_graft</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81744240)
Location: net/sched/sch_api.c:803
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
```
**Symbols:**

```
ffffffff81744240-ffffffff817445b5: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b1260)
Location: net/sched/sch_api.c:802
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff817b1260-ffffffff817b15c5: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817e09e0)
Location: net/sched/sch_api.c:808
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff817e09e0-ffffffff817e0d45: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817ffea0)
Location: net/sched/sch_api.c:804
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff817ffea0-ffffffff8180027b: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187dc40)
Location: net/sched/sch_api.c:899
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff8187dc40-ffffffff8187e01f: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818d0670)
Location: net/sched/sch_api.c:929
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff818d0670-ffffffff818d0aae: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fb820)
Location: net/sched/sch_api.c:1016
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff818fb820-ffffffff818fbc42: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8195b180)
Location: net/sched/sch_api.c:1020
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff8195b180-ffffffff8195b5f3: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819917e0)
Location: net/sched/sch_api.c:1020
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff819917e0-ffffffff81991c53: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a695d0)
Location: net/sched/sch_api.c:1029
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff81a695d0-ffffffff81a69afd: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a71e80)
Location: net/sched/sch_api.c:1031
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff81a71e80-ffffffff81a723ad: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a5a6f0)
Location: net/sched/sch_api.c:1031
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff81a5a6f0-ffffffff81a5ac2e: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b13850)
Location: net/sched/sch_api.c:1037
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff81b13850-ffffffff81b13dda: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c9a260)
Location: net/sched/sch_api.c:1037
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff81c9a260-ffffffff81c9a880: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e565e0)
Location: net/sched/sch_api.c:1056
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff81e565e0-ffffffff81e56cc1: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb2c20)
Location: net/sched/sch_api.c:1072
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff81eb2c20-ffffffff81eb333c: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f75730)
Location: net/sched/sch_api.c:1101
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff81f75730-ffffffff81f75e49: qdisc_graft (STB_LOCAL)
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
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3daf8)
Location: net/sched/sch_api.c:1020
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffff800010c3daf8-ffff800010c3dee8: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4f5d4)
Location: net/sched/sch_api.c:1020
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
c0d4f5d4-c0d4fa64: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c000000000d37600)
Location: net/sched/sch_api.c:1020
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
c000000000d37600-c000000000d37b80: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007ade30)
Location: net/sched/sch_api.c:1020
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffe0007ade30-ffffffe0007ae136: qdisc_graft (STB_LOCAL)
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
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81931650)
Location: net/sched/sch_api.c:1020
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff81931650-ffffffff81931ac3: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818eb150)
Location: net/sched/sch_api.c:1020
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff818eb150-ffffffff818eb5c3: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819827e0)
Location: net/sched/sch_api.c:1020
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff819827e0-ffffffff81982c53: qdisc_graft (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int qdisc_graft(struct net_device *dev, struct Qdisc *parent, struct sk_buff *skb, struct nlmsghdr *n, u32 classid, struct Qdisc *new, struct Qdisc *old, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a4d20)
Location: net/sched/sch_api.c:1020
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff819a4d20-ffffffff819a5193: qdisc_graft (STB_LOCAL)
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
