# Function: <code>mptcp_nl_mcast_send</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bbb9eb)
Location: net/mptcp/pm_netlink.c:1581
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
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
In net/mptcp/pm_netlink.c (ffffffff81c8b62b)
Location: net/mptcp/pm_netlink.c:1771
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e32bdb)
Location: net/mptcp/pm_netlink.c:1918
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
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
In net/mptcp/pm_netlink.c (ffffffff8200b63b)
Location: net/mptcp/pm_netlink.c:1932
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
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
In net/mptcp/pm_netlink.c (ffffffff82087acb)
Location: net/mptcp/pm_netlink.c:1948
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_nl_mcast_send(struct net *net, struct sk_buff *nlskb, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff821588b0)
Location: net/mptcp/pm_netlink.c:1947
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_event
  - net/mptcp/pm_netlink.c:mptcp_event_pm_listener
  - net/mptcp/pm_netlink.c:mptcp_event_addr_announced
  - net/mptcp/pm_netlink.c:mptcp_event_addr_removed
```
**Symbols:**

```
ffffffff821588b0-ffffffff82158912: mptcp_nl_mcast_send (STB_LOCAL)
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
</ul>
