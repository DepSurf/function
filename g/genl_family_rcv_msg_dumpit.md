# Function: <code>genl_family_rcv_msg_dumpit</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int genl_family_rcv_msg_dumpit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a7b7b0)
Location: net/netlink/genetlink.c:587
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81a7b7b0-ffffffff81a7b8bb: genl_family_rcv_msg_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genl_family_rcv_msg_dumpit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a84680)
Location: net/netlink/genetlink.c:657
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81a84680-ffffffff81a8478b: genl_family_rcv_msg_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genl_family_rcv_msg_dumpit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a6d770)
Location: net/netlink/genetlink.c:657
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81a6d770-ffffffff81a6d87b: genl_family_rcv_msg_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genl_family_rcv_msg_dumpit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81b26e80)
Location: net/netlink/genetlink.c:649
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81b26e80-ffffffff81b26f8b: genl_family_rcv_msg_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int genl_family_rcv_msg_dumpit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81cafd70)
Location: net/netlink/genetlink.c:649
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81cafd70-ffffffff81cafeb6: genl_family_rcv_msg_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genl_family_rcv_msg_dumpit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_split_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81e6dbc0)
Location: net/netlink/genetlink.c:892
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81e6dbc0-ffffffff81e6dcd2: genl_family_rcv_msg_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genl_family_rcv_msg_dumpit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_split_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81ec9cd0)
Location: net/netlink/genetlink.c:892
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81ec9cd0-ffffffff81ec9dea: genl_family_rcv_msg_dumpit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genl_family_rcv_msg_dumpit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_split_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81f8d8f0)
Location: net/netlink/genetlink.c:1049
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81f8d8f0-ffffffff81f8d9e9: genl_family_rcv_msg_dumpit (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct genl_ops *ops</code> ➡️ <code>const struct genl_split_ops *ops</code>
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
