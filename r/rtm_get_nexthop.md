# Function: <code>rtm_get_nexthop</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1557
Inline: False
```
**Symbols:**

```
ffffffff819d4ad0-ffffffff819d4bf7: rtm_get_nexthop (STB_LOCAL)
ffffffff819d5f92-ffffffff819d5fa5: rtm_get_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0b640)
Location: net/ipv4/nexthop.c:1559
Inline: False
```
**Symbols:**

```
ffffffff81a0b640-ffffffff81a0b752: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afc070)
Location: net/ipv4/nexthop.c:1695
Inline: False
```
**Symbols:**

```
ffffffff81afc070-ffffffff81afc180: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b09910)
Location: net/ipv4/nexthop.c:1918
Inline: False
```
**Symbols:**

```
ffffffff81b09910-ffffffff81b09a20: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af70a0)
Location: net/ipv4/nexthop.c:2985
Inline: False
```
**Symbols:**

```
ffffffff81af70a0-ffffffff81af71fe: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb6a40)
Location: net/ipv4/nexthop.c:3014
Inline: False
```
**Symbols:**

```
ffffffff81bb6a40-ffffffff81bb6b9e: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4a650)
Location: net/ipv4/nexthop.c:3014
Inline: False
```
**Symbols:**

```
ffffffff81d4a650-ffffffff81d4a7f1: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f13d00)
Location: net/ipv4/nexthop.c:3014
Inline: False
```
**Symbols:**

```
ffffffff81f13d00-ffffffff81f13ea1: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f739d0)
Location: net/ipv4/nexthop.c:3014
Inline: False
```
**Symbols:**

```
ffffffff81f739d0-ffffffff81f73b71: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff8203a1c0)
Location: net/ipv4/nexthop.c:3037
Inline: False
```
**Symbols:**

```
ffffffff8203a1c0-ffffffff8203a361: rtm_get_nexthop (STB_LOCAL)
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
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc4c08)
Location: net/ipv4/nexthop.c:1559
Inline: False
```
**Symbols:**

```
ffff800010cc4c08-ffff800010cc4d48: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dd0690)
Location: net/ipv4/nexthop.c:1559
Inline: False
```
**Symbols:**

```
c0dd0690-c0dd07d4: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de0e70)
Location: net/ipv4/nexthop.c:1559
Inline: False
```
**Symbols:**

```
c000000000de0e70-c000000000de101c: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe000819f3c)
Location: net/ipv4/nexthop.c:1559
Inline: False
```
**Symbols:**

```
ffffffe000819f3c-ffffffe00081a01a: rtm_get_nexthop (STB_LOCAL)
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
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819ab3e0)
Location: net/ipv4/nexthop.c:1559
Inline: False
```
**Symbols:**

```
ffffffff819ab3e0-ffffffff819ab4f2: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81964ea0)
Location: net/ipv4/nexthop.c:1559
Inline: False
```
**Symbols:**

```
ffffffff81964ea0-ffffffff81964fb2: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a15c80)
Location: net/ipv4/nexthop.c:1559
Inline: False
```
**Symbols:**

```
ffffffff81a15c80-ffffffff81a15d92: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtm_get_nexthop(struct sk_buff *in_skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a206c0)
Location: net/ipv4/nexthop.c:1559
Inline: False
```
**Symbols:**

```
ffffffff81a206c0-ffffffff81a207d2: rtm_get_nexthop (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
