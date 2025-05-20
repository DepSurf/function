# Function: <code>__mptcp_close_ssk</code>

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
In net/mptcp/protocol.c (ffffffff81bab038)
Location: net/mptcp/protocol.c:1156
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbeda0)
Location: net/mptcp/protocol.c:2124
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_subflow_received
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_rm_addr_received
```
**Symbols:**

```
ffffffff81bbeda0-ffffffff81bbef13: __mptcp_close_ssk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81babb00)
Location: net/mptcp/protocol.c:2178
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff81babb00-ffffffff81babc9b: __mptcp_close_ssk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7d820)
Location: net/mptcp/protocol.c:2238
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff81c7d820-ffffffff81c7d9e7: __mptcp_close_ssk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e22c90)
Location: net/mptcp/protocol.c:2304
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff81e22c90-ffffffff81e22f4c: __mptcp_close_ssk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff99d0)
Location: net/mptcp/protocol.c:2315
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff81ff99d0-ffffffff81ff9ca8: __mptcp_close_ssk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82075ed0)
Location: net/mptcp/protocol.c:2306
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_unaccepted_force_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff82075ed0-ffffffff820761bc: __mptcp_close_ssk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __mptcp_close_ssk(struct sock *sk, struct sock *ssk, struct mptcp_subflow_context *subflow, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2385
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_destroy_common
  - net/mptcp/protocol.c:__mptcp_close
  - net/mptcp/protocol.c:__mptcp_unaccepted_force_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff8214a460-ffffffff8214a9ec: __mptcp_close_ssk (STB_LOCAL)
ffffffff822198fc-ffffffff8221991b: __mptcp_close_ssk.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
