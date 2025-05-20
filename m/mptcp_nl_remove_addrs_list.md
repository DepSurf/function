# Function: <code>mptcp_nl_remove_addrs_list</code>

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
void mptcp_nl_remove_addrs_list(struct net *net, struct list_head *rm_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb9de0)
Location: net/mptcp/pm_netlink.c:1256
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
```
**Symbols:**

```
ffffffff81bb9de0-ffffffff81bba09b: mptcp_nl_remove_addrs_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_nl_remove_addrs_list(struct net *net, struct list_head *rm_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c89710)
Location: net/mptcp/pm_netlink.c:1444
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
```
**Symbols:**

```
ffffffff81c89710-ffffffff81c89a29: mptcp_nl_remove_addrs_list (STB_LOCAL)
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
In net/mptcp/pm_netlink.c (ffffffff81e325d3)
Location: net/mptcp/pm_netlink.c:1552
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
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
In net/mptcp/pm_netlink.c (ffffffff8200a923)
Location: net/mptcp/pm_netlink.c:1566
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
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
In net/mptcp/pm_netlink.c (ffffffff82086a83)
Location: net/mptcp/pm_netlink.c:1577
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
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
In net/mptcp/pm_netlink.c (ffffffff8215bc03)
Location: net/mptcp/pm_netlink.c:1578
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
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
</ul>
