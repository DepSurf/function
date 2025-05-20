# Function: <code>rtm_new_nexthop</code>

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
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:1466
Inline: False
```
**Symbols:**

```
ffffffff819d5860-ffffffff819d5f6c: rtm_new_nexthop (STB_LOCAL)
ffffffff819d5fd3-ffffffff819d5ff4: rtm_new_nexthop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a0c3d0)
Location: net/ipv4/nexthop.c:1468
Inline: False
```
**Symbols:**

```
ffffffff81a0c3d0-ffffffff81a0cae3: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81afd810)
Location: net/ipv4/nexthop.c:1604
Inline: False
```
**Symbols:**

```
ffffffff81afd810-ffffffff81afd895: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b0b6a0)
Location: net/ipv4/nexthop.c:1827
Inline: False
```
**Symbols:**

```
ffffffff81b0b6a0-ffffffff81b0b8b0: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af92d0)
Location: net/ipv4/nexthop.c:2899
Inline: False
```
**Symbols:**

```
ffffffff81af92d0-ffffffff81af9507: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb9e20)
Location: net/ipv4/nexthop.c:2928
Inline: False
```
**Symbols:**

```
ffffffff81bb9e20-ffffffff81bba057: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4de00)
Location: net/ipv4/nexthop.c:2928
Inline: False
```
**Symbols:**

```
ffffffff81d4de00-ffffffff81d4e045: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f17740)
Location: net/ipv4/nexthop.c:2928
Inline: False
```
**Symbols:**

```
ffffffff81f17740-ffffffff81f17985: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f77420)
Location: net/ipv4/nexthop.c:2928
Inline: False
```
**Symbols:**

```
ffffffff81f77420-ffffffff81f77665: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff8203dbf0)
Location: net/ipv4/nexthop.c:2951
Inline: False
```
**Symbols:**

```
ffffffff8203dbf0-ffffffff8203de35: rtm_new_nexthop (STB_LOCAL)
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
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffff800010cc5870)
Location: net/ipv4/nexthop.c:1468
Inline: False
```
**Symbols:**

```
ffff800010cc5870-ffff800010cc619c: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c0dd139c)
Location: net/ipv4/nexthop.c:1468
Inline: False
```
**Symbols:**

```
c0dd139c-c0dd1980: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (c000000000de2070)
Location: net/ipv4/nexthop.c:1468
Inline: False
```
**Symbols:**

```
c000000000de2070-c000000000de2c58: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffe00081a49e)
Location: net/ipv4/nexthop.c:1468
Inline: False
```
**Symbols:**

```
ffffffe00081a49e-ffffffe00081abee: rtm_new_nexthop (STB_LOCAL)
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
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff819ac170)
Location: net/ipv4/nexthop.c:1468
Inline: False
```
**Symbols:**

```
ffffffff819ac170-ffffffff819ac883: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81965c30)
Location: net/ipv4/nexthop.c:1468
Inline: False
```
**Symbols:**

```
ffffffff81965c30-ffffffff81966343: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a16a10)
Location: net/ipv4/nexthop.c:1468
Inline: False
```
**Symbols:**

```
ffffffff81a16a10-ffffffff81a17123: rtm_new_nexthop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtm_new_nexthop(struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81a21440)
Location: net/ipv4/nexthop.c:1468
Inline: False
```
**Symbols:**

```
ffffffff81a21440-ffffffff81a21b53: rtm_new_nexthop (STB_LOCAL)
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
