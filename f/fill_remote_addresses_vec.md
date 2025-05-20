# Function: <code>fill_remote_addresses_vec</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int fill_remote_addresses_vec(struct mptcp_sock *msk, bool fullmesh, struct mptcp_addr_info *addrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c88e40)
Location: net/mptcp/pm_netlink.c:429
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff81c88e40-ffffffff81c8907e: fill_remote_addresses_vec (STB_LOCAL)
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
In net/mptcp/pm_netlink.c (ffffffff81e30367)
Location: net/mptcp/pm_netlink.c:426
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
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
In net/mptcp/pm_netlink.c (ffffffff82008adb)
Location: net/mptcp/pm_netlink.c:426
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
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
In net/mptcp/pm_netlink.c (ffffffff82084f31)
Location: net/mptcp/pm_netlink.c:414
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int fill_remote_addresses_vec(struct mptcp_sock *msk, struct mptcp_addr_info *local, bool fullmesh, struct mptcp_addr_info *addrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:402
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
```
**Symbols:**

```
ffffffff82159100-ffffffff821593aa: fill_remote_addresses_vec (STB_LOCAL)
ffffffff82219fbc-ffffffff82219fdb: fill_remote_addresses_vec.cold (STB_LOCAL)
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
