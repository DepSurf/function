# Function: <code>addresses_equal</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool addresses_equal(const struct mptcp_addr_info *a, struct mptcp_addr_info *b, bool use_port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb41fa)
Location: net/mptcp/pm_netlink.c:46
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:lookup_subflow_by_saddr
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
```
**Symbols:**

```
ffffffff81bb2e70-ffffffff81bb2ec3: addresses_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool addresses_equal(const struct mptcp_addr_info *a, struct mptcp_addr_info *b, bool use_port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bc843b)
Location: net/mptcp/pm_netlink.c:54
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:lookup_subflow_by_saddr
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
```
**Symbols:**

```
ffffffff81bc72b0-ffffffff81bc7303: addresses_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool addresses_equal(const struct mptcp_addr_info *a, struct mptcp_addr_info *b, bool use_port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb8040)
Location: net/mptcp/pm_netlink.c:61
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
**Symbols:**

```
ffffffff81bb8040-ffffffff81bb80f9: addresses_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool addresses_equal(const struct mptcp_addr_info *a, struct mptcp_addr_info *b, bool use_port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c876c0)
Location: net/mptcp/pm_netlink.c:61
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_sport_in_anno_list
```
**Symbols:**

```
ffffffff81c876c0-ffffffff81c87779: addresses_equal (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
