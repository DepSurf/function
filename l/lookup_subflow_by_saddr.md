# Function: <code>lookup_subflow_by_saddr</code>

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
bool lookup_subflow_by_saddr(const struct list_head *list, struct mptcp_addr_info *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb3960)
Location: net/mptcp/pm_netlink.c:95
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81bb3960-ffffffff81bb3a2c: lookup_subflow_by_saddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool lookup_subflow_by_saddr(const struct list_head *list, struct mptcp_addr_info *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bc7e00)
Location: net/mptcp/pm_netlink.c:113
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81bc7e00-ffffffff81bc7ecd: lookup_subflow_by_saddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool lookup_subflow_by_saddr(const struct list_head *list, struct mptcp_addr_info *saddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb9e9a)
Location: net/mptcp/pm_netlink.c:125
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81bb8f90-ffffffff81bb9052: lookup_subflow_by_saddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool lookup_subflow_by_saddr(const struct list_head *list, struct mptcp_addr_info *saddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c897cc)
Location: net/mptcp/pm_netlink.c:125
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81c887e0-ffffffff81c888a2: lookup_subflow_by_saddr (STB_LOCAL)
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
In net/mptcp/pm_netlink.c (ffffffff81e32307)
Location: net/mptcp/pm_netlink.c:115
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
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
In net/mptcp/pm_netlink.c (ffffffff8200a647)
Location: net/mptcp/pm_netlink.c:115
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
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
In net/mptcp/pm_netlink.c (ffffffff820867a7)
Location: net/mptcp/pm_netlink.c:114
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool lookup_subflow_by_saddr(const struct list_head *list, const struct mptcp_addr_info *saddr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215b927)
Location: net/mptcp/pm_netlink.c:115
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
```
**Symbols:**

```
ffffffff82159720-ffffffff82159808: lookup_subflow_by_saddr (STB_LOCAL)
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
</ul>
