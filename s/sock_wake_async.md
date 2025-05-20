# Function: <code>sock_wake_async</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fd070)
Location: net/socket.c:1062
Inline: False
Direct callers:
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
```
**Symbols:**

```
ffffffff816fd070-ffffffff816fd0e2: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763be0)
Location: net/socket.c:1059
Inline: False
Direct callers:
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81763be0-ffffffff81763c4c: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790c10)
Location: net/socket.c:1102
Inline: False
Direct callers:
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_finish_connect
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81790c10-ffffffff81790c7c: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae530)
Location: net/socket.c:1151
Inline: False
Direct callers:
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff817ae530-ffffffff817ae59c: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81826600)
Location: net/socket.c:1170
Inline: False
Direct callers:
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81826600-ffffffff8182666c: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186fd30)
Location: net/socket.c:1192
Inline: False
Direct callers:
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff8186fd30-ffffffff8186fd9d: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890900)
Location: net/socket.c:1179
Inline: False
Direct callers:
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
```
**Symbols:**

```
ffffffff81890900-ffffffff8189096d: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818da800)
Location: net/socket.c:1306
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff818da800-ffffffff818da869: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190c950)
Location: net/socket.c:1306
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff8190c950-ffffffff8190c9b9: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de6c0)
Location: net/socket.c:1316
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff819de6c0-ffffffff819de729: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de100)
Location: net/socket.c:1294
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff819de100-ffffffff819de169: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c4110)
Location: net/socket.c:1285
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff819c4110-ffffffff819c4179: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a733b0)
Location: net/socket.c:1355
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff81a733b0-ffffffff81a73419: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be5e80)
Location: net/socket.c:1403
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_wfree
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff81be5e80-ffffffff81be5f05: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d920a0)
Location: net/socket.c:1408
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_wfree
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff81d920a0-ffffffff81d92125: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e00450)
Location: net/socket.c:1437
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_wfree
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff81e00450-ffffffff81e004d5: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebc9b0)
Location: net/socket.c:1459
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_wfree
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff81ebc9b0-ffffffff81ebca35: sock_wake_async (STB_GLOBAL)
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
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba2300)
Location: net/socket.c:1306
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffff800010ba2300-ffff800010ba2408: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc3804)
Location: net/socket.c:1306
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
c0cc3804-c0cc38b8: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c75e50)
Location: net/socket.c:1306
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
c000000000c75e50-c000000000c75f50: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000739928)
Location: net/socket.c:1306
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffe000739928-ffffffe0007399c6: sock_wake_async (STB_GLOBAL)
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
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ac950)
Location: net/socket.c:1306
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff818ac950-ffffffff818ac9b9: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818668a0)
Location: net/socket.c:1306
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff818668a0-ffffffff81866909: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fd950)
Location: net/socket.c:1306
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff818fd950-ffffffff818fd9b9: sock_wake_async (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq *wq, int how, int band);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191e9d0)
Location: net/socket.c:1306
Inline: False
Direct callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/stream.c:sk_stream_write_space
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_fin
  - net/ipv4/tcp_input.c:tcp_fin
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff8191e9d0-ffffffff8191ea39: sock_wake_async (STB_GLOBAL)
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
