# Function: <code>mptcp_pm_remove_addrs_and_subflows</code>

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
In net/mptcp/pm_netlink.c (ffffffff81bb9e5d)
Location: net/mptcp/pm_netlink.c:1229
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
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
In net/mptcp/pm_netlink.c (ffffffff81c8978f)
Location: net/mptcp/pm_netlink.c:1417
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_pm_remove_addrs_and_subflows(struct mptcp_sock *msk, struct list_head *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e322a0)
Location: net/mptcp/pm_netlink.c:1527
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
```
**Symbols:**

```
ffffffff81e322a0-ffffffff81e324df: mptcp_pm_remove_addrs_and_subflows (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_pm_remove_addrs_and_subflows(struct mptcp_sock *msk, struct list_head *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8200a5e0)
Location: net/mptcp/pm_netlink.c:1541
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_remove
```
**Symbols:**

```
ffffffff8200a5e0-ffffffff8200a81f: mptcp_pm_remove_addrs_and_subflows (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_pm_remove_addrs_and_subflows(struct mptcp_sock *msk, struct list_head *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82086740)
Location: net/mptcp/pm_netlink.c:1552
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
```
**Symbols:**

```
ffffffff82086740-ffffffff8208697f: mptcp_pm_remove_addrs_and_subflows (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_pm_remove_addrs_and_subflows(struct mptcp_sock *msk, struct list_head *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215b8c0)
Location: net/mptcp/pm_netlink.c:1553
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
```
**Symbols:**

```
ffffffff8215b8c0-ffffffff8215baff: mptcp_pm_remove_addrs_and_subflows (STB_GLOBAL)
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
