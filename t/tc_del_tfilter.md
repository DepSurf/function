# Function: <code>tc_del_tfilter</code>

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
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d3d50)
Location: net/sched/cls_api.c:1207
Inline: False
```
**Symbols:**

```
ffffffff818d3d50-ffffffff818d431c: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819007a0)
Location: net/sched/cls_api.c:1660
Inline: False
```
**Symbols:**

```
ffffffff819007a0-ffffffff81900dc4: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81961380)
Location: net/sched/cls_api.c:2194
Inline: False
```
**Symbols:**

```
ffffffff81961380-ffffffff81961bc2: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819984d0)
Location: net/sched/cls_api.c:2145
Inline: False
```
**Symbols:**

```
ffffffff819984d0-ffffffff81998cc2: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6fe50)
Location: net/sched/cls_api.c:2168
Inline: False
```
**Symbols:**

```
ffffffff81a6fe50-ffffffff81a705cb: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a78850)
Location: net/sched/cls_api.c:2169
Inline: False
```
**Symbols:**

```
ffffffff81a78850-ffffffff81a78fc1: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a61750)
Location: net/sched/cls_api.c:2170
Inline: False
```
**Symbols:**

```
ffffffff81a61750-ffffffff81a61fda: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2170
Inline: False
```
**Symbols:**

```
ffffffff81b1a960-ffffffff81b1b200: tc_del_tfilter (STB_LOCAL)
ffffffff81d3923b-ffffffff81d39250: tc_del_tfilter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2189
Inline: False
```
**Symbols:**

```
ffffffff81ca3650-ffffffff81ca3fd0: tc_del_tfilter (STB_LOCAL)
ffffffff81f05a6c-ffffffff81f05a8e: tc_del_tfilter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2196
Inline: False
```
**Symbols:**

```
ffffffff81e5f030-ffffffff81e5f895: tc_del_tfilter (STB_LOCAL)
ffffffff820ad860-ffffffff820ad875: tc_del_tfilter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2352
Inline: False
```
**Symbols:**

```
ffffffff81eba760-ffffffff81ebaf9e: tc_del_tfilter (STB_LOCAL)
ffffffff8212ea2a-ffffffff8212ea3f: tc_del_tfilter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/cls_api.c (0)
Location: net/sched/cls_api.c:2405
Inline: False
```
**Symbols:**

```
ffffffff81f7d9d0-ffffffff81f7e182: tc_del_tfilter (STB_LOCAL)
ffffffff822107c8-ffffffff822107eb: tc_del_tfilter.cold (STB_LOCAL)
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
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c45400)
Location: net/sched/cls_api.c:2145
Inline: False
```
**Symbols:**

```
ffff800010c45400-ffff800010c45b2c: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d56f98)
Location: net/sched/cls_api.c:2145
Inline: False
```
**Symbols:**

```
c0d56f98-c0d57684: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d42410)
Location: net/sched/cls_api.c:2145
Inline: False
```
**Symbols:**

```
c000000000d42410-c000000000d42ce4: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b4252)
Location: net/sched/cls_api.c:2145
Inline: False
```
**Symbols:**

```
ffffffe0007b4252-ffffffe0007b47fc: tc_del_tfilter (STB_LOCAL)
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
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81938340)
Location: net/sched/cls_api.c:2145
Inline: False
```
**Symbols:**

```
ffffffff81938340-ffffffff81938b32: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f1e40)
Location: net/sched/cls_api.c:2145
Inline: False
```
**Symbols:**

```
ffffffff818f1e40-ffffffff818f2632: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819894d0)
Location: net/sched/cls_api.c:2145
Inline: False
```
**Symbols:**

```
ffffffff819894d0-ffffffff81989cc2: tc_del_tfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tc_del_tfilter(struct sk_buff *skb, struct nlmsghdr *n, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819ac890)
Location: net/sched/cls_api.c:2145
Inline: False
```
**Symbols:**

```
ffffffff819ac890-ffffffff819ad080: tc_del_tfilter (STB_LOCAL)
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
