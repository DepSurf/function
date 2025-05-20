# Function: <code>mptcp_pm_nl_create_listen_socket</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mptcp_pm_nl_create_listen_socket(struct sock *sk, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:761
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
**Symbols:**

```
ffffffff81bb8410-ffffffff81bb84ff: mptcp_pm_nl_create_listen_socket (STB_LOCAL)
ffffffff81c262eb-ffffffff81c26319: mptcp_pm_nl_create_listen_socket.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mptcp_pm_nl_create_listen_socket(struct sock *sk, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:887
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
**Symbols:**

```
ffffffff81c87aa0-ffffffff81c87ba4: mptcp_pm_nl_create_listen_socket (STB_LOCAL)
ffffffff81d4400d-ffffffff81d4403b: mptcp_pm_nl_create_listen_socket.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mptcp_pm_nl_create_listen_socket(struct sock *sk, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:973
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
**Symbols:**

```
ffffffff81e2e2c0-ffffffff81e2e3e6: mptcp_pm_nl_create_listen_socket (STB_LOCAL)
ffffffff81f10b23-ffffffff81f10b53: mptcp_pm_nl_create_listen_socket.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_pm_nl_create_listen_socket(struct sock *sk, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8200b070)
Location: net/mptcp/pm_netlink.c:996
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
**Symbols:**

```
ffffffff8200b070-ffffffff8200b19d: mptcp_pm_nl_create_listen_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_pm_nl_create_listen_socket(struct sock *sk, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff820874b0)
Location: net/mptcp/pm_netlink.c:1002
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
```
**Symbols:**

```
ffffffff820874b0-ffffffff82087621: mptcp_pm_nl_create_listen_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_pm_nl_create_listen_socket(struct sock *sk, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215ccc0)
Location: net/mptcp/pm_netlink.c:1004
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
```
**Symbols:**

```
ffffffff8215ccc0-ffffffff8215ce66: mptcp_pm_nl_create_listen_socket (STB_LOCAL)
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
