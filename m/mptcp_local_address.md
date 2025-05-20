# Function: <code>mptcp_local_address</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mptcp_local_address(const struct sock_common *skc, struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8208681c)
Location: net/mptcp/pm_netlink.c:89
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_get_local_id
  - net/mptcp/pm.c:mptcp_pm_get_local_id
```
**Symbols:**

```
ffffffff820842a0-ffffffff82084309: mptcp_local_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mptcp_local_address(const struct sock_common *skc, struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215b99c)
Location: net/mptcp/pm_netlink.c:90
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_get_local_id
  - net/mptcp/pm.c:mptcp_pm_get_local_id
```
**Symbols:**

```
ffffffff82159a00-ffffffff82159a69: mptcp_local_address (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
