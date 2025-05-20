# Function: <code>tc_ctl_chain</code>

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
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ffe90)
Location: net/sched/cls_api.c:2146
Inline: False
```
**Symbols:**

```
ffffffff818ffe90-ffffffff819003f7: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819607f0)
Location: net/sched/cls_api.c:2789
Inline: False
```
**Symbols:**

```
ffffffff819607f0-ffffffff81960ed4: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819978d0)
Location: net/sched/cls_api.c:2759
Inline: False
```
**Symbols:**

```
ffffffff819978d0-ffffffff81997fe0: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a712b0)
Location: net/sched/cls_api.c:2795
Inline: False
```
**Symbols:**

```
ffffffff81a712b0-ffffffff81a7183e: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a79d30)
Location: net/sched/cls_api.c:2796
Inline: False
```
**Symbols:**

```
ffffffff81a79d30-ffffffff81a7a2bb: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a62f30)
Location: net/sched/cls_api.c:2797
Inline: False
```
**Symbols:**

```
ffffffff81a62f30-ffffffff81a635f3: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2795
Inline: False
```
**Symbols:**

```
ffffffff81b1c2a0-ffffffff81b1c96d: tc_ctl_chain (STB_LOCAL)
ffffffff81d3927f-ffffffff81d392a0: tc_ctl_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2814
Inline: False
```
**Symbols:**

```
ffffffff81ca1b50-ffffffff81ca2336: tc_ctl_chain (STB_LOCAL)
ffffffff81f05a28-ffffffff81f05a3d: tc_ctl_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2818
Inline: False
```
**Symbols:**

```
ffffffff81e5e3e0-ffffffff81e5eb78: tc_ctl_chain (STB_LOCAL)
ffffffff820ad84b-ffffffff820ad860: tc_ctl_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2982
Inline: False
```
**Symbols:**

```
ffffffff81ebc0d0-ffffffff81ebc854: tc_ctl_chain (STB_LOCAL)
ffffffff8212ea6e-ffffffff8212ea8f: tc_ctl_chain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:3039
Inline: False
```
**Symbols:**

```
ffffffff81f7f2b0-ffffffff81f7fa60: tc_ctl_chain (STB_LOCAL)
ffffffff8221081a-ffffffff8221083b: tc_ctl_chain.cold (STB_LOCAL)
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
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c44978)
Location: net/sched/cls_api.c:2759
Inline: False
```
**Symbols:**

```
ffff800010c44978-ffff800010c44fb0: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d56324)
Location: net/sched/cls_api.c:2759
Inline: False
```
**Symbols:**

```
c0d56324-c0d569ec: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d41570)
Location: net/sched/cls_api.c:2759
Inline: False
```
**Symbols:**

```
c000000000d41570-c000000000d41cb0: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b3938)
Location: net/sched/cls_api.c:2759
Inline: False
```
**Symbols:**

```
ffffffe0007b3938-ffffffe0007b3e1a: tc_ctl_chain (STB_LOCAL)
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
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81937740)
Location: net/sched/cls_api.c:2759
Inline: False
```
**Symbols:**

```
ffffffff81937740-ffffffff81937e50: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f1240)
Location: net/sched/cls_api.c:2759
Inline: False
```
**Symbols:**

```
ffffffff818f1240-ffffffff818f1950: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819888d0)
Location: net/sched/cls_api.c:2759
Inline: False
```
**Symbols:**

```
ffffffff819888d0-ffffffff81988fe0: tc_ctl_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tc_ctl_chain(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819abbd0)
Location: net/sched/cls_api.c:2759
Inline: False
```
**Symbols:**

```
ffffffff819abbd0-ffffffff819ac2e0: tc_ctl_chain (STB_LOCAL)
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
