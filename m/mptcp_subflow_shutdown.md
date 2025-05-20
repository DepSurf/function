# Function: <code>mptcp_subflow_shutdown</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baca54)
Location: net/mptcp/protocol.c:1314
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_subflow_shutdown(struct sock *sk, struct sock *ssk, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbf1b0)
Location: net/mptcp/protocol.c:2433
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_subflow_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_received
```
**Symbols:**

```
ffffffff81bbf1b0-ffffffff81bbf2e0: mptcp_subflow_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_subflow_shutdown(struct sock *sk, struct sock *ssk, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baedb0)
Location: net/mptcp/protocol.c:2501
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
```
**Symbols:**

```
ffffffff81baedb0-ffffffff81baeedf: mptcp_subflow_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_subflow_shutdown(struct sock *sk, struct sock *ssk, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7c9b0)
Location: net/mptcp/protocol.c:2559
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
```
**Symbols:**

```
ffffffff81c7c9b0-ffffffff81c7caa7: mptcp_subflow_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_subflow_shutdown(struct sock *sk, struct sock *ssk, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e21d90)
Location: net/mptcp/protocol.c:2703
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
**Symbols:**

```
ffffffff81e21d90-ffffffff81e21e8e: mptcp_subflow_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_subflow_shutdown(struct sock *sk, struct sock *ssk, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff9320)
Location: net/mptcp/protocol.c:2751
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
**Symbols:**

```
ffffffff81ff9320-ffffffff81ff941e: mptcp_subflow_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_subflow_shutdown(struct sock *sk, struct sock *ssk, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82075810)
Location: net/mptcp/protocol.c:2756
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_check_send_data_fin
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_destroy
```
**Symbols:**

```
ffffffff82075810-ffffffff82075932: mptcp_subflow_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_subflow_shutdown(struct sock *sk, struct sock *ssk, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82149e80)
Location: net/mptcp/protocol.c:2843
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_check_send_data_fin
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_or_subflow
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_destroy_doit
```
**Symbols:**

```
ffffffff82149e80-ffffffff82149fa2: mptcp_subflow_shutdown (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
