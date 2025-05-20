# Function: <code>mptcp_nl_remove_id_zero_address</code>

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
int mptcp_nl_remove_id_zero_address(struct net *net, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb9060)
Location: net/mptcp/pm_netlink.c:1146
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff81bb9060-ffffffff81bb91ea: mptcp_nl_remove_id_zero_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_nl_remove_id_zero_address(struct net *net, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c888b0)
Location: net/mptcp/pm_netlink.c:1334
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff81c888b0-ffffffff81c88a3a: mptcp_nl_remove_id_zero_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_nl_remove_id_zero_address(struct net *net, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e2f5e0)
Location: net/mptcp/pm_netlink.c:1444
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff81e2f5e0-ffffffff81e2f7a4: mptcp_nl_remove_id_zero_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_nl_remove_id_zero_address(struct net *net, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82007d40)
Location: net/mptcp/pm_netlink.c:1458
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff82007d40-ffffffff82007f04: mptcp_nl_remove_id_zero_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_nl_remove_id_zero_address(struct net *net, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff820840c0)
Location: net/mptcp/pm_netlink.c:1451
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff820840c0-ffffffff82084284: mptcp_nl_remove_id_zero_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_nl_remove_id_zero_address(struct net *net, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82159820)
Location: net/mptcp/pm_netlink.c:1451
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
```
**Symbols:**

```
ffffffff82159820-ffffffff821599e4: mptcp_nl_remove_id_zero_address (STB_LOCAL)
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
