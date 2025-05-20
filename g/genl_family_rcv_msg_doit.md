# Function: <code>genl_family_rcv_msg_doit</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a7c1a7)
Location: net/netlink/genetlink.c:633
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genl_family_rcv_msg_doit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a85150)
Location: net/netlink/genetlink.c:703
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81a85150-ffffffff81a85291: genl_family_rcv_msg_doit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genl_family_rcv_msg_doit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a6e140)
Location: net/netlink/genetlink.c:703
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81a6e140-ffffffff81a6e281: genl_family_rcv_msg_doit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genl_family_rcv_msg_doit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81b277c0)
Location: net/netlink/genetlink.c:695
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81b277c0-ffffffff81b27901: genl_family_rcv_msg_doit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int genl_family_rcv_msg_doit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81cb0780)
Location: net/netlink/genetlink.c:695
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_rcv_msg
```
**Symbols:**

```
ffffffff81cb0780-ffffffff81cb08f6: genl_family_rcv_msg_doit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81e6e700)
Location: net/netlink/genetlink.c:935
Inline: True
Direct callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81e6e700-ffffffff81e6e844: genl_family_rcv_msg_doit.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81eca690)
Location: net/netlink/genetlink.c:937
Inline: True
Direct callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81eca690-ffffffff81eca7d4: genl_family_rcv_msg_doit.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genl_family_rcv_msg_doit(const struct genl_family *family, struct sk_buff *skb, struct nlmsghdr *nlh, struct netlink_ext_ack *extack, const struct genl_split_ops *ops, int hdrlen, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81f8d050)
Location: net/netlink/genetlink.c:1080
Inline: False
Direct callers:
  - net/netlink/genetlink.c:genl_family_rcv_msg
```
**Symbols:**

```
ffffffff81f8d050-ffffffff81f8d1ac: genl_family_rcv_msg_doit (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
