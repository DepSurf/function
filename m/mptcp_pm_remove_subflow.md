# Function: <code>mptcp_pm_remove_subflow</code>

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
int mptcp_pm_remove_subflow(struct mptcp_sock *msk, u8 remote_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (0)
Location: net/mptcp/pm.c:32
Inline: False
```
**Symbols:**

```
ffffffff81bb24b0-ffffffff81bb24c0: mptcp_pm_remove_subflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_pm_remove_subflow(struct mptcp_sock *msk, u8 local_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bc6730)
Location: net/mptcp/pm.c:59
Inline: False
```
**Symbols:**

```
ffffffff81bc6730-ffffffff81bc6796: mptcp_pm_remove_subflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_pm_remove_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb72a0)
Location: net/mptcp/pm.c:60
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff81bb72a0-ffffffff81bb7303: mptcp_pm_remove_subflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_pm_remove_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81c865d0)
Location: net/mptcp/pm.c:62
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_del_addr
```
**Symbols:**

```
ffffffff81c865d0-ffffffff81c86630: mptcp_pm_remove_subflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_pm_remove_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81e2ca20)
Location: net/mptcp/pm.c:62
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
```
**Symbols:**

```
ffffffff81e2ca20-ffffffff81e2ca89: mptcp_pm_remove_subflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_pm_remove_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82004d80)
Location: net/mptcp/pm.c:62
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
```
**Symbols:**

```
ffffffff82004d80-ffffffff82004de9: mptcp_pm_remove_subflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_pm_remove_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82080f30)
Location: net/mptcp/pm.c:64
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
```
**Symbols:**

```
ffffffff82080f30-ffffffff82080f99: mptcp_pm_remove_subflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_pm_remove_subflow(struct mptcp_sock *msk, const struct mptcp_rm_list *rm_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82156550)
Location: net/mptcp/pm.c:64
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
```
**Symbols:**

```
ffffffff82156550-ffffffff821565b9: mptcp_pm_remove_subflow (STB_GLOBAL)
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
<code>u8 local_id</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 remote_id</code>
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
<code>const struct mptcp_rm_list *rm_list</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 local_id</code>
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
