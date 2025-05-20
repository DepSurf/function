# Function: <code>mptcp_pm_nl_rm_subflow_received</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock *msk, u8 rm_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bc9010)
Location: net/mptcp/pm_netlink.c:485
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
**Symbols:**

```
ffffffff81bc9010-ffffffff81bc9102: mptcp_pm_nl_rm_subflow_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb910a)
Location: net/mptcp/pm_netlink.c:650
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
**Symbols:**

```
ffffffff81bbb110-ffffffff81bbb125: mptcp_pm_nl_rm_subflow_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c8895a)
Location: net/mptcp/pm_netlink.c:776
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
**Symbols:**

```
ffffffff81c8abb0-ffffffff81c8abc5: mptcp_pm_nl_rm_subflow_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e31a3e)
Location: net/mptcp/pm_netlink.c:832
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
**Symbols:**

```
ffffffff81e310c0-ffffffff81e310df: mptcp_pm_nl_rm_subflow_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8200a083)
Location: net/mptcp/pm_netlink.c:845
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
**Symbols:**

```
ffffffff820096a0-ffffffff820096bf: mptcp_pm_nl_rm_subflow_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82086db8)
Location: net/mptcp/pm_netlink.c:848
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
**Symbols:**

```
ffffffff82085ae0-ffffffff82085aff: mptcp_pm_nl_rm_subflow_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mptcp_pm_nl_rm_subflow_received(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215c568)
Location: net/mptcp/pm_netlink.c:849
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_id_zero_address
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_remove_subflow
```
**Symbols:**

```
ffffffff8215ac60-ffffffff8215ac7f: mptcp_pm_nl_rm_subflow_received (STB_GLOBAL)
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
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct mptcp_rm_list *rm_list</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 rm_id</code>
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
