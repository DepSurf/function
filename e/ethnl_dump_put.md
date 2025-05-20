# Function: <code>ethnl_dump_put</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *ethnl_dump_put(struct sk_buff *skb, struct netlink_callback *cb, u8 cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a8fec0)
Location: net/ethtool/netlink.c:192
Inline: False
Direct callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81a8fec0-ffffffff81a8feee: ethnl_dump_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *ethnl_dump_put(struct sk_buff *skb, struct netlink_callback *cb, u8 cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a795f0)
Location: net/ethtool/netlink.c:192
Inline: False
Direct callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81a795f0-ffffffff81a7961e: ethnl_dump_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *ethnl_dump_put(struct sk_buff *skb, struct netlink_callback *cb, u8 cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81b33970)
Location: net/ethtool/netlink.c:226
Inline: False
Direct callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81b33970-ffffffff81b3399e: ethnl_dump_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *ethnl_dump_put(struct sk_buff *skb, struct netlink_callback *cb, u8 cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81cbf050)
Location: net/ethtool/netlink.c:228
Inline: False
Direct callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81cbf050-ffffffff81cbf090: ethnl_dump_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *ethnl_dump_put(struct sk_buff *skb, struct netlink_callback *cb, u8 cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81e7dbc0)
Location: net/ethtool/netlink.c:228
Inline: False
Direct callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81e7dbc0-ffffffff81e7dc00: ethnl_dump_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *ethnl_dump_put(struct sk_buff *skb, struct netlink_callback *cb, u8 cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81eda180)
Location: net/ethtool/netlink.c:230
Inline: False
Direct callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81eda180-ffffffff81eda1c0: ethnl_dump_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *ethnl_dump_put(struct sk_buff *skb, struct netlink_callback *cb, u8 cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81f9df10)
Location: net/ethtool/netlink.c:230
Inline: False
Direct callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
```
**Symbols:**

```
ffffffff81f9df10-ffffffff81f9df50: ethnl_dump_put (STB_GLOBAL)
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
