# Function: <code>__mptcp_retransmit_pending_data</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool __mptcp_retransmit_pending_data(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7c7e0)
Location: net/mptcp/protocol.c:2189
Inline: True
Direct callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
**Symbols:**

```
ffffffff81c7c7e0-ffffffff81c7c9a7: __mptcp_retransmit_pending_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __mptcp_retransmit_pending_data(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e21b60)
Location: net/mptcp/protocol.c:2252
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
**Symbols:**

```
ffffffff81e21b60-ffffffff81e21d10: __mptcp_retransmit_pending_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __mptcp_retransmit_pending_data(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff9060)
Location: net/mptcp/protocol.c:2263
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
**Symbols:**

```
ffffffff81ff9060-ffffffff81ff9210: __mptcp_retransmit_pending_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __mptcp_retransmit_pending_data(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82075550)
Location: net/mptcp/protocol.c:2254
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
**Symbols:**

```
ffffffff82075550-ffffffff82075700: __mptcp_retransmit_pending_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __mptcp_retransmit_pending_data(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82149bd0)
Location: net/mptcp/protocol.c:2316
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
**Symbols:**

```
ffffffff82149bd0-ffffffff82149d53: __mptcp_retransmit_pending_data (STB_GLOBAL)
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
