# Function: <code>tcp_mstamp_refresh</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818307e5)
Location: include/net/tcp.h:746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818373a6)
Location: include/net/tcp.h:746
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff81838617)
Location: include/net/tcp.h:746
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c4d0)
Location: include/net/tcp.h:746
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818afc73)
Location: include/net/tcp.h:722
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff818b6a56)
Location: include/net/tcp.h:722
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff818b6da6)
Location: include/net/tcp.h:722
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbbfb)
Location: include/net/tcp.h:722
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819053a9)
Location: include/net/tcp.h:732
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
```
In net/ipv4/tcp_output.c (ffffffff8190c295)
Location: include/net/tcp.h:732
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_timer.c (ffffffff8190c626)
Location: include/net/tcp.h:732
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911656)
Location: include/net/tcp.h:732
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8193a565)
Location: net/ipv4/tcp_output.c:51
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81935670-ffffffff819356ba: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199e8c0)
Location: net/ipv4/tcp_output.c:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81999970-ffffffff819999a8: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d53d0)
Location: net/ipv4/tcp_output.c:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819d0360-ffffffff819d0398: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac1d10)
Location: net/ipv4/tcp_output.c:53
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff81abd350-ffffffff81abd38b: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81acd780)
Location: net/ipv4/tcp_output.c:53
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff81ac8aa0-ffffffff81ac8adb: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab8940)
Location: net/ipv4/tcp_output.c:53
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff81ab39c0-ffffffff81ab39fb: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b75b60)
Location: net/ipv4/tcp_output.c:53
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff81b70840-ffffffff81b7087b: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d0545c)
Location: net/ipv4/tcp_output.c:53
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff81cffca0-ffffffff81cffce5: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81eca54c)
Location: net/ipv4/tcp_output.c:53
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
**Symbols:**

```
ffffffff81ec4d50-ffffffff81ec4d95: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f2908c)
Location: net/ipv4/tcp_output.c:53
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff81f236b0-ffffffff81f236f5: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81fedbcc)
Location: net/ipv4/tcp_output.c:53
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
```
**Symbols:**

```
ffffffff81fe7e10-ffffffff81fe7e55: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c88050)
Location: net/ipv4/tcp_output.c:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffff800010c82f50-ffff800010c82f9c: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d92128)
Location: net/ipv4/tcp_output.c:52
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
c0d92128-c0d921b0: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d94e9c)
Location: net/ipv4/tcp_output.c:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
c000000000d8e5c0-c000000000d8e628: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e92ee)
Location: net/ipv4/tcp_output.c:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffe0007e4c26-ffffffe0007e4c5e: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81975240)
Location: net/ipv4/tcp_output.c:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819701d0-ffffffff81970208: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192ed00)
Location: net/ipv4/tcp_output.c:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff81929ca0-ffffffff81929cd8: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819dfa10)
Location: net/ipv4/tcp_output.c:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819da9a0-ffffffff819da9d8: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tcp_mstamp_refresh(struct tcp_sock *tp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e96c0)
Location: net/ipv4/tcp_output.c:52
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
Direct callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
**Symbols:**

```
ffffffff819e4630-ffffffff819e4668: tcp_mstamp_refresh (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
