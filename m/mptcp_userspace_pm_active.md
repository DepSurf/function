# Function: <code>mptcp_userspace_pm_active</code>

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
bool mptcp_userspace_pm_active(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e326e0)
Location: net/mptcp/pm_netlink.c:1924
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
```
**Symbols:**

```
ffffffff81e326e0-ffffffff81e3272e: mptcp_userspace_pm_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mptcp_userspace_pm_active(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8200aa40)
Location: net/mptcp/pm_netlink.c:1938
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
```
**Symbols:**

```
ffffffff8200aa40-ffffffff8200aa8e: mptcp_userspace_pm_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mptcp_userspace_pm_active(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82086e70)
Location: net/mptcp/pm_netlink.c:1954
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
```
**Symbols:**

```
ffffffff82086e70-ffffffff82086ebe: mptcp_userspace_pm_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mptcp_userspace_pm_active(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215c710)
Location: net/mptcp/pm_netlink.c:1953
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_can_accept_new_subflow
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_allow_new_subflow
```
**Symbols:**

```
ffffffff8215c710-ffffffff8215c75e: mptcp_userspace_pm_active (STB_GLOBAL)
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
