# Function: <code>__mptcp_subflow_connect</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __mptcp_subflow_connect(struct sock *sk, int ifindex, const struct mptcp_addr_info *loc, const struct mptcp_addr_info *remote);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bafd00)
Location: net/mptcp/subflow.c:970
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81bafd00-ffffffff81baff7c: __mptcp_subflow_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __mptcp_subflow_connect(struct sock *sk, const struct mptcp_addr_info *loc, const struct mptcp_addr_info *remote);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc3810)
Location: net/mptcp/subflow.c:1140
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81bc3810-ffffffff81bc3c1c: __mptcp_subflow_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __mptcp_subflow_connect(struct sock *sk, const struct mptcp_addr_info *loc, const struct mptcp_addr_info *remote, u8 flags, int ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb3eb0)
Location: net/mptcp/subflow.c:1252
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81bb3eb0-ffffffff81bb4271: __mptcp_subflow_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __mptcp_subflow_connect(struct sock *sk, const struct mptcp_addr_info *loc, const struct mptcp_addr_info *remote);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1379
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81d43b91-ffffffff81d43ba5: __mptcp_subflow_connect.cold (STB_LOCAL)
ffffffff81c825f0-ffffffff81c829e1: __mptcp_subflow_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __mptcp_subflow_connect(struct sock *sk, const struct mptcp_addr_info *loc, const struct mptcp_addr_info *remote);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1467
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
```
**Symbols:**

```
ffffffff81f106f2-ffffffff81f10706: __mptcp_subflow_connect.cold (STB_LOCAL)
ffffffff81e28310-ffffffff81e28725: __mptcp_subflow_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __mptcp_subflow_connect(struct sock *sk, const struct mptcp_addr_info *loc, const struct mptcp_addr_info *remote);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1539
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
```
**Symbols:**

```
ffffffff820b6a81-ffffffff820b6a95: __mptcp_subflow_connect.cold (STB_LOCAL)
ffffffff82000280-ffffffff820006a0: __mptcp_subflow_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __mptcp_subflow_connect(struct sock *sk, const struct mptcp_addr_info *loc, const struct mptcp_addr_info *remote);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1519
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
```
**Symbols:**

```
ffffffff82137dee-ffffffff82137e02: __mptcp_subflow_connect.cold (STB_LOCAL)
ffffffff8207c450-ffffffff8207c888: __mptcp_subflow_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __mptcp_subflow_connect(struct sock *sk, const struct mptcp_addr_info *loc, const struct mptcp_addr_info *remote);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1516
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit
```
**Symbols:**

```
ffffffff82219c63-ffffffff82219c77: __mptcp_subflow_connect.cold (STB_LOCAL)
ffffffff82151930-ffffffff82151d8b: __mptcp_subflow_connect (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int ifindex</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, ifindex, loc, remote</code> ➡️ <code>sk, loc, remote</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 flags</code>
</li>
<li>
<b>Param added. </b>
<code>int ifindex</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u8 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int ifindex</code>
</li>
</ul>
</details>
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
