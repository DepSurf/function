# Function: <code>mptcp_pm_is_kernel</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81e2ce3f)
Location: net/mptcp/protocol.h:849
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2e553)
Location: net/mptcp/protocol.h:849
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff8200520f)
Location: net/mptcp/protocol.h:881
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
```
```
In net/mptcp/pm_netlink.c (ffffffff8200671f)
Location: net/mptcp/protocol.h:881
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82082ac7)
Location: net/mptcp/protocol.h:894
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
```
```
In net/mptcp/sockopt.c (ffffffff82088795)
Location: net/mptcp/protocol.h:894
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82158145)
Location: net/mptcp/protocol.h:988
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
```
```
In net/mptcp/sockopt.c (ffffffff8215e391)
Location: net/mptcp/protocol.h:988
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
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
