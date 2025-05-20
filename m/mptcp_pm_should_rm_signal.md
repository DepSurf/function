# Function: <code>mptcp_pm_should_rm_signal</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bc4ea0)
Location: net/mptcp/protocol.h:588
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/pm.c (ffffffff81bc6d58)
Location: net/mptcp/protocol.h:588
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb5563)
Location: net/mptcp/protocol.h:728
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/pm.c (ffffffff81bb7a5d)
Location: net/mptcp/protocol.h:728
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
```
```
In net/mptcp/pm_netlink.c (ffffffff81bba32c)
Location: net/mptcp/protocol.h:728
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
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
In net/mptcp/options.c (ffffffff81c841e4)
Location: net/mptcp/protocol.h:783
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/pm.c (ffffffff81c86f2d)
Location: net/mptcp/protocol.h:783
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
```
```
In net/mptcp/pm_netlink.c (ffffffff81c89cbc)
Location: net/mptcp/protocol.h:783
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
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
In net/mptcp/options.c (ffffffff81e2a3b8)
Location: net/mptcp/protocol.h:839
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/pm.c (ffffffff81e2d618)
Location: net/mptcp/protocol.h:839
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
```
```
In net/mptcp/pm_netlink.c (ffffffff81e300bc)
Location: net/mptcp/protocol.h:839
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
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
In net/mptcp/options.c (ffffffff820024f8)
Location: net/mptcp/protocol.h:871
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/pm.c (ffffffff82005a78)
Location: net/mptcp/protocol.h:871
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
```
```
In net/mptcp/pm_netlink.c (ffffffff8200889c)
Location: net/mptcp/protocol.h:871
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
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
In net/mptcp/options.c (ffffffff8207e6b8)
Location: net/mptcp/protocol.h:884
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/pm.c (ffffffff82081c68)
Location: net/mptcp/protocol.h:884
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
```
```
In net/mptcp/pm_netlink.c (ffffffff82084d1c)
Location: net/mptcp/protocol.h:884
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
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
In net/mptcp/options.c (ffffffff82153ba8)
Location: net/mptcp/protocol.h:978
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options
```
```
In net/mptcp/pm.c (ffffffff82157258)
Location: net/mptcp/protocol.h:978
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_signal
```
```
In net/mptcp/pm_netlink.c (ffffffff8215a0bc)
Location: net/mptcp/protocol.h:978
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
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
