# Function: <code>mptcp_pm_should_add_signal</code>

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
In net/mptcp/options.c (ffffffff81bc4309)
Location: net/mptcp/protocol.h:568
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff81bc6c75)
Location: net/mptcp/protocol.h:568
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc8e78)
Location: net/mptcp/protocol.h:568
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
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
In net/mptcp/options.c (ffffffff81bb4aa1)
Location: net/mptcp/protocol.h:708
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff81bb7985)
Location: net/mptcp/protocol.h:708
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81bba3e5)
Location: net/mptcp/protocol.h:708
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
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
In net/mptcp/options.c (ffffffff81c833ea)
Location: net/mptcp/protocol.h:767
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff81c86d7c)
Location: net/mptcp/protocol.h:767
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81c89d16)
Location: net/mptcp/protocol.h:767
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
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
In net/mptcp/options.c (ffffffff81e2934e)
Location: net/mptcp/protocol.h:823
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff81e2d498)
Location: net/mptcp/protocol.h:823
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff81e3011a)
Location: net/mptcp/protocol.h:823
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
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
In net/mptcp/options.c (ffffffff8200139e)
Location: net/mptcp/protocol.h:855
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff820058e8)
Location: net/mptcp/protocol.h:855
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff82008885)
Location: net/mptcp/protocol.h:855
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
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
In net/mptcp/options.c (ffffffff8207d52e)
Location: net/mptcp/protocol.h:868
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff82081ad8)
Location: net/mptcp/protocol.h:868
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff82084d05)
Location: net/mptcp/protocol.h:868
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
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
In net/mptcp/options.c (ffffffff82152a1e)
Location: net/mptcp/protocol.h:962
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
```
In net/mptcp/pm.c (ffffffff821570c8)
Location: net/mptcp/protocol.h:962
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_signal
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
```
In net/mptcp/pm_netlink.c (ffffffff8215a0a5)
Location: net/mptcp/protocol.h:962
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
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
