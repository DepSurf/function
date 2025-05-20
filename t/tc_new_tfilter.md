# Function: <code>tc_new_tfilter</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d4320)
Location: net/sched/cls_api.c:1059
Inline: False
```
**Symbols:**

```
ffffffff818d4320-ffffffff818d4a32: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81900dd0)
Location: net/sched/cls_api.c:1505
Inline: False
```
**Symbols:**

```
ffffffff81900dd0-ffffffff81901525: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81961bd0)
Location: net/sched/cls_api.c:1974
Inline: False
```
**Symbols:**

```
ffffffff81961bd0-ffffffff819625b6: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81998cd0)
Location: net/sched/cls_api.c:1919
Inline: False
```
**Symbols:**

```
ffffffff81998cd0-ffffffff81999841: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a705d0)
Location: net/sched/cls_api.c:1941
Inline: False
```
**Symbols:**

```
ffffffff81a705d0-ffffffff81a70f30: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a78fd0)
Location: net/sched/cls_api.c:1942
Inline: False
```
**Symbols:**

```
ffffffff81a78fd0-ffffffff81a7990e: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a61fe0)
Location: net/sched/cls_api.c:1943
Inline: False
```
**Symbols:**

```
ffffffff81a61fe0-ffffffff81a62ac8: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1936
Inline: False
```
**Symbols:**

```
ffffffff81b1b200-ffffffff81b1bdd8: tc_new_tfilter (STB_LOCAL)
ffffffff81d39250-ffffffff81d3927f: tc_new_tfilter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1955
Inline: False
```
**Symbols:**

```
ffffffff81ca2600-ffffffff81ca309f: tc_new_tfilter (STB_LOCAL)
ffffffff81f05a3d-ffffffff81f05a6c: tc_new_tfilter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:1962
Inline: False
```
**Symbols:**

```
ffffffff81e5fe70-ffffffff81e608fc: tc_new_tfilter (STB_LOCAL)
ffffffff820ad875-ffffffff820ad8a4: tc_new_tfilter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2118
Inline: False
```
**Symbols:**

```
ffffffff81ebafb0-ffffffff81ebba66: tc_new_tfilter (STB_LOCAL)
ffffffff8212ea3f-ffffffff8212ea6e: tc_new_tfilter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2171
Inline: False
```
**Symbols:**

```
ffffffff81f7e1a0-ffffffff81f7ec88: tc_new_tfilter (STB_LOCAL)
ffffffff822107eb-ffffffff8221081a: tc_new_tfilter.cold (STB_LOCAL)
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
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c45b30)
Location: net/sched/cls_api.c:1919
Inline: False
```
**Symbols:**

```
ffff800010c45b30-ffff800010c46490: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d55994)
Location: net/sched/cls_api.c:1919
Inline: False
```
**Symbols:**

```
c0d55994-c0d56324: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d40770)
Location: net/sched/cls_api.c:1919
Inline: False
```
**Symbols:**

```
c000000000d40770-c000000000d41450: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b2fb4)
Location: net/sched/cls_api.c:1919
Inline: False
```
**Symbols:**

```
ffffffe0007b2fb4-ffffffe0007b3896: tc_new_tfilter (STB_LOCAL)
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
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81938b40)
Location: net/sched/cls_api.c:1919
Inline: False
```
**Symbols:**

```
ffffffff81938b40-ffffffff819396b1: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f2640)
Location: net/sched/cls_api.c:1919
Inline: False
```
**Symbols:**

```
ffffffff818f2640-ffffffff818f31b1: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81989cd0)
Location: net/sched/cls_api.c:1919
Inline: False
```
**Symbols:**

```
ffffffff81989cd0-ffffffff8198a841: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tc_new_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819ab050)
Location: net/sched/cls_api.c:1919
Inline: False
```
**Symbols:**

```
ffffffff819ab050-ffffffff819abbc7: tc_new_tfilter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
