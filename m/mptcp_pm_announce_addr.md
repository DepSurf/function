# Function: <code>mptcp_pm_announce_addr</code>

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
int mptcp_pm_announce_addr(struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb2430)
Location: net/mptcp/pm.c:17
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81bb2430-ffffffff81bb2494: mptcp_pm_announce_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mptcp_pm_announce_addr(struct mptcp_sock *msk, const struct mptcp_addr_info *addr, bool echo, bool port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:15
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff81c33f70-ffffffff81c33f8a: mptcp_pm_announce_addr.cold (STB_LOCAL)
ffffffff81bc6610-ffffffff81bc66c9: mptcp_pm_announce_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mptcp_pm_announce_addr(struct mptcp_sock *msk, const struct mptcp_addr_info *addr, bool echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:15
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff81c262b7-ffffffff81c262d1: mptcp_pm_announce_addr.cold (STB_LOCAL)
ffffffff81bb7170-ffffffff81bb7212: mptcp_pm_announce_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mptcp_pm_announce_addr(struct mptcp_sock *msk, const struct mptcp_addr_info *addr, bool echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:17
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff81d43e48-ffffffff81d43e66: mptcp_pm_announce_addr.cold (STB_LOCAL)
ffffffff81c86480-ffffffff81c86549: mptcp_pm_announce_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mptcp_pm_announce_addr(struct mptcp_sock *msk, const struct mptcp_addr_info *addr, bool echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:17
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
**Symbols:**

```
ffffffff81f1097a-ffffffff81f10998: mptcp_pm_announce_addr.cold (STB_LOCAL)
ffffffff81e2c8c0-ffffffff81e2c997: mptcp_pm_announce_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_pm_announce_addr(struct mptcp_sock *msk, const struct mptcp_addr_info *addr, bool echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82004bd0)
Location: net/mptcp/pm.c:17
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
**Symbols:**

```
ffffffff82004bd0-ffffffff82004cbc: mptcp_pm_announce_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_pm_announce_addr(struct mptcp_sock *msk, const struct mptcp_addr_info *addr, bool echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82080d70)
Location: net/mptcp/pm.c:17
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
```
**Symbols:**

```
ffffffff82080d70-ffffffff82080e66: mptcp_pm_announce_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_pm_announce_addr(struct mptcp_sock *msk, const struct mptcp_addr_info *addr, bool echo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82156390)
Location: net/mptcp/pm.c:17
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_received
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
```
**Symbols:**

```
ffffffff82156390-ffffffff82156486: mptcp_pm_announce_addr (STB_GLOBAL)
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
<b>Param added. </b>
<code>bool echo</code>
</li>
<li>
<b>Param added. </b>
<code>bool port</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool port</code>
</li>
</ul>
</details>
</li>
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
