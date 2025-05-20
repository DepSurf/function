# Function: <code>mptcp_subflow_get_send</code>

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
struct sock *mptcp_subflow_get_send(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81babbb0)
Location: net/mptcp/protocol.c:695
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81babbb0-ffffffff81babc9c: mptcp_subflow_get_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *mptcp_subflow_get_send(struct mptcp_sock *msk, u32 *sndbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbb400)
Location: net/mptcp/protocol.c:1362
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff81bbb400-ffffffff81bbb77e: mptcp_subflow_get_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct sock *mptcp_subflow_get_send(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baa950)
Location: net/mptcp/protocol.c:1414
Inline: True
Direct callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff81baa950-ffffffff81baabf2: mptcp_subflow_get_send.part.0 (STB_LOCAL)
ffffffff81baac00-ffffffff81baac80: mptcp_subflow_get_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct sock *mptcp_subflow_get_send(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7c0d0)
Location: net/mptcp/protocol.c:1434
Inline: True
Direct callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff81c7c0d0-ffffffff81c7c436: mptcp_subflow_get_send.part.0 (STB_LOCAL)
ffffffff81c7c440-ffffffff81c7c4c0: mptcp_subflow_get_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sock *mptcp_subflow_get_send(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1439
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff81e213c0-ffffffff81e2184e: mptcp_subflow_get_send (STB_LOCAL)
ffffffff81f102b6-ffffffff81f102d8: mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sock *mptcp_subflow_get_send(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1400
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff81ff8890-ffffffff81ff8d1e: mptcp_subflow_get_send (STB_LOCAL)
ffffffff820b6590-ffffffff820b65b2: mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sock *mptcp_subflow_get_send(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1371
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff82074d60-ffffffff820751ed: mptcp_subflow_get_send (STB_LOCAL)
ffffffff82137a2c-ffffffff82137a45: mptcp_subflow_get_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *mptcp_subflow_get_send(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82149780)
Location: net/mptcp/protocol.c:1400
Inline: False
Direct callers:
  - net/mptcp/sched.c:mptcp_sched_get_send
```
**Symbols:**

```
ffffffff82149780-ffffffff82149a39: mptcp_subflow_get_send (STB_GLOBAL)
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
<code>u32 *sndbuf</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 *sndbuf</code>
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
