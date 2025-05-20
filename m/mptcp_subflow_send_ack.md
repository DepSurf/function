# Function: <code>mptcp_subflow_send_ack</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mptcp_subflow_send_ack(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:446
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
```
**Symbols:**

```
ffffffff81d43617-ffffffff81d43631: mptcp_subflow_send_ack.cold (STB_LOCAL)
ffffffff81c7a820-ffffffff81c7a898: mptcp_subflow_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mptcp_subflow_send_ack(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1fce4)
Location: net/mptcp/protocol.c:516
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_addr_send_ack
```
**Symbols:**

```
ffffffff81e20b00-ffffffff81e20b52: mptcp_subflow_send_ack (STB_GLOBAL)
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
In net/mptcp/protocol.c (ffffffff81ff672b)
Location: net/mptcp/protocol.c:508
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
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
In net/mptcp/protocol.c (ffffffff820706ca)
Location: net/mptcp/protocol.c:522
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_send_ack
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
In net/mptcp/protocol.c (ffffffff8214462a)
Location: net/mptcp/protocol.c:510
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_send_ack
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
