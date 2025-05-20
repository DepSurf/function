# Function: <code>mptcp_pm_nl_check_work_pending</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mptcp_pm_nl_check_work_pending(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e2f7b0)
Location: net/mptcp/pm_netlink.c:242
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81e2f7b0-ffffffff81e2f884: mptcp_pm_nl_check_work_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mptcp_pm_nl_check_work_pending(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82007f20)
Location: net/mptcp/pm_netlink.c:242
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff82007f20-ffffffff82007fe2: mptcp_pm_nl_check_work_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mptcp_pm_nl_check_work_pending(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82084320)
Location: net/mptcp/pm_netlink.c:230
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff82084320-ffffffff820843e2: mptcp_pm_nl_check_work_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mptcp_pm_nl_check_work_pending(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82159a80)
Location: net/mptcp/pm_netlink.c:231
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff82159a80-ffffffff82159b42: mptcp_pm_nl_check_work_pending (STB_GLOBAL)
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
