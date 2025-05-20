# Function: <code>__mptcp_push_pending</code>

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
void __mptcp_push_pending(struct sock *sk, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbf480)
Location: net/mptcp/protocol.c:1445
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81bbf480-ffffffff81bbf737: __mptcp_push_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mptcp_push_pending(struct sock *sk, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baf000)
Location: net/mptcp/protocol.c:1486
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81baf000-ffffffff81baf24a: __mptcp_push_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __mptcp_push_pending(struct sock *sk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7cd20)
Location: net/mptcp/protocol.c:1537
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
**Symbols:**

```
ffffffff81c7cd20-ffffffff81c7cf46: __mptcp_push_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __mptcp_push_pending(struct sock *sk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e224f0)
Location: net/mptcp/protocol.c:1570
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
**Symbols:**

```
ffffffff81e224f0-ffffffff81e2279a: __mptcp_push_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mptcp_push_pending(struct sock *sk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff9710)
Location: net/mptcp/protocol.c:1531
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
**Symbols:**

```
ffffffff81ff9710-ffffffff81ff99bb: __mptcp_push_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mptcp_push_pending(struct sock *sk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82075bf0)
Location: net/mptcp/protocol.c:1504
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
**Symbols:**

```
ffffffff82075bf0-ffffffff82075eb4: __mptcp_push_pending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __mptcp_push_pending(struct sock *sk, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1558
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_subflow_chk_stale
```
**Symbols:**

```
ffffffff822198c9-ffffffff822198fc: __mptcp_push_pending.cold (STB_LOCAL)
ffffffff8214a1b0-ffffffff8214a44b: __mptcp_push_pending (STB_GLOBAL)
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
