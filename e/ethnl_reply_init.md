# Function: <code>ethnl_reply_init</code>

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
struct sk_buff *ethnl_reply_init(size_t payload, struct net_device *dev, u8 cmd, u16 hdr_attrtype, struct genl_info *info, void **ehdrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a86250)
Location: net/ethtool/netlink.c:154
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
```
**Symbols:**

```
ffffffff81a86250-ffffffff81a8630c: ethnl_reply_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *ethnl_reply_init(size_t payload, struct net_device *dev, u8 cmd, u16 hdr_attrtype, struct genl_info *info, void **ehdrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a8fb30)
Location: net/ethtool/netlink.c:162
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81a8fb30-ffffffff81a8fbec: ethnl_reply_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *ethnl_reply_init(size_t payload, struct net_device *dev, u8 cmd, u16 hdr_attrtype, struct genl_info *info, void **ehdrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a79260)
Location: net/ethtool/netlink.c:162
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81a79260-ffffffff81a79322: ethnl_reply_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *ethnl_reply_init(size_t payload, struct net_device *dev, u8 cmd, u16 hdr_attrtype, struct genl_info *info, void **ehdrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81b33530)
Location: net/ethtool/netlink.c:196
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81b33530-ffffffff81b335f2: ethnl_reply_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *ethnl_reply_init(size_t payload, struct net_device *dev, u8 cmd, u16 hdr_attrtype, struct genl_info *info, void **ehdrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81cbebe0)
Location: net/ethtool/netlink.c:198
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81cbebe0-ffffffff81cbecbb: ethnl_reply_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *ethnl_reply_init(size_t payload, struct net_device *dev, u8 cmd, u16 hdr_attrtype, struct genl_info *info, void **ehdrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81e7d710)
Location: net/ethtool/netlink.c:198
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81e7d710-ffffffff81e7d7eb: ethnl_reply_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *ethnl_reply_init(size_t payload, struct net_device *dev, u8 cmd, u16 hdr_attrtype, struct genl_info *info, void **ehdrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81ed9cd0)
Location: net/ethtool/netlink.c:200
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81ed9cd0-ffffffff81ed9dab: ethnl_reply_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *ethnl_reply_init(size_t payload, struct net_device *dev, u8 cmd, u16 hdr_attrtype, struct genl_info *info, void **ehdrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81f9da60)
Location: net/ethtool/netlink.c:200
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_doit
  - net/ethtool/features.c:features_send_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81f9da60-ffffffff81f9db3b: ethnl_reply_init (STB_GLOBAL)
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
