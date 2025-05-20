# Function: <code>__MPTCP_INC_STATS</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bac81c)
Location: net/mptcp/mib.h:33
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_accept
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bc90c9)
Location: net/mptcp/mib.h:42
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_subflow_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_received
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
In net/mptcp/pm_netlink.c (ffffffff81bb8744)
Location: net/mptcp/mib.h:54
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81c86c5e)
Location: net/mptcp/mib.h:62
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81c87cea)
Location: net/mptcp/mib.h:62
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81e2d27f)
Location: net/mptcp/mib.h:73
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2e510)
Location: net/mptcp/mib.h:73
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
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
In net/mptcp/pm.c (ffffffff8200568f)
Location: net/mptcp/mib.h:73
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff820066aa)
Location: net/mptcp/mib.h:73
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
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
In net/mptcp/pm.c (ffffffff8208187d)
Location: net/mptcp/mib.h:91
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff82082a4a)
Location: net/mptcp/mib.h:91
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
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
In net/mptcp/pm.c (ffffffff82156e9d)
Location: net/mptcp/mib.h:92
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff821580a0)
Location: net/mptcp/mib.h:92
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
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
