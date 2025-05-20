# Function: <code>mptcp_pm_get_local_addr_max</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_local_addr_max(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bbb520)
Location: net/mptcp/pm_netlink.c:249
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81bb8010-ffffffff81bb803d: mptcp_pm_get_local_addr_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_local_addr_max(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c8afc0)
Location: net/mptcp/pm_netlink.c:249
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81c87690-ffffffff81c876bd: mptcp_pm_get_local_addr_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_local_addr_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e301e0)
Location: net/mptcp/pm_netlink.c:234
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff81e2ee10-ffffffff81e2ee4a: mptcp_pm_get_local_addr_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_local_addr_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82008992)
Location: net/mptcp/pm_netlink.c:234
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff82007510-ffffffff8200754a: mptcp_pm_get_local_addr_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_local_addr_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82084e12)
Location: net/mptcp/pm_netlink.c:222
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff82083860-ffffffff8208389a: mptcp_pm_get_local_addr_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_local_addr_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215a5d2)
Location: net/mptcp/pm_netlink.c:223
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff82159040-ffffffff8215907a: mptcp_pm_get_local_addr_max (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mptcp_sock *msk</code> ➡️ <code>const struct mptcp_sock *msk</code>
</li>
</ul>
</details>
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
