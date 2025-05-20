# Function: <code>mptcp_pm_parse_pm_addr_attr</code>

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
int mptcp_pm_parse_pm_addr_attr(struct nlattr **tb, const struct nlattr *attr, struct genl_info *info, struct mptcp_addr_info *addr, bool require_family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e2e940)
Location: net/mptcp/pm_netlink.c:1156
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
```
**Symbols:**

```
ffffffff81e2e940-ffffffff81e2eb50: mptcp_pm_parse_pm_addr_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_pm_parse_pm_addr_attr(struct nlattr **tb, const struct nlattr *attr, struct genl_info *info, struct mptcp_addr_info *addr, bool require_family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82006ad0)
Location: net/mptcp/pm_netlink.c:1171
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
```
**Symbols:**

```
ffffffff82006ad0-ffffffff82006ce0: mptcp_pm_parse_pm_addr_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_pm_parse_pm_addr_attr(struct nlattr **tb, const struct nlattr *attr, struct genl_info *info, struct mptcp_addr_info *addr, bool require_family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82082e70)
Location: net/mptcp/pm_netlink.c:1175
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
```
**Symbols:**

```
ffffffff82082e70-ffffffff82083080: mptcp_pm_parse_pm_addr_attr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_pm_parse_pm_addr_attr(struct nlattr **tb, const struct nlattr *attr, struct genl_info *info, struct mptcp_addr_info *addr, bool require_family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff821584e0)
Location: net/mptcp/pm_netlink.c:1162
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_entry
  - net/mptcp/pm_netlink.c:mptcp_pm_parse_addr
```
**Symbols:**

```
ffffffff821584e0-ffffffff82158703: mptcp_pm_parse_pm_addr_attr (STB_LOCAL)
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
