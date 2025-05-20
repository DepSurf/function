# Function: <code>inet_csk_listen_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81764c40)
Location: net/ipv4/inet_connection_sock.c:837
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81764c40-ffffffff81764e4f: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817d11b0)
Location: net/ipv4/inet_connection_sock.c:837
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff817d11b0-ffffffff817d13c6: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81801070)
Location: net/ipv4/inet_connection_sock.c:841
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81801070-ffffffff81801286: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81820db0)
Location: net/ipv4/inet_connection_sock.c:967
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81820db0-ffffffff81820f6a: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818a02d0)
Location: net/ipv4/inet_connection_sock.c:964
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff818a02d0-ffffffff818a052b: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f5680)
Location: net/ipv4/inet_connection_sock.c:959
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff818f5680-ffffffff818f58f8: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819229c0)
Location: net/ipv4/inet_connection_sock.c:977
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819229c0-ffffffff81922c38: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_connection_sock.c (0)
Location: net/ipv4/inet_connection_sock.c:968
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81985f71-ffffffff81985f84: inet_csk_listen_stop.cold (STB_LOCAL)
ffffffff81985380-ffffffff819855e4: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819bbb90)
Location: net/ipv4/inet_connection_sock.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819bbb90-ffffffff819bbdfb: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa63f0)
Location: net/ipv4/inet_connection_sock.c:1019
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81aa63f0-ffffffff81aa6797: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0a40)
Location: net/ipv4/inet_connection_sock.c:1016
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81ab0a40-ffffffff81ab0de1: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9baf0)
Location: net/ipv4/inet_connection_sock.c:1016
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81a9baf0-ffffffff81a9be8d: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b571c0)
Location: net/ipv4/inet_connection_sock.c:1169
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81b571c0-ffffffff81b576c0: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5140)
Location: net/ipv4/inet_connection_sock.c:1174
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:__tcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff81ce5140-ffffffff81ce570d: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8330)
Location: net/ipv4/inet_connection_sock.c:1349
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:__tcp_close
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff81ea8330-ffffffff81ea88fd: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f06bb0)
Location: net/ipv4/inet_connection_sock.c:1371
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81f06bb0-ffffffff81f0717d: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fcaed0)
Location: net/ipv4/inet_connection_sock.c:1371
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_abort
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:__tcp_close
```
**Symbols:**

```
ffffffff81fcaed0-ffffffff81fcb49d: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6d9d0)
Location: net/ipv4/inet_connection_sock.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffff800010c6d9d0-ffff800010c6dd40: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7bf68)
Location: net/ipv4/inet_connection_sock.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
c0d7bf68-c0d7c270: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d72e30)
Location: net/ipv4/inet_connection_sock.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
c000000000d72e30-c000000000d73224: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2d26)
Location: net/ipv4/inet_connection_sock.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffe0007d2d26-ffffffe0007d2f82: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195ba00)
Location: net/ipv4/inet_connection_sock.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff8195ba00-ffffffff8195bc6b: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819154f0)
Location: net/ipv4/inet_connection_sock.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819154f0-ffffffff8191575b: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c61d0)
Location: net/ipv4/inet_connection_sock.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819c61d0-ffffffff819c643b: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_csk_listen_stop(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819cfcf0)
Location: net/ipv4/inet_connection_sock.c:988
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819cfcf0-ffffffff819cff57: inet_csk_listen_stop (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
