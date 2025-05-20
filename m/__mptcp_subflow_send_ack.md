# Function: <code>__mptcp_subflow_send_ack</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mptcp_subflow_send_ack(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:510
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_mp_prio_send_ack
```
**Symbols:**

```
ffffffff81f100f9-ffffffff81f10113: __mptcp_subflow_send_ack.cold (STB_LOCAL)
ffffffff81e1f880-ffffffff81e1f8e6: __mptcp_subflow_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __mptcp_subflow_send_ack(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff6733)
Location: net/mptcp/protocol.c:502
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_retrans
Direct callers:
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
```
**Symbols:**

```
ffffffff820b6427-ffffffff820b6441: __mptcp_subflow_send_ack.cold (STB_LOCAL)
ffffffff81ff71a0-ffffffff81ff7206: __mptcp_subflow_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __mptcp_subflow_send_ack(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff820706d5)
Location: net/mptcp/protocol.c:516
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_send_ack
Direct callers:
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
```
**Symbols:**

```
ffffffff8213795c-ffffffff82137976: __mptcp_subflow_send_ack.cold (STB_LOCAL)
ffffffff82074450-ffffffff820744b6: __mptcp_subflow_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __mptcp_subflow_send_ack(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82144635)
Location: net/mptcp/protocol.c:504
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_send_ack
Direct callers:
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
  - net/mptcp/pm_netlink.c:__mptcp_pm_send_ack
```
**Symbols:**

```
ffffffff822196db-ffffffff822196f5: __mptcp_subflow_send_ack.cold (STB_LOCAL)
ffffffff82147ad0-ffffffff82147b36: __mptcp_subflow_send_ack (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
