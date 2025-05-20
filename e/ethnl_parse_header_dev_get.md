# Function: <code>ethnl_parse_header_dev_get</code>

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
int ethnl_parse_header_dev_get(struct ethnl_req_info *req_info, const struct nlattr *header, struct net *net, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a85d90)
Location: net/ethtool/netlink.c:36
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_parse
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
```
**Symbols:**

```
ffffffff81a85d90-ffffffff81a85ff3: ethnl_parse_header_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethnl_parse_header_dev_get(struct ethnl_req_info *req_info, const struct nlattr *header, struct net *net, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a8f720)
Location: net/ethtool/netlink.c:48
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_parse
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81a8f720-ffffffff81a8f95e: ethnl_parse_header_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethnl_parse_header_dev_get(struct ethnl_req_info *req_info, const struct nlattr *header, struct net *net, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a78e10)
Location: net/ethtool/netlink.c:48
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_parse
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/fec.c:ethnl_set_fec
```
**Symbols:**

```
ffffffff81a78e10-ffffffff81a79092: ethnl_parse_header_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethnl_parse_header_dev_get(struct ethnl_req_info *req_info, const struct nlattr *header, struct net *net, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81b330e0)
Location: net/ethtool/netlink.c:88
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_parse
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/fec.c:ethnl_set_fec
```
**Symbols:**

```
ffffffff81b330e0-ffffffff81b33335: ethnl_parse_header_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethnl_parse_header_dev_get(struct ethnl_req_info *req_info, const struct nlattr *header, struct net *net, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81cbe2b0)
Location: net/ethtool/netlink.c:88
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_parse
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/module.c:ethnl_set_module
```
**Symbols:**

```
ffffffff81cbe2b0-ffffffff81cbe514: ethnl_parse_header_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethnl_parse_header_dev_get(struct ethnl_req_info *req_info, const struct nlattr *header, struct net *net, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81e7cd70)
Location: net/ethtool/netlink.c:88
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_parse
  - net/ethtool/linkinfo.c:ethnl_set_linkinfo
  - net/ethtool/linkmodes.c:ethnl_set_linkmodes
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/rings.c:ethnl_set_rings
  - net/ethtool/channels.c:ethnl_set_channels
  - net/ethtool/coalesce.c:ethnl_set_coalesce
  - net/ethtool/pause.c:ethnl_set_pause
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/module.c:ethnl_set_module
  - net/ethtool/pse-pd.c:ethnl_set_pse
```
**Symbols:**

```
ffffffff81e7cd70-ffffffff81e7cfd4: ethnl_parse_header_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethnl_parse_header_dev_get(struct ethnl_req_info *req_info, const struct nlattr *header, struct net *net, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81ed9130)
Location: net/ethtool/netlink.c:88
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
  - net/ethtool/netlink.c:ethnl_default_parse
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81ed9130-ffffffff81ed93cc: ethnl_parse_header_dev_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethnl_parse_header_dev_get(struct ethnl_req_info *req_info, const struct nlattr *header, struct net *net, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81f9cff0)
Location: net/ethtool/netlink.c:88
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
  - net/ethtool/netlink.c:ethnl_default_parse
  - net/ethtool/features.c:ethnl_set_features
  - net/ethtool/cabletest.c:ethnl_act_cable_test_tdr
  - net/ethtool/cabletest.c:ethnl_act_cable_test
  - net/ethtool/tunnels.c:ethnl_tunnel_info_start
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81f9cff0-ffffffff81f9d293: ethnl_parse_header_dev_get (STB_GLOBAL)
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
