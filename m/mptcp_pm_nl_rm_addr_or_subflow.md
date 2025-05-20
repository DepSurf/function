# Function: <code>mptcp_pm_nl_rm_addr_or_subflow</code>

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
void mptcp_pm_nl_rm_addr_or_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list, enum linux_mptcp_mib_field rm_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb8680)
Location: net/mptcp/pm_netlink.c:594
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff81bb8680-ffffffff81bb8861: mptcp_pm_nl_rm_addr_or_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_pm_nl_rm_addr_or_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list, enum linux_mptcp_mib_field rm_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c87bb0)
Location: net/mptcp/pm_netlink.c:711
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff81c87bb0-ffffffff81c87e33: mptcp_pm_nl_rm_addr_or_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_pm_nl_rm_addr_or_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list, enum linux_mptcp_mib_field rm_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e2e3f0)
Location: net/mptcp/pm_netlink.c:761
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff81e2e3f0-ffffffff81e2e734: mptcp_pm_nl_rm_addr_or_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_pm_nl_rm_addr_or_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list, enum linux_mptcp_mib_field rm_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff820065b0)
Location: net/mptcp/pm_netlink.c:773
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff820065b0-ffffffff820068b0: mptcp_pm_nl_rm_addr_or_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_pm_nl_rm_addr_or_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list, enum linux_mptcp_mib_field rm_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82082920)
Location: net/mptcp/pm_netlink.c:776
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff82082920-ffffffff82082c4d: mptcp_pm_nl_rm_addr_or_subflow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_pm_nl_rm_addr_or_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list, enum linux_mptcp_mib_field rm_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82157f90)
Location: net/mptcp/pm_netlink.c:777
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff82157f90-ffffffff821582b1: mptcp_pm_nl_rm_addr_or_subflow (STB_LOCAL)
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
