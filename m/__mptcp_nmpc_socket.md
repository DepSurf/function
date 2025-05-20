# Function: <code>__mptcp_nmpc_socket</code>

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
In net/mptcp/protocol.c (ffffffff81baac73)
Location: net/mptcp/protocol.c:47
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_get_port
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:__mptcp_socket_create
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
In net/mptcp/protocol.c (ffffffff81bbe265)
Location: net/mptcp/protocol.c:54
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_get_port
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:mptcp_setsockopt
  - net/mptcp/protocol.c:mptcp_accept
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct socket *__mptcp_nmpc_socket(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bad9f5)
Location: net/mptcp/protocol.c:58
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_get_port
  - net/mptcp/protocol.c:mptcp_accept
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff81bae490-ffffffff81bae4b9: __mptcp_nmpc_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct socket *__mptcp_nmpc_socket(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7a425)
Location: net/mptcp/protocol.c:63
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_get_port
  - net/mptcp/protocol.c:mptcp_accept
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff81d43602-ffffffff81d43617: __mptcp_nmpc_socket.cold (STB_LOCAL)
ffffffff81c7a7d0-ffffffff81c7a817: __mptcp_nmpc_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct socket *__mptcp_nmpc_socket(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1eb4a)
Location: net/mptcp/protocol.c:65
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_get_port
  - net/mptcp/protocol.c:mptcp_accept
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff81f100e4-ffffffff81f100f9: __mptcp_nmpc_socket.cold (STB_LOCAL)
ffffffff81e1f820-ffffffff81e1f87f: __mptcp_nmpc_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct socket *__mptcp_nmpc_socket(const struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff54da)
Location: net/mptcp/protocol.c:56
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_get_port
  - net/mptcp/protocol.c:mptcp_accept
  - net/mptcp/protocol.c:mptcp_sendmsg
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff820b6412-ffffffff820b6427: __mptcp_nmpc_socket.cold (STB_LOCAL)
ffffffff81ff67d0-ffffffff81ff682f: __mptcp_nmpc_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct socket *__mptcp_nmpc_socket(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82072983)
Location: net/mptcp/protocol.c:111
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
  - net/mptcp/sockopt.c:mptcp_getsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff821378d4-ffffffff821378ed: __mptcp_nmpc_socket.cold (STB_LOCAL)
ffffffff82072940-ffffffff82072afe: __mptcp_nmpc_socket (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct mptcp_sock *msk</code> ➡️ <code>struct mptcp_sock *msk</code>
</li>
</ul>
</details>
</li>
</ul>
