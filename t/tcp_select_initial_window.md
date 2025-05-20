# Function: <code>tcp_select_initial_window</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_select_initial_window(int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817742d0)
Location: net/ipv4/tcp_output.c:208
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff817742d0-ffffffff817743e5: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_select_initial_window(int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e1160)
Location: net/ipv4/tcp_output.c:205
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff817e1160-ffffffff817e1291: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_select_initial_window(int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81811580)
Location: net/ipv4/tcp_output.c:205
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81811580-ffffffff818116b1: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_select_initial_window(int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81831690)
Location: net/ipv4/tcp_output.c:206
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81831690-ffffffff818317c1: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b0a80)
Location: net/ipv4/tcp_output.c:191
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff818b0a80-ffffffff818b0bd1: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81906260)
Location: net/ipv4/tcp_output.c:204
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81906260-ffffffff8190636b: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819346c0)
Location: net/ipv4/tcp_output.c:204
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819346c0-ffffffff819347af: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81998200)
Location: net/ipv4/tcp_output.c:204
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81998200-ffffffff819982ef: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819ced30)
Location: net/ipv4/tcp_output.c:207
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819ced30-ffffffff819cee1f: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abae60)
Location: net/ipv4/tcp_output.c:208
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81abae60-ffffffff81abaf59: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac6200)
Location: net/ipv4/tcp_output.c:208
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81ac6200-ffffffff81ac62f9: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab1410)
Location: net/ipv4/tcp_output.c:208
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81ab1410-ffffffff81ab14f6: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b6e3b0)
Location: net/ipv4/tcp_output.c:208
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81b6e3b0-ffffffff81b6e4ad: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81cfdaa0)
Location: net/ipv4/tcp_output.c:206
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81cfdaa0-ffffffff81cfdb98: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec2700)
Location: net/ipv4/tcp_output.c:206
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81ec2700-ffffffff81ec27f8: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f20c60)
Location: net/ipv4/tcp_output.c:206
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81f20c60-ffffffff81f20d58: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fe5360)
Location: net/ipv4/tcp_output.c:205
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81fe5360-ffffffff81fe5458: tcp_select_initial_window (STB_GLOBAL)
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
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c81780)
Location: net/ipv4/tcp_output.c:207
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffff800010c81780-ffff800010c818d0: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d907d8)
Location: net/ipv4/tcp_output.c:207
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c0d907d8-c0d90900: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d8c6f0)
Location: net/ipv4/tcp_output.c:207
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
c000000000d8c6f0-c000000000d8c8d8: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e35a4)
Location: net/ipv4/tcp_output.c:207
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffe0007e35a4-ffffffe0007e3754: tcp_select_initial_window (STB_GLOBAL)
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
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8196eba0)
Location: net/ipv4/tcp_output.c:207
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff8196eba0-ffffffff8196ec8f: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81928690)
Location: net/ipv4/tcp_output.c:207
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff81928690-ffffffff8192877f: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d9370)
Location: net/ipv4/tcp_output.c:207
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819d9370-ffffffff819d945f: tcp_select_initial_window (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_select_initial_window(const struct sock *sk, int __space, __u32 mss, __u32 *rcv_wnd, __u32 *window_clamp, int wscale_ok, __u8 *rcv_wscale, __u32 init_rcv_wnd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e2fd0)
Location: net/ipv4/tcp_output.c:207
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv6/syncookies.c:cookie_v6_check
```
**Symbols:**

```
ffffffff819e2fd0-ffffffff819e30bf: tcp_select_initial_window (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock *sk</code>
</li>
<li>
<b>Param reordered. </b>
<code>__space, mss, rcv_wnd, window_clamp, wscale_ok, rcv_wscale, init_rcv_wnd</code> ➡️ <code>sk, __space, mss, rcv_wnd, window_clamp, wscale_ok, rcv_wscale, init_rcv_wnd</code>
</li>
</ul>
</details>
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
