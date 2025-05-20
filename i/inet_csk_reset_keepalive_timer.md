# Function: <code>inet_csk_reset_keepalive_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817641c0)
Location: net/ipv4/inet_connection_sock.c:403
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_set_keepalive
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff817641c0-ffffffff817641e1: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff817d0700)
Location: net/ipv4/inet_connection_sock.c:398
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_set_keepalive
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff817d0700-ffffffff817d0721: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81800550)
Location: net/ipv4/inet_connection_sock.c:402
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_set_keepalive
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81800550-ffffffff81800571: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81820130)
Location: net/ipv4/inet_connection_sock.c:528
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81820130-ffffffff81820151: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8189f0f0)
Location: net/ipv4/inet_connection_sock.c:528
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff8189f0f0-ffffffff8189f111: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff818f3b30)
Location: net/ipv4/inet_connection_sock.c:523
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff818f3b30-ffffffff818f3b51: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81921650)
Location: net/ipv4/inet_connection_sock.c:539
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81921650-ffffffff81921671: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81984010)
Location: net/ipv4/inet_connection_sock.c:535
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81984010-ffffffff81984031: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819ba7c0)
Location: net/ipv4/inet_connection_sock.c:555
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff819ba7c0-ffffffff819ba7e1: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aa5320)
Location: net/ipv4/inet_connection_sock.c:581
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81aa5320-ffffffff81aa5341: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81aaf920)
Location: net/ipv4/inet_connection_sock.c:581
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81aaf920-ffffffff81aaf941: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81a9ac30)
Location: net/ipv4/inet_connection_sock.c:581
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81a9ac30-ffffffff81a9ac51: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81b560a0)
Location: net/ipv4/inet_connection_sock.c:590
Inline: False
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81b560a0-ffffffff81b560c1: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ce3e90)
Location: net/ipv4/inet_connection_sock.c:594
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sock_set_keepidle_locked
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81ce3e90-ffffffff81ce3ebb: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81ea6a40)
Location: net/ipv4/inet_connection_sock.c:755
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sock_set_keepidle_locked
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81ea6a40-ffffffff81ea6a6b: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81f05210)
Location: net/ipv4/inet_connection_sock.c:779
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sock_set_keepidle_locked
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81f05210-ffffffff81f0523b: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81fc9560)
Location: net/ipv4/inet_connection_sock.c:780
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sock_set_keepidle_locked
  - net/ipv4/tcp.c:__tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81fc9560-ffffffff81fc958b: inet_csk_reset_keepalive_timer (STB_GLOBAL)
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
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffff800010c6c538)
Location: net/ipv4/inet_connection_sock.c:555
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffff800010c6c538-ffff800010c6c578: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c0d7b190)
Location: net/ipv4/inet_connection_sock.c:555
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
c0d7b190-c0d7b1c4: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (c000000000d71bd0)
Location: net/ipv4/inet_connection_sock.c:555
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
c000000000d71bd0-c000000000d71c1c: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffe0007d1cd8)
Location: net/ipv4/inet_connection_sock.c:555
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffe0007d1cd8-ffffffe0007d1d16: inet_csk_reset_keepalive_timer (STB_GLOBAL)
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
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff8195a630)
Location: net/ipv4/inet_connection_sock.c:555
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff8195a630-ffffffff8195a651: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff81914120)
Location: net/ipv4/inet_connection_sock.c:555
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff81914120-ffffffff81914141: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819c4e00)
Location: net/ipv4/inet_connection_sock.c:555
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff819c4e00-ffffffff819c4e21: inet_csk_reset_keepalive_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock *sk, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_connection_sock.c (ffffffff819ce8b0)
Location: net/ipv4/inet_connection_sock.c:555
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
**Symbols:**

```
ffffffff819ce8b0-ffffffff819ce8d1: inet_csk_reset_keepalive_timer (STB_GLOBAL)
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
