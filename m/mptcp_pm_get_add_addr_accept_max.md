# Function: <code>mptcp_pm_get_add_addr_accept_max</code>

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
unsigned int mptcp_pm_get_add_addr_accept_max(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bbb567)
Location: net/mptcp/pm_netlink.c:231
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
```
**Symbols:**

```
ffffffff81bb7fb0-ffffffff81bb7fdd: mptcp_pm_get_add_addr_accept_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_add_addr_accept_max(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c8b007)
Location: net/mptcp/pm_netlink.c:231
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_data_init
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
```
**Symbols:**

```
ffffffff81c87630-ffffffff81c8765d: mptcp_pm_get_add_addr_accept_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_add_addr_accept_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e30a62)
Location: net/mptcp/pm_netlink.c:218
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff81e2ee50-ffffffff81e2ee8a: mptcp_pm_get_add_addr_accept_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_add_addr_accept_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff820090b2)
Location: net/mptcp/pm_netlink.c:218
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff82007470-ffffffff820074aa: mptcp_pm_get_add_addr_accept_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_add_addr_accept_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82085512)
Location: net/mptcp/pm_netlink.c:206
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff820837c0-ffffffff820837fa: mptcp_pm_get_add_addr_accept_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mptcp_pm_get_add_addr_accept_max(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215a192)
Location: net/mptcp/pm_netlink.c:207
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/pm.c:mptcp_pm_data_reset
  - net/mptcp/sockopt.c:mptcp_diag_fill_info
```
**Symbols:**

```
ffffffff82158fa0-ffffffff82158fda: mptcp_pm_get_add_addr_accept_max (STB_GLOBAL)
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
