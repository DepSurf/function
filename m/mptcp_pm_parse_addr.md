# Function: <code>mptcp_pm_parse_addr</code>

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
int mptcp_pm_parse_addr(struct nlattr *attr, struct genl_info *info, bool require_family, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb3130)
Location: net/mptcp/pm_netlink.c:410
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
**Symbols:**

```
ffffffff81bb3130-ffffffff81bb32ed: mptcp_pm_parse_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_pm_parse_addr(struct nlattr *attr, struct genl_info *info, bool require_family, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bc75d0)
Location: net/mptcp/pm_netlink.c:671
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
**Symbols:**

```
ffffffff81bc75d0-ffffffff81bc77a9: mptcp_pm_parse_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_pm_parse_addr(struct nlattr *attr, struct genl_info *info, bool require_family, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb8a60)
Location: net/mptcp/pm_netlink.c:911
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
**Symbols:**

```
ffffffff81bb8a60-ffffffff81bb8cd4: mptcp_pm_parse_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_pm_parse_addr(struct nlattr *attr, struct genl_info *info, bool require_family, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c88030)
Location: net/mptcp/pm_netlink.c:1078
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
**Symbols:**

```
ffffffff81c88030-ffffffff81c882a4: mptcp_pm_parse_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_pm_parse_addr(struct nlattr *attr, struct genl_info *info, struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e315d0)
Location: net/mptcp/pm_netlink.c:1217
Inline: False
Direct callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
```
**Symbols:**

```
ffffffff81e315d0-ffffffff81e31657: mptcp_pm_parse_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_pm_parse_addr(struct nlattr *attr, struct genl_info *info, struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82009bf0)
Location: net/mptcp/pm_netlink.c:1232
Inline: False
Direct callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
```
**Symbols:**

```
ffffffff82009bf0-ffffffff82009c77: mptcp_pm_parse_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_pm_parse_addr(struct nlattr *attr, struct genl_info *info, struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82085f00)
Location: net/mptcp/pm_netlink.c:1236
Inline: False
Direct callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
```
**Symbols:**

```
ffffffff82085f00-ffffffff82085f87: mptcp_pm_parse_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_pm_parse_addr(struct nlattr *attr, struct genl_info *info, struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215b0b0)
Location: net/mptcp/pm_netlink.c:1223
Inline: False
Direct callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit
```
**Symbols:**

```
ffffffff8215b0b0-ffffffff8215b137: mptcp_pm_parse_addr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mptcp_addr_info *addr</code>
</li>
<li>
<b>Param removed. </b>
<code>bool require_family</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mptcp_pm_addr_entry *entry</code>
</li>
</ul>
</details>
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
