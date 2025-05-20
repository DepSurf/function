# Function: <code>mptcp_nl_remove_subflow_and_signal_addr</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bc86e0)
Location: net/mptcp/pm_netlink.c:814
Inline: True
Direct callers:
  - net/mptcp/pm_netlink.c:pm_nl_exit_net
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff81bc86e0-ffffffff81bc8920: mptcp_nl_remove_subflow_and_signal_addr.isra.0 (STB_LOCAL)
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
In net/mptcp/pm_netlink.c (ffffffff81bb9c16)
Location: net/mptcp/pm_netlink.c:1103
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
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
In net/mptcp/pm_netlink.c (ffffffff81c89526)
Location: net/mptcp/pm_netlink.c:1291
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e2fbb0)
Location: net/mptcp/pm_netlink.c:1404
Inline: True
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff81e2fbb0-ffffffff81e2fe1b: mptcp_nl_remove_subflow_and_signal_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82008360)
Location: net/mptcp/pm_netlink.c:1418
Inline: True
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff82008360-ffffffff820085cb: mptcp_nl_remove_subflow_and_signal_addr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82084680)
Location: net/mptcp/pm_netlink.c:1411
Inline: True
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff82084680-ffffffff82084a55: mptcp_nl_remove_subflow_and_signal_addr.isra.0 (STB_LOCAL)
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
In net/mptcp/pm_netlink.c (ffffffff8215b428)
Location: net/mptcp/pm_netlink.c:1411
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
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
