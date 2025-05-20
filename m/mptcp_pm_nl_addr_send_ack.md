# Function: <code>mptcp_pm_nl_addr_send_ack</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_pm_nl_addr_send_ack(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bba310)
Location: net/mptcp/pm_netlink.c:528
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81bba310-ffffffff81bba415: mptcp_pm_nl_addr_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_pm_nl_addr_send_ack(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c89ca0)
Location: net/mptcp/pm_netlink.c:653
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81c89ca0-ffffffff81c89d46: mptcp_pm_nl_addr_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_pm_nl_addr_send_ack(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e300a0)
Location: net/mptcp/pm_netlink.c:696
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
**Symbols:**

```
ffffffff81e300a0-ffffffff81e3014a: mptcp_pm_nl_addr_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_pm_nl_addr_send_ack(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82008880)
Location: net/mptcp/pm_netlink.c:722
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
**Symbols:**

```
ffffffff82008880-ffffffff820088fa: mptcp_pm_nl_addr_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_pm_nl_addr_send_ack(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82084d00)
Location: net/mptcp/pm_netlink.c:725
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
**Symbols:**

```
ffffffff82084d00-ffffffff82084d7a: mptcp_pm_nl_addr_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_pm_nl_addr_send_ack(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215a0a0)
Location: net/mptcp/pm_netlink.c:726
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
```
**Symbols:**

```
ffffffff8215a0a0-ffffffff8215a11a: mptcp_pm_nl_addr_send_ack (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
