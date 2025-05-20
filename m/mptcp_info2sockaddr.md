# Function: <code>mptcp_info2sockaddr</code>

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
In net/mptcp/subflow.c (ffffffff81bafdc0)
Location: net/mptcp/subflow.c:949
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc392b)
Location: net/mptcp/subflow.c:1119
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_info2sockaddr(const struct mptcp_addr_info *info, struct __kernel_sockaddr_storage *addr, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb3ad0)
Location: net/mptcp/subflow.c:1221
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81bb3ad0-ffffffff81bb3b83: mptcp_info2sockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_info2sockaddr(const struct mptcp_addr_info *info, struct __kernel_sockaddr_storage *addr, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81c82220)
Location: net/mptcp/subflow.c:1348
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81c82220-ffffffff81c822d3: mptcp_info2sockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_info2sockaddr(const struct mptcp_addr_info *info, struct __kernel_sockaddr_storage *addr, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e27f20)
Location: net/mptcp/subflow.c:1436
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81e27f20-ffffffff81e27ff7: mptcp_info2sockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_info2sockaddr(const struct mptcp_addr_info *info, struct __kernel_sockaddr_storage *addr, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81fffe70)
Location: net/mptcp/subflow.c:1508
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81fffe70-ffffffff81ffff47: mptcp_info2sockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_info2sockaddr(const struct mptcp_addr_info *info, struct __kernel_sockaddr_storage *addr, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8207c010)
Location: net/mptcp/subflow.c:1488
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff8207c010-ffffffff8207c0e7: mptcp_info2sockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_info2sockaddr(const struct mptcp_addr_info *info, struct __kernel_sockaddr_storage *addr, short unsigned int family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff821514e0)
Location: net/mptcp/subflow.c:1485
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff821514e0-ffffffff821515b7: mptcp_info2sockaddr (STB_GLOBAL)
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
