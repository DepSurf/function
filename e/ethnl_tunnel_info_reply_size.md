# Function: <code>ethnl_tunnel_info_reply_size</code>

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
ssize_t ethnl_tunnel_info_reply_size(const struct ethnl_req_info *req_base, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/tunnels.c (ffffffff81a97010)
Location: net/ethtool/tunnels.c:36
Inline: False
Direct callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81a97010-ffffffff81a97139: ethnl_tunnel_info_reply_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/tunnels.c (ffffffff81a80e9e)
Location: net/ethtool/tunnels.c:36
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/tunnels.c (ffffffff81b3abde)
Location: net/ethtool/tunnels.c:36
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/tunnels.c (ffffffff81cc6b53)
Location: net/ethtool/tunnels.c:36
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/tunnels.c (ffffffff81e86183)
Location: net/ethtool/tunnels.c:36
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/tunnels.c (ffffffff81ee2b15)
Location: net/ethtool/tunnels.c:36
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/tunnels.c (ffffffff81fa69a5)
Location: net/ethtool/tunnels.c:36
Inline: True
Inline callers:
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
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
</ul>
