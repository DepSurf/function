# Function: <code>rtnl_newlink_create</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtnl_newlink_create(struct sk_buff *skb, struct ifinfomsg *ifm, const struct rtnl_link_ops *ops, struct nlattr **tb, struct nlattr **data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81c2db70)
Location: net/core/rtnetlink.c:3311
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff81c2db70-ffffffff81c2df10: rtnl_newlink_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtnl_newlink_create(struct sk_buff *skb, struct ifinfomsg *ifm, const struct rtnl_link_ops *ops, const struct nlmsghdr *nlh, struct nlattr **tb, struct nlattr **data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81de0d40)
Location: net/core/rtnetlink.c:3353
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff81de0d40-ffffffff81de1101: rtnl_newlink_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtnl_newlink_create(struct sk_buff *skb, struct ifinfomsg *ifm, const struct rtnl_link_ops *ops, const struct nlmsghdr *nlh, struct nlattr **tb, struct nlattr **data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81e52430)
Location: net/core/rtnetlink.c:3432
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff81e52430-ffffffff81e527f1: rtnl_newlink_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtnl_newlink_create(struct sk_buff *skb, struct ifinfomsg *ifm, const struct rtnl_link_ops *ops, const struct nlmsghdr *nlh, struct nlattr **tb, struct nlattr **data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81f11400)
Location: net/core/rtnetlink.c:3464
Inline: False
Direct callers:
  - net/core/rtnetlink.c:__rtnl_newlink
```
**Symbols:**

```
ffffffff81f11400-ffffffff81f117c1: rtnl_newlink_create (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct nlmsghdr *nlh</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, ifm, ops, tb, data, extack</code> ➡️ <code>skb, ifm, ops, nlh, tb, data, extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
