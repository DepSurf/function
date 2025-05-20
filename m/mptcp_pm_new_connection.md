# Function: <code>mptcp_pm_new_connection</code>

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
void mptcp_pm_new_connection(struct mptcp_sock *msk, int server_side);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb24c0)
Location: net/mptcp/pm.c:39
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81bb24c0-ffffffff81bb2509: mptcp_pm_new_connection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_pm_new_connection(struct mptcp_sock *msk, int server_side);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bc67a0)
Location: net/mptcp/pm.c:71
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81bc67a0-ffffffff81bc67e9: mptcp_pm_new_connection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_pm_new_connection(struct mptcp_sock *msk, const struct sock *ssk, int server_side);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb7310)
Location: net/mptcp/pm.c:72
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81bb7310-ffffffff81bb7375: mptcp_pm_new_connection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_pm_new_connection(struct mptcp_sock *msk, const struct sock *ssk, int server_side);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81c86630)
Location: net/mptcp/pm.c:74
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81c86630-ffffffff81c86692: mptcp_pm_new_connection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_pm_new_connection(struct mptcp_sock *msk, const struct sock *ssk, int server_side);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81e2ca90)
Location: net/mptcp/pm.c:74
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff81e2ca90-ffffffff81e2cb03: mptcp_pm_new_connection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_pm_new_connection(struct mptcp_sock *msk, const struct sock *ssk, int server_side);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82004e00)
Location: net/mptcp/pm.c:74
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff82004e00-ffffffff82004e73: mptcp_pm_new_connection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_pm_new_connection(struct mptcp_sock *msk, const struct sock *ssk, int server_side);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82080fb0)
Location: net/mptcp/pm.c:76
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff82080fb0-ffffffff82081023: mptcp_pm_new_connection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_pm_new_connection(struct mptcp_sock *msk, const struct sock *ssk, int server_side);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff821565d0)
Location: net/mptcp/pm.c:76
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_connect
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff821565d0-ffffffff82156643: mptcp_pm_new_connection (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock *ssk</code>
</li>
<li>
<b>Param reordered. </b>
<code>msk, server_side</code> ➡️ <code>msk, ssk, server_side</code>
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
