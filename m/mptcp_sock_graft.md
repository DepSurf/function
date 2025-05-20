# Function: <code>mptcp_sock_graft</code>

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
In net/mptcp/protocol.c (ffffffff81babf5c)
Location: net/mptcp/protocol.c:1694
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mptcp_sock_graft(struct sock *sk, struct socket *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbe464)
Location: net/mptcp/protocol.c:3058
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81bc0c30-ffffffff81bc0c83: mptcp_sock_graft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mptcp_sock_graft(struct sock *sk, struct socket *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81badbfe)
Location: net/mptcp/protocol.c:3037
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81bb0ca0-ffffffff81bb0cf3: mptcp_sock_graft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mptcp_sock_graft(struct sock *sk, struct socket *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7a63b)
Location: net/mptcp/protocol.c:3130
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81c7ed60-ffffffff81c7edb3: mptcp_sock_graft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mptcp_sock_graft(struct sock *sk, struct socket *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1ed14)
Location: net/mptcp/protocol.c:3308
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_release_cb
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81e24520-ffffffff81e2457d: mptcp_sock_graft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mptcp_sock_graft(struct sock *sk, struct socket *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff56a8)
Location: net/mptcp/protocol.c:3381
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_release_cb
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81ffbfc0-ffffffff81ffc01d: mptcp_sock_graft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mptcp_sock_graft(struct sock *sk, struct socket *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82076347)
Location: net/mptcp/protocol.c:3447
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff82078390-ffffffff820783ed: mptcp_sock_graft (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mptcp_sock_graft(struct sock *sk, struct socket *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff8214abc5)
Location: net/mptcp/protocol.c:3540
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff8214d530-ffffffff8214d58d: mptcp_sock_graft (STB_GLOBAL)
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
