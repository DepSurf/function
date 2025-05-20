# Function: <code>ethnl_fill_reply_header</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ethnl_fill_reply_header(struct sk_buff *skb, struct net_device *dev, u16 attrtype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a8679c)
Location: net/ethtool/netlink.c:117
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
```
**Symbols:**

```
ffffffff81a85960-ffffffff81a85a5b: ethnl_fill_reply_header.part.0 (STB_LOCAL)
ffffffff81a86230-ffffffff81a8624b: ethnl_fill_reply_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ethnl_fill_reply_header(struct sk_buff *skb, struct net_device *dev, u16 attrtype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a900ac)
Location: net/ethtool/netlink.c:125
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81a8f2d0-ffffffff81a8f3e8: ethnl_fill_reply_header.part.0 (STB_LOCAL)
ffffffff81c32327-ffffffff81c3233f: ethnl_fill_reply_header.part.0.cold (STB_LOCAL)
ffffffff81a8fb10-ffffffff81a8fb2b: ethnl_fill_reply_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ethnl_fill_reply_header(struct sk_buff *skb, struct net_device *dev, u16 attrtype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a797cb)
Location: net/ethtool/netlink.c:125
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_reply_init
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81a789d0-ffffffff81a78ade: ethnl_fill_reply_header.part.0 (STB_LOCAL)
ffffffff81c24610-ffffffff81c24628: ethnl_fill_reply_header.part.0.cold (STB_LOCAL)
ffffffff81a79240-ffffffff81a7925b: ethnl_fill_reply_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ethnl_fill_reply_header(struct sk_buff *skb, struct net_device *dev, u16 attrtype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81b33b4c)
Location: net/ethtool/netlink.c:159
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_reply_init
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81b32ba0-ffffffff81b32cae: ethnl_fill_reply_header.part.0 (STB_LOCAL)
ffffffff81d39697-ffffffff81d396af: ethnl_fill_reply_header.part.0.cold (STB_LOCAL)
ffffffff81b33510-ffffffff81b3352b: ethnl_fill_reply_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethnl_fill_reply_header(struct sk_buff *skb, struct net_device *dev, u16 attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (0)
Location: net/ethtool/netlink.c:161
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81f05e25-ffffffff81f05e3d: ethnl_fill_reply_header.cold (STB_LOCAL)
ffffffff81cbe740-ffffffff81cbe85e: ethnl_fill_reply_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethnl_fill_reply_header(struct sk_buff *skb, struct net_device *dev, u16 attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81e7d230)
Location: net/ethtool/netlink.c:161
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81e7d230-ffffffff81e7d362: ethnl_fill_reply_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethnl_fill_reply_header(struct sk_buff *skb, struct net_device *dev, u16 attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81ed97f0)
Location: net/ethtool/netlink.c:163
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81ed97f0-ffffffff81ed9922: ethnl_fill_reply_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethnl_fill_reply_header(struct sk_buff *skb, struct net_device *dev, u16 attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81f9d6b0)
Location: net/ethtool/netlink.c:163
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_reply_init
  - net/ethtool/cabletest.c:ethnl_cable_test_alloc
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81f9d6b0-ffffffff81f9d7ea: ethnl_fill_reply_header (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
