# Function: <code>mptcp_pm_get_subflows_max</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_subflows_max(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bbb4e5)
Location: net/mptcp/pm_netlink.c:240
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
```
**Symbols:**

```
ffffffff81bb7fe0-ffffffff81bb800d: mptcp_pm_get_subflows_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_subflows_max(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c8af85)
Location: net/mptcp/pm_netlink.c:240
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
```
**Symbols:**

```
ffffffff81c87660-ffffffff81c8768d: mptcp_pm_get_subflows_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_subflows_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e30a8a)
Location: net/mptcp/pm_netlink.c:226
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff81e2edd0-ffffffff81e2ee0a: mptcp_pm_get_subflows_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_subflows_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff820090da)
Location: net/mptcp/pm_netlink.c:226
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff820074c0-ffffffff820074fa: mptcp_pm_get_subflows_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_subflows_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8208553a)
Location: net/mptcp/pm_netlink.c:214
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff82083810-ffffffff8208384a: mptcp_pm_get_subflows_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_subflows_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215a1ba)
Location: net/mptcp/pm_netlink.c:215
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:fill_remote_addresses_vec
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff82158ff0-ffffffff8215902a: mptcp_pm_get_subflows_max (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mptcp_sock *msk</code> ➡️ <code>const struct mptcp_sock *msk</code>
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
