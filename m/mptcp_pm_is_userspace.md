# Function: <code>mptcp_pm_is_userspace</code>

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
In net/mptcp/subflow.c (ffffffff81e2526d)
Location: net/mptcp/protocol.h:844
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
```
```
In net/mptcp/pm.c (ffffffff81e2cf67)
Location: net/mptcp/protocol.h:844
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff81e319d2)
Location: net/mptcp/protocol.h:844
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
```
```
In net/mptcp/pm_userspace.c (ffffffff81e3608f)
Location: net/mptcp/protocol.h:844
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
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
In net/mptcp/subflow.c (ffffffff81ffce8d)
Location: net/mptcp/protocol.h:876
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
```
```
In net/mptcp/pm.c (ffffffff82005347)
Location: net/mptcp/protocol.h:876
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff8200a017)
Location: net/mptcp/protocol.h:876
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
```
```
In net/mptcp/pm_userspace.c (ffffffff8200edaf)
Location: net/mptcp/protocol.h:876
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
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
In net/mptcp/subflow.c (ffffffff8207915d)
Location: net/mptcp/protocol.h:889
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
```
```
In net/mptcp/pm.c (ffffffff82081e04)
Location: net/mptcp/protocol.h:889
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm.c:mptcp_pm_get_local_id
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff82086d0b)
Location: net/mptcp/protocol.h:889
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
```
In net/mptcp/pm_userspace.c (ffffffff8208b99f)
Location: net/mptcp/protocol.h:889
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
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
In net/mptcp/subflow.c (ffffffff8214e5ad)
Location: net/mptcp/protocol.h:983
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
```
```
In net/mptcp/pm.c (ffffffff821573f4)
Location: net/mptcp/protocol.h:983
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_get_flags_and_ifindex_by_id
  - net/mptcp/pm.c:mptcp_pm_get_local_id
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
```
```
In net/mptcp/pm_netlink.c (ffffffff8215c4bb)
Location: net/mptcp/protocol.h:983
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
```
```
In net/mptcp/pm_userspace.c (ffffffff8216179f)
Location: net/mptcp/protocol.h:983
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_remove_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
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
