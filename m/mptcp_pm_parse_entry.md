# Function: <code>mptcp_pm_parse_entry</code>

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
int mptcp_pm_parse_entry(struct nlattr *attr, struct genl_info *info, bool require_family, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e31660)
Location: net/mptcp/pm_netlink.c:1227
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
**Symbols:**

```
ffffffff81e31660-ffffffff81e31734: mptcp_pm_parse_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_pm_parse_entry(struct nlattr *attr, struct genl_info *info, bool require_family, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82009c90)
Location: net/mptcp/pm_netlink.c:1242
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
**Symbols:**

```
ffffffff82009c90-ffffffff82009d64: mptcp_pm_parse_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_pm_parse_entry(struct nlattr *attr, struct genl_info *info, bool require_family, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82085fa0)
Location: net/mptcp/pm_netlink.c:1246
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
**Symbols:**

```
ffffffff82085fa0-ffffffff82086074: mptcp_pm_parse_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_pm_parse_entry(struct nlattr *attr, struct genl_info *info, bool require_family, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215b150)
Location: net/mptcp/pm_netlink.c:1233
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
```
**Symbols:**

```
ffffffff8215b150-ffffffff8215b224: mptcp_pm_parse_entry (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
